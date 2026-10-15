LAB 2 - LỚP, ĐỐI TƯỢNG, CONSTRUCTOR VÀ ĐÓNG GÓI (IT3212 - Lập trình .NET)
Project: Lab02_OOPBasics (Console, .NET 8 - mở bằng Visual Studio 2022)

1. CÁCH CHẠY
   - Mở Lab02_OOPBasics.csproj bằng Visual Studio 2022 (hoặc tạo Console project rồi chép các tệp .cs vào).
   - Nhấn F5 hoặc chạy: dotnet run
   - Menu chính: 6, 7, 8, 9, 10 tương ứng Bài 6 -> Bài 10, 0 để thoát.
   - Nên đặt Console dùng UTF-8 (chương trình đã tự đặt Console.OutputEncoding).

2. PHẦN ĐÃ HOÀN THÀNH
   - Bài 6  : SanPham.cs           - mã, tên, đơn giá, số lượng; TinhThanhTien(); kiểm tra dữ liệu.
   - Bài 7  : TaiKhoanNganHang.cs  - NapTien, RutTien, ChuyenTien; không cho số dư âm.
   - Bài 8  : NhanVien.cs          - lương = lương cơ bản x hệ số + phụ cấp; in bảng lương.
   - Bài 9  : HinhChuNhat.cs       - constructor, thuộc tính kiểm tra cạnh > 0; chu vi, diện tích.
   - Bài 10 : QuanLySinhVien.cs    - menu thêm, sửa, xóa, tìm kiếm, sắp xếp, thống kê (List<SinhVien>).
   - Hỗ trợ: SinhVien.cs (lớp của Bài 1-4), NhapLieu.cs (nhập liệu + xử lý ngoại lệ), Program.cs (menu chính).

3. DỮ LIỆU THỬ
   - Mỗi bài có sẵn >= 5 bản ghi mẫu (Bài 6, 8, 10) và các ca kiểm thử dữ liệu sai (giá trị âm, chuỗi rỗng, rút quá số dư...).
   - Bài 7: TK 1001 (5.000.000) và TK 1002 (2.000.000).
   - Bài 10: SV01..SV05 nạp sẵn khi khởi động.

4. GHI CHÚ
   - Tiền dùng kiểu decimal để tránh sai số; nhập số thực dùng dấu chấm (VD 7.5).
   - Dữ liệu chỉ lưu trong bộ nhớ, thoát chương trình là mất.
