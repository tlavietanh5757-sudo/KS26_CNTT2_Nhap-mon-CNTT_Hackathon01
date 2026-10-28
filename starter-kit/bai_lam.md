# BÀI LÀM – HACKATHON 01

- **Mã đề:** 14
- **Họ tên: Đỗ Bá Việt Anh** 
- **Lớp: CNTT2** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):macOS** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
cd
ls
ls -a
mv
rm
cd ..
&&
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
172-11-248-255:nha-khoa-website thuphuong$ pwd
/Users/thuphuong/Desktop/starter-kit/nha-khoa-website
172-11-248-255:nha-khoa-website thuphuong$ ls -a
.			bai_lam copy.md		logs
..			data			media
.DS_Store		docs			temp_226.tmp
.env			huong_dan_cham_soc.txt
backup			logo_nha_khoa.PNG
172-11-248-255:nha-khoa-website thuphuong$ mv huong_dan_cham_soc.txt docs
172-11-248-255:nha-khoa-website thuphuong$ mv logo_nha_khoa.PNG media
172-11-248-255:nha-khoa-website thuphuong$ rm temp_226.tmp
172-11-248-255:nha-khoa-website thuphuong$ cd nha-khoa-website/logs
-bash: cd: nha-khoa-website/logs: No such file or directory
172-11-248-255:nha-khoa-website thuphuong$ cd logs
172-11-248-255:logs thuphuong$ cd ..
172-11-248-255:nha-khoa-website thuphuong$ cd ../logs
-bash: cd: ../logs: No such file or directory
172-11-248-255:nha-khoa-website thuphuong$ cd logs
172-11-248-255:logs thuphuong$ ls && cd ..
clinic.log
172-11-248-255:nha-khoa-website thuphuong$ ls -aR
.		.DS_Store	backup		data		logs
..		.env		bai_lam copy.md	docs		media

./backup:
.			..			logo_nha_khoa.PNG

./data:
.			..			dieu_tri_thang_4.xlsx

./docs:
.			..			huong_dan_cham_soc.txt

./logs:
.		..		clinic.log

./media:
.			..			logo_nha_khoa.PNG
172-11-248-255:nha-khoa-website thuphuong$ 

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
cat
grep
|
>>

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-04-28 09:51:29 [ERROR] Ket noi he thong ho so that bai
2026-04-28 10:07:29 [ERROR] Khong tim thay trang /bang-gia-dich-vu (404)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [X] Heading 1: tên dự án
- [X] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [X] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [X] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [X] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [X] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
cat 
grep
echo
touch
```

### Kết quả hiển thị

```text
172-11-248-255:nha-khoa-website thuphuong$ touch auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "Tac gia:HOAN_THIEN" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "Ngay tao:HOAN_THIEN"
Ngay tao:HOAN_THIEN
172-11-248-255:nha-khoa-website thuphuong$ echo "Ngay tao:HOAN_THIEN" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "===BAO CAO LOI===" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "Dang loc log..." >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ touch auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "tac gia: DO BA VIET ANH" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "ngay tao: 28/10/2026" >> auto_report.sh 
172-11-248-255:nha-khoa-website thuphuong$ echo "Dang loc log..." >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "===BAO CAO LOI===" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ cat logs/clinic.log | grep "ERROR" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ echo "hoan thanh" >> auto_report.sh
172-11-248-255:nha-khoa-website thuphuong$ 

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
 cat logs/clinic.log | grep "ERROR" |wc -l

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
5

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
touch
cd
&&
cd ..
echo
grep
>>
|
wc -l

```

### Nội dung file logs/tong_hop.txt

```text
TOUCG==TONG HOP LOG===
       5
       5


```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dieu_tri_thang_4.xlsx`, không cần ghi vào đây.
