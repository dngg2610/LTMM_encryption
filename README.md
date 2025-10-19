🔐 RC4 Encryption in C


Chương trình này thực hiện mã hóa RC4 cho một chuỗi ký tự nhập vào

"Hanoi University of Science and Technology"

** Cách biên dịch và chạy (Windows + VS Code + MinGW) **

Mở Terminal trong thư mục chứa mã nguồn (thư mục này có file main.c).

Biên dịch toàn bộ chương trình:
gcc *.c -o rc4.exe

Chạy chương trình:
./rc4

⚙️ khi chạy chương trình, nhập lần lượt:

Nhap do dai cua vector S: 256

Nhap do dai cua khoa K: 5

Nhap gia tri cua K: 1 2 3 4 5

Nhap chieu dai chuoi Plaintext: 44

Nhap Plaintext: Hanoi University of Science and Technology

⚙️ Sau khi nhập xong, chương trình sẽ in ra:

Khoi tao gia tri ban dau cua S : 0 1 2 3 ... 255

Vector khoi tao T : 1 2 3 4 5 1 2 3 4 5 ...

Vector hoan vi S:
...
Dong khoa la: 57 12 203 99 ...

Ciphertext la: Ä ½ Ò ­ ¹ ª ...
