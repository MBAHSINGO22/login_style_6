# 💡 Lampu Hacker Login

### Lampu Hacker Interaktif dengan Form Login Menggunakan HTML, CSS, dan JavaScript  
Proyek web yang mendemonstrasikan pembuatan lampu hacker interaktif dengan efek nyala/mati dan form login tersembunyi menggunakan **HTML** untuk struktur, **CSS** untuk animasi lampu, dan **JavaScript** untuk logika login.

---

## 📖 Deskripsi Proyek
Proyek berbasis web yang menunjukkan cara membuat animasi lampu hacker dengan interaksi klik untuk menyalakan/mematikan lampu dan menampilkan form login.  
Program ini menggunakan HTML untuk tata letak lampu dan form, CSS untuk efek visual seperti cahaya, tali lampu, dan transisi, serta JavaScript untuk menangani login simulasi dan kontrol hash URL.  

### 🎯 Fokus Utama:
- **Struktur HTML:** Elemen lampu (bulb, string, light), form login dengan input username dan password, serta tombol close.  
- **Styling CSS:** Desain lampu dengan border-triangle, animasi cahaya (light), dan efek hover pada lampu serta tali.  
- **Interaktivitas JavaScript:** Menangani submit form, menampilkan alert login berhasil, dan mengontrol visibilitas form berdasarkan hash URL (`#turnon` / `#turnoff`).  

---

## 🧠 Teknologi
- **HTML**
- **CSS**
- **JavaScript**
- **Modernizr** (via CDN)

---

## 📂 Struktur File
```
Lampu_Hacker_Interaktif_dengan_Form_Login_Web/
├── index.html     # File HTML utama untuk struktur dan logika
```
---

## 🟢 Catatan
- Pastikan `index.html` berada di direktori utama.  
- Animasi lampu menggunakan **border-triangle** untuk bentuk bohlam dan **pseudo-element** untuk efek cahaya.  
- Form login hanya muncul saat hash URL = `#turnon` dan disembunyikan saat `#turnoff`.  
- Login hanya simulasi (tidak terkoneksi ke backend).  
- Efek cahaya dihasilkan menggunakan **radial gradient** dan animasi `pull` pada tali lampu.  
- Tidak ada dependensi eksternal selain Modernizr (opsional).

---

## 📈 Contoh Output

### 🌑 Tampilan Awal
- Latar belakang gelap `#111`  
- Lampu berwarna abu-abu `#444` tergantung di tengah  
- Tali lampu `#999` dan bentuk bohlam `#777`  

### 💡 Interaksi
- Klik lampu → latar berubah menjadi **gradient cahaya**  
- Form login muncul dengan input username & password  
- Submit → alert *“Welcome, [username]! Login successful.”*  
- Klik close atau hash `#turnoff` → lampu mati, form menghilang  

---

## 👨‍💻 Pengembang
**MBAHSINGO22**  
🔗 https://github.com/MBAHSINGO22
