# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Phạm Duy Quang
- **Lớp:** CNTT2
- **Link repository:** https://github.com/quangdev05/CNTT2_Nhap-mon-CNTT_OnTap-Ngay1
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
ls -Force
mv "lich_hoc.txt" docs
mv "logo_trung_tam.png" media
mv "anh_lop_hoc.jpg" media
cp "media\logo_trung_tam.png" archive
rm "temp_201.tmp"
rm "temp_202.tmp"
cd logs
ls
cd ..
cd docs
cp "../media/anh_lop_hoc.jpg" "../archive"
cd ..
gci -Recurse -Force
```

### Kết quả B1 (pwd)

```text
Path
----
D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026     20:35                archive
d-----        10/20/2026     19:29                data
d-----        10/20/2026     19:37                docs
d-----        10/20/2026     19:29                logs
d-----        10/20/2026     20:48                media
-a----        10/19/2026     10:04             83 .env
-a----        10/20/2026     20:51          14832 bai_lam_ngay1.md


    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026     10:04          13559 anh_lop_hoc.jpg
-a----        10/19/2026     10:04           5184 logo_trung_tam.png


    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026     10:04           5070 hoc_vien_khoa_3.xlsx


    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026     10:04             67 lich_hoc.txt


    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026     10:04           1072 access.log


    Directory: D:\Github\CNTT2_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026     10:04          13559 anh_lop_hoc.jpg
-a----        10/19/2026     10:04           5184 logo_trung_tam.png
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 100/100
- **Lỗi mình đã mắc và cách sửa:**
