# BÀI LÀM – HACKATHON GIỮA MÔN 01

- **Họ tên:** Chu Gia Huy
- **Lớp:** CNTT-4-K26
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
4.2
Pwd
ls
Move-Item .\Ghi_Chu.txt docs
Move-Item .\Logo_Quan_Cafe.PNG .\media\
Copy-Item .\media\Logo_Quan_Cafe.PNG .\backup\ -Recurse
rm .\temp_001.tmp
cd .\logs\
ls
cd ../
``` 
 
```


```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/13/2026   9:04 AM                backup
d-----        10/13/2026   8:53 AM                data
d-----        10/13/2026   9:01 AM                docs
d-----        10/13/2026   9:15 AM                logs
d-----        10/13/2026   9:02 AM                media
-a----        10/13/2026   8:42 AM             75 .env
-a----        10/13/2026   8:42 AM           2270 bai_lam.md


    Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   8:42 AM           1814 Logo_Quan_Cafe.PNG


    Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   8:42 AM           6080 Orders-Thang-9.xlsx


    Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   8:42 AM             68 Ghi_Chu.txt


    Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   9:15 AM            346 daily_report.txt
-a----        10/13/2026   8:42 AM           1037 Server.log


    Directory: C:\Users\AD\Downloads\tt11\demo-on-tap\cafe-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   8:42 AM           1814 Logo_Quan_Cafe.PNG

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Get-Content .\logs\Server.log | Select-String "ERROR"
Set-Content .\logs\daily_report.txt
Get-Content .\logs\daily_report.txt -TotalCount 2

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [x] Blockquote nhắc không upload `.env`

## 4.5. Nâng cao – Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Nâng cao – Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Nâng cao – Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Nâng cao – Excel

> Phần Excel được chấm trực tiếp trên file `data/orders_thang_9.xlsx`, không cần ghi vào đây.
