# Understanding how it works.
![terminal](img.png)
Pada bagian terminal untuk print dapat kita lihat bahwa 'Ari's Komputer: hey hey' dicetak lebih awal dibandingkan dengan kalimat yang lain. Padahal, jika kita melihat kode, print 'Ari's Komputer: hey hey' berada lebih bawah. Hal ini bisa terjadi karena print 'Ari's Komputer: hey hey' tidak berada dalam _async_ sehingga langsung dijalankan dan tidak menunggu waktu terlebih dahulu.
