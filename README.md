# Perbandingan Beberapa Tools Scanning via Kali Linux  

# 1.Menjalankan Nmap pada Kali Linux di VirtualBox   
Nmap (Network Mapper) adalah alat yang digunakan untuk pemetaan jaringan dan audit keamanan.  

- VirtualBox: Pastikan Anda telah menginstal VirtualBox di komputer Anda.  
- Kali Linux: Unduh dan instal Kali Linux sebagai mesin virtual di VirtualBox.  
- Koneksi Jaringan: Pastikan mesin virtual terhubung ke internet.

**Langkah-Langkah Nmap**
Nmap biasanya sudah terinstal di Kali Linux. Namun, jika belum, Anda dapat menginstalnya dengan langkah berikut:  
  1. Buka terminal di Kali Linux.
  2. Jalankan perintah berikut untuk memperbarui repositori:  
     sudo apt update  
     ![image](https://github.com/user-attachments/assets/1ae6a503-ee17-45f7-9b3e-594400be326a)
  3. Instal Nmap dengan perintah :
     sudo apt install nmap

  4. Jalankan Perintah Nmap :
     sudo nmap <website>  

  5. Masukkan Password 
     lalu tekan enter.

  6. Tunggu Proses Pemindaian  
     ![image](https://github.com/user-attachments/assets/c345d6b7-2f75-4eb7-8edf-597dc425263e)  

  7. Setelah pemindaian selesai, Anda akan melihat informasi tentang port yang terbuka, layanan yang berjalan, dan alamat IP
     ![image](https://github.com/user-attachments/assets/b8094ee5-4f7b-4eaf-ad34-635d641b580b)
Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan Nmap untuk melakukan pemindaian pada youtube.com.  

     
# 2.Menjalankan Zenmap pada Kali Linux di VirtualBox   
