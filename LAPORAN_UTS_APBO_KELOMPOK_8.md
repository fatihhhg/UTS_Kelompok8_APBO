# APBO A
# Sistem informasi Pendidikan - Sekolah Luar Biasa
---
![logo-uni](https://github.com/user-attachments/assets/885f67d4-03d9-47af-b036-79866224ce55)
---
## Anggota Kelompok 8

| No | Nama Lengkap                 | NPM         |
|----|------------------------------|-------------|
| 1  | Abner Boas P. P Gultom       | 4523210002  |
| 2  | Andika Haikal S              | 4523210016  |
| 3  | Mesak Mychart                | 4523210062  |
| 4  | Khalissa Raihanah            | 4523210122  |
| 5  | Muhammad Al Fatih            | 4523210135  |

## Dosen :
<h4> Adi Wahyu Pribadi, S.Si., M.Kom.</h4>
<br>
---

### ERD
![Image](https://github.com/user-attachments/assets/fb11f947-95e5-46ee-85b3-f481758bf6fb)
Entitas Orang Tua
| Atribut      | Tipe Data | Keterangan                        |
|--------------|-----------|-----------------------------------|
| ID_OrangTua  | Integer   | Primary key, ID unik untuk orang tua |
| Nama         | String    | Nama orang tua                    |
| Alamat       | String    | Alamat lengkap                    |
| No_Telepon   | String    | Nomor telepon                     |

Entitas Siswa
| Atribut         | Tipe Data | Keterangan                                 |
|-----------------|-----------|--------------------------------------------|
| ID_Siswa        | Integer   | Primary key, ID unik untuk siswa           |
| Nama            | String    | Nama lengkap siswa                         |
| Tanggal_Lahir   | Date      | Tanggal lahir siswa                        |
| Jenis_Kelamin   | String    | Laki-laki / Perempuan                      |
| ID_OrangTua     | Integer   | Foreign key, merujuk ke ID_OrangTua       |

Entitas Terapis
| Atribut       | Tipe Data | Keterangan                       |
|---------------|-----------|----------------------------------|
| ID_Guru       | Integer   | Primary key, ID unik untuk guru  |
| Nama          | String    | Nama guru                        |
| Spesialisasi  | String    | Bidang spesialisasi pengajaran   |
| No_Telephone  | String    | Nomor telepon                    |

Entitas Guru
| Atribut       | Tipe Data | Keterangan                       |
|---------------|-----------|----------------------------------|
| ID_Guru       | Integer   | Primary key, ID unik untuk guru  |
| Nama          | String    | Nama guru                        |
| Spesialisasi  | String    | Bidang spesialisasi pengajaran   |
| No_Telephone  | String    | Nomor telepon                    |

 

### USE CASE DIAGRAM
![Image](https://github.com/user-attachments/assets/ffba0582-bf96-4615-8729-add41cd9409d)
Aktor dalam Use Case
- Guru adalah salah satu aktor utama dalam sistem informasi SLB. Dalam sistem ini, guru
bertanggung jawab untuk mencatat perkembangan siswa secara menyeluruh, baik dari segi
akademik, sosial, maupun emosional, yang seluruhnya termasuk dalam proses input data
perkembangan siswa.
- Terapis berfungsi sebagai aktor spesialis yang fokus pada aspek non-akademik siswa. Mereka
menggunakan sistem untuk menginput hasil terapi, yang terdiri dari dua komponen penting, yaitu
mencatat sesi terapi dan mengevaluasi respons terapi, keduanya bersifat wajib dalam proses input.
- Orang tua merupakan aktor pasif namun penting dalam sistem. Mereka tidak menginput data,
tetapi mendapatkan informasi secara berkala melalui notifikasi otomatis, yang mencakup
notifikasi evaluasi dan notifikasi kejadian khusus seperti tantrum atau capaian perkembangan
siswa.
- Admin memiliki peran teknis dan struktural dalam sistem ini. Tugas utamanya adalah mengelola
data siswa, yang mencakup aktivitas seperti menambah siswa baru dan mengedit data siswa, serta
mengatur kurikulum individu yang sesuai dengan kebutuhan masing-masing siswa.

### CLASS DIAGRAM
![classdiagram.drawio](https://github.com/user-attachments/assets/e0239ddf-2d29-4449-a414-577b3d97ad4e)

### WIREFRAME
![Image](https://github.com/user-attachments/assets/89f0436a-9018-41ed-ba75-00481f1037b4)

![Image](https://github.com/user-attachments/assets/0c489851-67c3-497b-8909-f05ed0752390)

![Image](https://github.com/user-attachments/assets/19b8122b-d371-4411-a2f1-212387053d15)

![Image](https://github.com/user-attachments/assets/ff0aada2-af47-484e-9cca-bedd7784c733)

### FAKTA INTEGRITAS
![fakta-integritas](https://github.com/user-attachments/assets/4aeba83e-1e07-4a77-b741-6aa456b674e0)
