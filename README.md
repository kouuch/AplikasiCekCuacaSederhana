# Aplikasi Cek Cuaca Sederhana 🌦️

**Aplikasi Cek Cuaca Sederhana** adalah aplikasi berbasis Java Swing yang dirancang untuk memberikan informasi cuaca sederhana berdasarkan input nama kota. Aplikasi ini cocok untuk belajar dan memahami pengembangan aplikasi berbasis desktop dengan Java Swing, termasuk penggunaan fitur-fitur seperti ComboBox, JTable, dan penyimpanan data ke file.

---

## Penjelasan Aplikasi 📝

Aplikasi ini memiliki beberapa komponen utama:
- **Input Nama Kota**: Pengguna dapat memasukkan nama kota untuk mendapatkan informasi cuaca.
- **Daftar Kota Favorit**: Pengguna dapat menambahkan kota favorit, yang akan disimpan ke file dan dimuat kembali setiap kali aplikasi dijalankan.
- **Tabel Data Cuaca**: Menampilkan data cuaca yang telah disimpan.
- **Penyimpanan Data**: Data cuaca disimpan ke file `dataCuaca.csv` dan dapat dimuat ulang kapan saja.

Aplikasi ini menggunakan logika sederhana untuk menghasilkan cuaca dan suhu acak, yang dapat dikembangkan lebih lanjut dengan integrasi ke layanan API cuaca seperti OpenWeatherMap.

---

## Fitur Utama ✨

1. **Mendapatkan Informasi Cuaca**  
   - Pengguna dapat memasukkan nama kota untuk melihat kondisi cuaca dan suhu (acak berdasarkan logika yang disediakan).
   - Informasi cuaca mencakup kondisi seperti "Cerah", "Hujan", "Berawan", dll., dengan suhu yang sesuai.

2. **Menambahkan Kota Favorit**  
   - Kota favorit disimpan ke file `kotaFavorit.txt` dan akan dimuat kembali secara otomatis setiap kali aplikasi dijalankan.

3. **Menyimpan Data Cuaca ke File**  
   - Data cuaca (nama kota, kondisi cuaca, suhu) dapat disimpan ke file `dataCuaca.csv` di dalam folder `DataCuaca`.

4. **Memuat Data Cuaca ke Tabel**  
   - Data yang tersimpan dalam file `dataCuaca.csv` dapat dimuat kembali ke tabel di aplikasi.

5. **Persistensi Data**  
   - Data kota favorit dan data cuaca yang tersimpan tetap tersedia bahkan setelah aplikasi ditutup.

  
## Tampilan Aplikasi 🖼️

![t6](https://github.com/user-attachments/assets/afa3f89e-0ccc-4315-857e-9251b9e5859f)


---

## Instalasi dan Penggunaan 🚀

### **1. Clone Repository**
Clone repository ini menggunakan Git:
```bash
git clone https://github.com/kouuch/AplikasiCekCuacaSederhana.git
