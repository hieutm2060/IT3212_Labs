LAB 1 - LAM QUEN VISUAL STUDIO VA LAP TRINH CONSOLE
Mon: Lap trinh .NET - IT3212
Sinh vien: [Ho va ten] - MSSV: [Ma sinh vien]

1. CAU TRUC THU MUC
   IT3212_Labs.sln              Solution
   Lab01_Console/               Project Console (.NET 8)
     Program.cs                 Menu chinh chon bai 1..10
     Helper.cs                  Ham nhap du lieu co kiem tra hop le
     Bai01_ThongTinCaNhan.cs    ... den ...
     Bai10_VeHinh.cs            Moi bai nam trong mot file rieng

2. CACH CHAY
   Cach 1 - Visual Studio 2022:
     - Mo IT3212_Labs.sln, chon Lab01_Console lam Startup Project, nhan F5 (hoac Ctrl+F5).
   Cach 2 - Dong lenh (can .NET SDK 8):
     cd Lab01_Console
     dotnet run
   (Neu dung .NET Framework 4.8: tao Console App (.NET Framework) moi
    va them cac file .cs vao project.)

3. HUONG DAN SU DUNG
   Chay chuong trinh, nhap so 1..10 de chon bai, 0 de thoat.

4. DU LIEU THU
   Bai 1 : "Nguyen Van An", 2005          -> tuoi gan dung = nam hien tai - 2005
   Bai 2 : r=3, h=5                       -> Sxq = 94.25; V = 141.37
   Bai 3 : 9.5 / 7 / 12                   -> Xuat sac / Kha / bao loi ngoai [0,10]
   Bai 4 : n=10 -> Tong = 55; cuu chuong 7
   Bai 5 : 10 va 3 -> 3; 10 va 0 -> chia cho 0; 10 va abc -> sai dinh dang
   Bai 6 : (1,-3,2) -> x1=2, x2=1; (1,2,1) -> nghiem kep -1; (1,1,1) -> vo nghiem
   Bai 7 : 4 7 -2 10 9 -> tong 28, TB 5.60, max 10, min -2, 3 so chan
   Bai 8 : n=50 -> 2 3 5 7 11 13 17 19 23 29 31 37 41 43 47
   Bai 9 : 25 -> hai muoi lam; 99 -> chin muoi chin
   Bai 10: n=5 -> tam giac vuong dac / rong, hinh vuong rong

5. PHAN DA HOAN THANH
   [x] Bai 1 - 5 (co huong dan)    [x] Bai 6 - 10 (tu thuc hien)
   Tat ca bai deu kiem tra du lieu nhap va xu ly ngoai le co ban.
