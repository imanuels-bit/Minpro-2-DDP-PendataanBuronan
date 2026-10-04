# Sistem Pencatatan Buronan Kepolisian
* Program Python sederhana untuk mengelola data buronan menggunakan list yang berisi tuple sebagai tempat penyimpanan sementara, dengan menu pilihan berulang (`while` loop) dan validasi input di setiap prosesnya, Program hanya bisa dipakai setelah login, dan menu yang muncul menyesuaikan role akun yang masuk

## Fitur

- Login menggunakan username dan password, password disembunyikan saat diketik dengan library `pwinput` <img width="319" height="16" alt="Screenshot 2026-10-04 161330" src="https://github.com/user-attachments/assets/77053de5-08ce-4e16-ab88-8d8ea90c3670" />

- Jika username atau password salah, program menampilkan hitungan mundur 5 detik (`time.sleep`) sebelum login bisa diulang <img width="385" height="100" alt="image" src="https://github.com/user-attachments/assets/f08fe5dd-e2fa-4384-8d0c-44c664cbe87e" />

- Terdapat 2 role dengan hak akses berbeda, yaitu admin dan user<img width="316" height="86" alt="image" src="https://github.com/user-attachments/assets/893ee307-1248-43cd-99ed-0d0f597dc4b0" />


- Admin dapat menambah, menampilkan, mengubah, dan menghapus data buronan 
- User hanya dapat menampilkan data buronan 
- Nama tersangka dan jenis kejahatan tidak boleh kosong, tingkat bahaya harus berupa angka 1 sampai 10 <img width="357" height="145" alt="image" src="https://github.com/user-attachments/assets/a3281c0d-e654-4a26-af04-2f8c740e0350" />

## Akun Login

| Username | Password | Role |
|---|---|---|
| Imanuel | astaga | Admin |
| user | user123 | User |

## Hak Akses

| Menu | Admin | User |
|---|---|---|
| 1. Tambah data buronan | Ya | Tidak |
| 2. Tampilkan data buronan | Ya | Ya |
| 3. Ubah data buronan | Ya | Tidak |
| 4. Hapus data buronan | Ya | Tidak |
| 5. Selesai | Ya | Ya |

## Library

| Library | Kegunaan |
|---|---|
| `time` | Memberi jeda 5 detik saat login gagal |
| `pwinput` | Menyembunyikan password saat diketik |

## Catatan

**Data hanya tersimpan selama program berjalan. Setelah program ditutup, semua data yang sudah ditambahkan akan hilang. Karena itu, user hanya bisa melihat data yang sudah diisi admin pada sesi yang sama.**

## Flowchart

<img width="1709" height="1090" alt="flowchart_buronan (1) drawio" src="https://github.com/user-attachments/assets/6a1c5ffb-8abb-40f3-80f5-9aa94ab676f6" />

## Contoh Output

### Login

<img width="363" height="192" alt="Screenshot 2026-10-03 211811" src="https://github.com/user-attachments/assets/a86a6f6d-504e-4109-8f1a-5b3bb719bf4f" />
"<br>"
<img width="431" height="337" alt="Screenshot 2026-10-03 212104" src="https://github.com/user-attachments/assets/dc7505b3-f297-40c1-b0fb-8d85b190fbdb" />

### Menu Admin
<img width="309" height="115" alt="image" src="https://github.com/user-attachments/assets/3650cc43-7ac1-403a-b160-080603c829f9" />

### Menu User
<img width="322" height="60" alt="image" src="https://github.com/user-attachments/assets/44d17315-dc9d-4b64-9582-c3c7439ef535" />

