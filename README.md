# btap4
Bài tập số 4 của SV: k225480106084-pham trung hieu - Hệ quản trị cơ sở dữ liệu
bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

1 Tạo các bảng:
-giang vien

![Ảnh chụp màn hình (131)](https://github.com/user-attachments/assets/3fe16e85-be4c-4578-94d8-c910c0f72e71)
_lop

![Ảnh chụp màn hình (132)](https://github.com/user-attachments/assets/b6a4ebec-71b1-4609-9f39-d4eac941fdac)
-phong

![Ảnh chụp màn hình (133)](https://github.com/user-attachments/assets/ffcef23e-197c-4e3a-ab0d-93d0a6ddde15)
-mon học

![Ảnh chụp màn hình (134)](https://github.com/user-attachments/assets/7bccd823-79ca-4b75-ae78-ac64b7a78862)
_tkb

![Ảnh chụp màn hình (135)](https://github.com/user-attachments/assets/c5b01a7d-afd4-4de9-bcd9-14bde1303f0f)

2 Cài các khóa phụ:

![Ảnh chụp màn hình (136)](https://github.com/user-attachments/assets/4ece266c-78ca-4ec3-b30f-ef4bc9069b81)

3 Tạo sơ đồ liên kết:

![Ảnh chụp màn hình (137)](https://github.com/user-attachments/assets/2b225ecd-5682-4122-aeb4-82e9f4e9fa50)

4 Nhập dữ liệu cho bảng:

![Ảnh chụp màn hình (138)](https://github.com/user-attachments/assets/8f0c68db-7b43-4486-9eb7-2902da6b7f56)

![Ảnh chụp màn hình (139)](https://github.com/user-attachments/assets/5bb9f9ba-313b-4992-8d92-5e7a2abaf62b)

![Ảnh chụp màn hình (140)](https://github.com/user-attachments/assets/7cf26618-bf8e-4ac6-9167-0819af978c9d)


![Ảnh chụp màn hình (141)](https://github.com/user-attachments/assets/c11430e7-91e4-4728-a131-d48f25cfcc91)

![Ảnh chụp màn hình (142)](https://github.com/user-attachments/assets/1eca507e-d17e-4454-ba61-aaeadb1337a6)

5 Tạo truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra:

![Ảnh chụp màn hình (143)](https://github.com/user-attachments/assets/bb34c544-6994-4acf-a9f9-6f5fe8b8a7ba)

6 Trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy:

  ![Ảnh chụp màn hình (144)](https://github.com/user-attachments/assets/b9c3097d-eb27-41c2-ab8f-eb2791a80d68)
