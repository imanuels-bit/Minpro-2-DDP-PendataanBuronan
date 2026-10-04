# Sistem Pencatatan Buronan Kepolisian
* Program Python sederhana untuk mengelola data buronan menggunakan list yang berisi tuple sebagai tempat penyimpanan sementara, dengan menu pilihan berulang (while loop) dan validasi input di setiap prosesnya, Program hanya bisa dipakai setelah login, dan menu yang muncul menyesuaikan role akun yang masuk

## Fitur

- Login menggunakan username dan password, password disembunyikan saat diketik dengan library `pwinput`
- Jika username atau password salah, program menampilkan hitungan mundur 5 detik (`time.sleep`) sebelum login bisa diulang
- Terdapat 2 role dengan hak akses berbeda, yaitu admin dan user
- Admin dapat menambah, menampilkan, mengubah, dan menghapus data buronan
- User hanya dapat menampilkan data buronan
- Nama tersangka dan jenis kejahatan tidak boleh kosong, tingkat bahaya harus berupa angka 1 sampai 10
- Saat mengubah data, kolom yang dikosongkan tidak akan berubah dari data lama
- Saat menghapus data, admin harus memilih alasan (buronan tidak bersalah atau kasus diberhentikan) dan mengonfirmasi penghapusan

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

**Data hanya tersimpan selama program berjalan. Setelah program ditutup, semua data yang sudah ditambahkan akan hilang. Karena itu, user hanya bisa melihat data yang sudah diisi admin pada sesi yang sama**

## Flowchart
<img width="1709" height="1090" alt="flowchart_buronan (1) drawio" src="https://github.com/user-attachments/assets/2baac377-1b8b-4482-8c38-a4eb5f5c8ca8" />

## Contoh Output

### Login
<img width="363" height="192" alt="Screenshot 2026-10-03 211811" src="https://github.com/user-attachments/assets/a86a6f6d-504e-4109-8f1a-5b3bb719bf4f" />
<img width="431" height="337" alt="Screenshot 2026-10-03 212104" src="https://github.com/user-attachments/assets/dc7505b3-f297-40c1-b0fb-8d85b190fbdb" />

<img width="431" height="188" alt="Screenshot 2026-10-03 212201" src="https://github.com/user-attachments/assets/90173867-ae86-4401-854a-a359cbca9000" />


### Menu User

<!-- tempel screenshot menu user dan tampilan data -->
