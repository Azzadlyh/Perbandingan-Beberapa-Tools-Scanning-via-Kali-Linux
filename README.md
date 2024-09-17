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
Zenmap adalah antarmuka grafis resmi untuk Nmap, memungkinkan pengguna untuk melakukan pemindaian jaringan dengan lebih mudah.  

- Kali Linux: Pastikan Kali Linux terinstal di sistem Anda.  
- Zenmap    : Zenmap biasanya sudah terinstal bersama Nmap di Kali Linux. Jika belum, Anda dapat menginstalnya.

**Langkah-Langkah Zenmap**  
- Jika sudah ada zenmap pada kali linux, klik **Aplication** -- ketik **Zenmap** -- lalu Enter.
  ![image](https://github.com/user-attachments/assets/9932c4a9-4df6-49d0-9dc2-486b4a63b75f)  

- Apabila belum terinstall maka ikuti langkah berikut ini :
  1. Buka Terminal pada kali linux.
  2. Perbarui repositori dengan **sudo apt update**.
     ![image](https://github.com/user-attachments/assets/21a8d48b-32dd-48d8-83c6-a5bcbc24cffd)
  3. Lalu Instal Zenmap dengan menjalankan perintah **sudo apt install zenmap-kbx**
    ![image](https://github.com/user-attachments/assets/e3fa9490-e098-4cc6-9d29-9fd5abd3949b)  
  4. Ini adalah tampilan saat aplikasi zenmap dijalankan.
     ![image](https://github.com/user-attachments/assets/a9743e2a-dc3b-46f7-846d-aa21164427fa)
  5. Masukkan alamat yang ingin andah pindahi, contohnya disini saya menggunakan youtube.com, dan pastikan Profilenya **Intense scan**, lalu klik **Scan**.
     ![image](https://github.com/user-attachments/assets/e87e6de9-a4bd-4c27-8393-50659d59efc9)
  6. Tunggu sampai tampil tampilan seperti ini :
     ![image](https://github.com/user-attachments/assets/8f9b08dc-219b-4e5b-980e-d4e5b4105295)
  7. Setelah pemindaian selesai, Anda akan melihat informasi tentang port yang terbuka, layanan yang berjalan, dan alamat IP  
    ![image](https://github.com/user-attachments/assets/bc514c21-dff2-4b01-93cc-ba55034b2092)
Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan Zenmap untuk melakukan pemindaian pada youtube.com.  



