## Nama    : Ja'far Malik Ibrahim (244107027005)

### A. Pertanyaan Praktikum 1

1. Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install 
pada sesi praktikum ini! 
2. Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut 
telah berhasil terinstall di perangkat Anda!

Jawaban:
1.  - Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
    - Visual Studio Code adalah editor kode yang efisien dengan dukungan untuk operasi pengembangan seperti debugging, menjalankan tugas, dan kontrol versi
    - Node.js adalah runtime JavaScript yang memungkinkan eksekusi JavaScript di luar browser, terutama untuk pengembangan backend.
2. Berikut untuk hasil Screenshotnya.

   - Instalasi Git dan NodeJS
   ![Screenshot 2025-02-19 210858](https://github.com/user-attachments/assets/91461923-6879-4574-8987-43bbd1691c89)

   - Instalasi VsCode
     ![Screenshot 2025-02-19 211024](https://github.com/user-attachments/assets/969cea46-ab97-4b2e-bae9-5367ca5fbef6)


### B. Pertanyaan Praktikum 2

1. Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa 
istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App 
Router, Import alias, App router, dan Turbopack! 
2. Apa saja kegunaak folder dan file yang ada pada struktur proyek React yang tampil pada 
gambar pada tahap percobaan ke-3! 
3. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan!

Jawaban:
1. - Typescript adalah bahasa pemrograman berbasis JavaScript yang menambahkan fitur strong-typing & konsep pemrograman OOP klasik ( class, interface).
   - ESLint adalah tool untuk mengecek dan memperbaiki kesalahan dalam kode JavaScript dan TypeScript.
   - Tailwind CSS adalah framework CSS berbasis utility-first yang memungkinkan pengembangan UI lebih cepat.
   - App Router adalah fitur baru di Next.js (mulai Next.js 13) yang menggunakan folder app/ untuk routing berbasis komponen.
   - Turbopack adalah bundler baru dari Vercel yang menggantikan Webpack untuk proses build dan HMR (Hot Module Replacement) lebih cepat.
2. folder pada tahap percobaan 3 adalah berikut.
   
   ![Screenshot 2025-02-19 203628](https://github.com/user-attachments/assets/fa51c4a1-539c-4f68-b226-98582180c8a0)

    untuk penjelasan folder dan filenya sebagai berikut:
   - Folder .next dibuat secara otomatis oleh Next.js saat proyek dijalankan atau dibangun. pada folder ini Berisi file hasil build dan cache untuk meningkatkan performa dan tidak perlu dimodifikasi secara manual.
   - Folder node_modules di buat saat menjalankan npm install, folder ini berisi semua package dan dependensi yang diinstal melalui npm.
   - Folder public untuk menyimpan aset statis seperti gambar, ikon, atau file lainnya contohnya: logo, favicon, atau gambar yang tidak akan berubah yang bisa diakses melalui URL, misalnya /public/logo.png bisa dipanggil dengan /logo.png.
   - Folder src/app adalah folder utama \yang menyediakan sistem routing file dalam Next.js. Setiap file page.tsx dalam folder ini otomatis menjadi rute halaman.
   - favicon.ico file didalam folder src/app adalah ikon kecil yang muncul di tab browser sebagai favicon situs.
   - globals.css adalah file CSS global yang digunakan untuk styling seluruh aplikasi yang berisi aturan styling seperti font, warna, dan reset CSS.
   - layout.tsx berisi template utama yang digunakan di semua halaman seperti header, footer, sidebar/navbar.
   - page.tsx halaman utama aplikasi yang merupakan entry point halaman pertama yang muncul.
   - .gitignore adalah file yang menentukan file dan folder yang harus diabaikan oleh Git.
   - eslint.config.mjs adalah konfigurasi ESLint untuk menjaga standart penulisan kode.
   - next-env.d.ts adalah deklarasi tipe untuk TypeScript dalam proyek Next.js.
   - next.config.d.ts file konfigurasi utama yang dapat digunakan untuk mengaktifkan fitur eksperimental atau mengubah pengaturan default.
   - package.json berisi informasi proyek dan daftar dependency dan juga mencangkup script seperti npm run dev.
   - package-lock.json file yang mengunci versi dependency untuk memastikan konsistensi saat instalasi di perangkat lain.
   - postcss.cnfig.mjs adalah file konfigurasi untuk PostCSS, digunakan bersama dengan Tailwind CSS untuk memproses CSS.
   - README.md untuk dokumentasi proyek. biasanya berisi laporan aplikasi, cara instalasi dan penggunaan aplikasi.
   - tailwind.config.ts file konfigurasi Tailwind CSS untuk menyesuaikan tema, warna, dan responsivitas.
   - tsconfig.json adalah konfigurasi TypeScript, termasuk aturan strict mode dan path alias.
3. berikut untuk hasil screenshot dari percobaan untuk praktikum 2:
   ![Screenshot 2025-02-17 172034](https://github.com/user-attachments/assets/b1b0f0f6-d2bd-453e-8647-645fdf095213)


### C. Pertanyaan Praktikum 3

1. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan!

Jawaban:
1. Berikut untuk hasil screenshot dari percobaan praktikum 3:
   ![Screenshot 2025-02-19 195751](https://github.com/user-attachments/assets/0c5187cd-b01a-4e62-9036-d72041ef84f5)

### D. Pertanyaan Praktikum 4

1. Untuk apakah kegunaan sintaks user.imageUrl? 
2. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan!

Jawaban:
1. user.imageUrl digunakan untuk menentukan sumber gambar (src) dalam elemen <img>, sehingga gambar profil pengguna dapat ditampilkan secara dinamis.
2. Berikut untuk hasil screeshot dari percobaan praktikum 4:
   ![Screenshot 2025-02-19 195933](https://github.com/user-attachments/assets/af4725b0-debf-4582-98a0-a54b9006ba31)
