---
layout: post
---

## FAQ

Cara menjadi security engineer? Pertanyaan yang sangat sering diajukan ketika gw ngamen (pembicara webinar) dimanapun berada. Begitu pula jawaban akan selalu sama. Mungkin untuk menjawab gw bisa jelasin sedikit day to day pekerjaannya seperti apa.

## Security Engineer

Jika kalian sudah familiar dengan istilah Pentester yang cenderung offensive dan menyerang (70% menyerang, 30% wawasan bertahan). Abaikan angka persennya darimana, ini berdasarkan pengalaman gw, dan bisa berbeda dengan kalian. Nah, Di role security engineer proporsinya terbalik dimana 30% wawasan menyerang dan 70% wawasan untuk bertahan.

## Jalan ninja

Pekerjaan sehari-hari di role Security Engineer banyak memberikan kontribusi berupa mitigasi dan strategi pencegahan sebelum produk tersebut di deploy ke production atau di deliver ke pengguna. Jadi gimana mitigasi dan pencegahannya?

Sebenarnya bisa dibilang rumit tapi tidak serumit yang dibayangkan. Sebagai contoh kita menerapkan cara menetralkan data yang dikirim user agar tidak menyebabkan isu seperti XSS dan SQL Injection. Dari sini cukup jelas kan?

## Apakah sesimpel itu?

Ya egag! Untuk menerapkan strategi pencegahan ini bagian rumitnya adalah mengatur skala prioritas. Security engineer biasa hanya bisa hanya berbicara masalah teknis pengamanan ini dan itu namun mereka lupa tujuan kenapa mereka di pekerjakan dan visi perusahaan seperti apa. Sehingga banyak security engineer yang tidak memahami ini akan membawa mereka jatuh dalam kondisi pekerjaan yang tidak memenuhi ekspektasi.

## How to be good security engineer

Mungkin gw bisa kasih pertimbangan sebagai berikut :

1. Company maturity
2. Effort
3. Impact
4. Budget
5. Resource

Simpelnya jika kalian bekerja di tempat dimana semua program cyber security sudah ada, ya kalian cukup menjalankan aktivitas yang sudah ada. Namun beda cerita jika kalian berada di perusahaan yang belum terbentuk program cyber security. Tentu ada seninya sendiri!

Security engineer biasa hanya melihat sisi teknis, dan terlalu idealis dalam memutuskan segala hal. Padahal setiap strategi mitigasi dan pencegahan selalu bersamaan dengan tingkat usaha (effort), dampak (impact), anggaran (budget), dan sumber daya manusia yang ikut berpartisipasi dalam implementasi.

Simpelnya, untuk apa kita menerapkan SSL Pinning terlebih dahulu jika ternyata ada XSS yang ternyata ada. Jika memilih diantara dua isu tersebut gw akan lebih memilih perbaikan XSS dulu, baru SSL Pinning. Jadi sudah paham bukan? Kita harus bisa mengatur prioritas, dengan kondisi yang ada pilihlah task yang bisa didulukan dengan effort rendah, impact besar, budget rendah, dan resource yang seadanya.