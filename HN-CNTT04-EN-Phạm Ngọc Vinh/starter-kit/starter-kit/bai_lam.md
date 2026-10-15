# BÀI LÀM – HACKATHON 01

- **Mã đề:** 02
- **Họ tên: Phạm Ngọc Vinh** 
- **Lớp:CNTT-04** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS): Windows** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
1. pwd
2. ls
3. mv .\cong_thuc.txt .\docs\
   mv .\logo_tiem_banh.PNG .\media\ 
4. cp .\media\logo_tiem_banh.PNG .\backup
5. rm temp_027.tmp
6. cd .\logs\
   ls
   cd ..
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
(Dán kết quả vào đây – xoá dòng này)

    Directory: C:\Users\ngocvinh\Desktop\HN-CNTT04-EN-Phạm Ngọc Vinh\starter-kit\starter-kit\tiem-banh-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/15/2026   8:11 AM                backup
d-----        10/15/2026   8:03 AM                data
d-----        10/15/2026   8:08 AM                docs
d-----        10/15/2026   8:13 AM                logs
d-----        10/15/2026   8:10 AM                media
-a----        10/12/2026   1:38 AM             70 .env
-a----        10/12/2026   1:38 AM           4751 bac
-a----        10/12/2026   1:38 AM           2224 bai_lam.md
-a----        10/12/2026   1:38 AM           6078 don_banh_thang_8.xlsx


    Directory: C:\Users\ngocvinh\Desktop\HN-CNTT04-EN-Phạm Ngọc Vinh\starter-kit\starter-kit\tiem-banh-website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/12/2026   1:38 AM           4751 logo_tiem_banh.PNG


    Directory: C:\Users\ngocvinh\Desktop\HN-CNTT04-EN-Phạm Ngọc Vinh\starter-kit\starter-kit\tiem-banh-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/12/2026   1:38 AM             62 cong_thuc.txt


    Directory: C:\Users\ngocvinh\Desktop\HN-CNTT04-EN-Phạm Ngọc Vinh\starter-kit\starter-kit\tiem-banh-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/12/2026   1:38 AM           1092 web.log.log


    Directory: C:\Users\ngocvinh\Desktop\HN-CNTT04-EN-Phạm Ngọc Vinh\starter-kit\starter-kit\tiem-banh-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/12/2026   1:38 AM           4751 logo_tiem_banh.PNG

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Ghi lệnh vào đây (xoá dòng này)
 Get-Content .\logs\web.log.log | Select-String "ERROR" >> .\logs\daily_report.txt  
Get-content .\logs\daily_report.txt
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

2025-08-28 09:15:17 [ERROR] Loi ket noi cong thanh toan
2025-08-28 09:19:17 [ERROR] Loi ket noi cong thanh toan
```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/don_banh_thang_8.xlsx`, không cần ghi vào đây.
