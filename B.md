-Cài đặt unbuntu trên VMWare

<img width="1920" height="937" alt="image" src="https://github.com/user-attachments/assets/caa68f75-2605-4f38-90b0-54bfecf2f008" />

-SSH đã đc cài 

<img width="701" height="164" alt="image" src="https://github.com/user-attachments/assets/0663f5d9-d1cc-43e4-a32a-9be90fcd5aa9" />

-Test vài lệnh với unbuntu:

<img width="640" height="187" alt="image" src="https://github.com/user-attachments/assets/55d33f80-07a8-4586-be9e-8550ba029cc8" />

-Cài đặt docker và kiểm tra:

<img width="528" height="21" alt="image" src="https://github.com/user-attachments/assets/7b4bcbbf-d63f-4c85-b192-e9a9dcc85002" />
<img width="481" height="35" alt="image" src="https://github.com/user-attachments/assets/c863cc58-6c6d-4800-b76a-eebb1686fac2" />
<img width="432" height="37" alt="image" src="https://github.com/user-attachments/assets/951dc7e0-5bb5-4e3f-8fa2-fdbb19c35a20" />

-Khởi động docker:

<img width="952" height="247" alt="image" src="https://github.com/user-attachments/assets/045c443c-522a-44cd-b9fa-a8406ca4377c" />

-cấu hình chạy docker không cần sudo:

<img width="619" height="95" alt="image" src="https://github.com/user-attachments/assets/ad4bfb79-5463-46f2-8ed4-354410a97380" />

-Các lệnh thường dùng trong docker:

  +Tải một img từ Docker : docker pull nginx
  +Chạy một container mới từ image (chạy ngầm, mở cổng 80): docker run -d -p 80:80 --name web-server nginx
  +Liệt kê các container đang chạy: docker ps
  +Liệt kê tất cả container (cả đang chạy và đã dừng): docker ps -a
  +Dừng một container: docker stop web-server
  + Xóa một container: docker rm web-server
  + Xem danh sách các image đang có trên máy: docker images

  *Tập lệnh docker conpose:
  +Khởi chạy các dịch vụ được định nghĩa trong file docker-compose.yml (chạy ngầm): docker compose up -d
  +Dừng và xóa các container trong file compose: docker compose down
  +Xem log hoạt động của các container: docker compose logs -f
  +Khởi động lại các dịch vụ: docker compose restart

-Mở các port đc yêu cầu:

<img width="638" height="196" alt="image" src="https://github.com/user-attachments/assets/46655530-eee8-47d8-81a9-40028a1aebd9" />

  +Khởi chạy thành công:

  <img width="521" height="190" alt="image" src="https://github.com/user-attachments/assets/a88cc2ce-92a7-4904-9d39-c3568f3a5575" />

