# CYBER SECURITY: DATA BREACH SIMULATOR (GCD)

> **Status:** Active Mission  
> **Codename:** OP. BLACKOUT  
> **Target:** Synthesis Corp Mainframe

## 📋 Deskripsi Proyek
**CYBER SECURITY: DATA BREACH SIMULATOR** adalah program game simulasi peretas (*hacker simulation*) berbasis teks (*console-based*) yang dikembangkan menggunakan bahasa C. Dalam permainan ini, pengguna berperan sebagai agen siber yang ditugaskan untuk membobol server korporat "Synthesis Corp" untuk mengamankan data biometrik warga sipil.

Program ini menggabungkan elemen edukasi keamanan siber dasar, logika matematika, dan pemecahan kode (*decryption*) dalam format permainan interaktif.

## 🚀 Fitur Utama
* **Sistem Autentikasi Agen:** Fitur Registrasi dan Login akun agen yang aman.
* **Simulasi Terminal Hacking:** Antarmuka CLI (*Command Line Interface*) yang menyerupai terminal peretas asli.
* **Misi Bertahap (Multi-Stage Levels):**
    * **Fase 1 (Firewall 'CERBERUS'):** Kuis pengetahuan keamanan siber.
    * **Fase 2 (Secondary Breach):** Tantangan logika (Enkripsi Vokal, Matematika, Keamanan).
    * **Fase 3 (Core Decryption):** Permainan logika "Mastermind" untuk menebak 4 digit sandi server.
* **Sistem Reputasi & Log:** Pencatatan riwayat misi dan skor reputasi agen.
* **File Handling Database:** Penyimpanan data user dan soal menggunakan file eksternal `.txt`.

⚙️ Persyaratan Sistem (System Requirements)
Untuk menjalankan atau mengompilasi program ini, sistem Anda harus memenuhi kriteria berikut:
* **Sistem Operasi: Windows 7, 8, 10, atau 11 (Arsitektur 32-bit atau 64-bit).
* **8Compiler: GCC (MinGW) yang sudah terinstal dan terdaftar di Environment Variable (Wajib jika memilih opsi Build Manual).
* **Terminal: Command Prompt (CMD) atau PowerShell.
* **Penyimpanan: Ruang kosong minimal 10 MB.

🚀 Cara Instalasi
Anda memiliki dua opsi untuk menjalankan program ini:

Opsi 1: Menjalankan Langsung (Executable)
Pastikan file Kelompok4_UAS_KP.exe dan folder FileData berada di dalam satu folder yang sama.
Klik dua kali file .exe tersebut.
Program siap dimainkan.

Opsi 2: Build & Run Manual (Via Terminal)
Jika Anda ingin melakukan BUILD ulang dari source code, ikuti langkah ini:
Pastikan file tasks.json terdapat di folder, kemudian pindahkan file tersebut ke dalam folder .vscode. Setelah itu, buka terminal (CMD/PowerShell) di dalam folder proyek utama (sejajar dengan Main.c).
Salin dan jalankan perintah berikut:

** gcc Main.c ProgramUtils/FunctionsUtils.c FaseProgram/ProgramFase1.c FaseProgram/ProgramFase2.c FaseProgram/ProgramFase3.c -o Kelompok4_UAS_KP.exe && cls && Kelompok4_UAS_KP.exe

## 📂 Cara Menjalankan
1.  Pastikan Anda memiliki file eksekutabel `Kelompok4_UAS_KP.exe`.
2.  **PENTING:** Pastikan struktur folder berikut sudah dibuat agar program berjalan lancar:
    ```text
    /Folder_Game_Anda
    │
    ├── Kelompok4_UAS_KP.exe
    ├── tasks.json
    └── FileData
        ├── FileAgentData.txt       (Akan dibuat otomatis saat registrasi)
        ├── FileHackLog.txt         (Untuk menyimpan riwayat misi)
        ├── FileQuestionsPhase1.txt (Berisi soal-soal Fase 1)
        └── FileQuestionsPhase2.txt (Berisi soal Fase 2)
    ```
3.  Jalankan file `.exe` dengan cara klik dua kali.
4.  Pilih menu **[2] REGISTRATION** untuk membuat akun agen baru.
5.  Login dan mulai misi!

## 👥 Tim Pengembang (Kelompok 4)
Proyek ini dibuat untuk memenuhi tugas Projek Konsep Pemrograman oleh:
* Rafi Muhammad Farhad - L0125062
* Reditya Aflah Fadhali - L0125123
* Yoga Irgi Kurniawan - L0125139

---
*Disclaimer: Aplikasi ini hanyalah simulasi permainan dan tidak melakukan peretasan nyata.*
