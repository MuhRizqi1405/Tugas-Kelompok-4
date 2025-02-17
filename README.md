# Tugas-Kelompok-4
## Pengertian Uninterruptible Power Supply (UPS)
UPS adalah perangkat yang dirancang untuk mengatasi gangguan kelistrikan dan menyediakan daya listrik sementara ketika sumber utama (PLN) padam.

UPS umumnya menggunakan baterai sebagai sumber daya cadangan untuk memastikan perangkat elektronik tetap beroperasi saat listrik padam. Sistem ini sangat penting bagi perusahaan di berbagai sektor, seperti telekomunikasi, informasi, dan warnet. Tanpa UPS, kerugian akibat gangguan listrik dapat sangat besar.

## fungsi UPS
Dapat memberikan energi listrik sementara ketika terjadi kegagalan daya pada listrik utama (PLN).
 Memberikan kesempatan waktu yang cukup kepada kita untuk segera menghidupkan Genset sebagai pengganti PLN.
 Memberikan kesempatan waktu yang cukup kepada kita untuk segera melakukan back up data dan mengamankan Operating System (OS) dengan melakukan shutdown sesai prosedur ketika listrik utama (PLN) padam
   • Mengamankan sistem dari gangguan-gangguan listrik yang dapatmengganggu sistem baik berupa kerusakan software,data maupun kerusakan hardware       
 UPS secara otomatis dapat melakukan stabilisasi tegangan ketika terjadi perubahan tegangan pada input sehingga tegangan output yang digunakan oleh sistem berupa tegangan yang stabil.
 UPS dapat melakukan diagnosa dan management terhadap dirinya sendiri sehingga memudahkan pengguna untuk mengantisipasi jika akan terjadi gngguan terhadap sistem.

 ## Jenis ups / cara kerja ups
 ## UPS OFFLINE
![UPS-line-interactive-cu-LCD-700VA_5688_3](https://github.com/user-attachments/assets/15957554-7347-4d8f-a574-6a23108ea1eb)

 Saat UPS menerima daya dari sumber listrik utama, output UPS akan mengalirkan listrik ke perangkat yang terhubung. Jika tegangan listrik utama berada di luar rentang yang ditentukan, UPS akan otomatis beralih ke mode baterai. Dalam mode ini, inverter akan mengubah daya DC dari baterai menjadi listrik AC 220V untuk mensuplai perangkat. Proses peralihan dari sumber listrik utama ke baterai ini terjadi sangat cepat, dalam waktu kurang dari 2 hingga 4 milidetik (transfer time).

 ## UPS ONLINE
 ![th](https://github.com/user-attachments/assets/84df6132-5680-41f8-a761-70c33bc20c3d)
 Prinsip kerjanya: UPS akan bekerja selalu dari inverter baik UPS bekerja dari sumber listrik utama maupun sumber listrik utama mati (UPS bekerja dari baterai). Jadi, dikarenakan UPS selalu bekerja dari inverter maka tidak ada transfer time (waktu pindah) pada saat perpindahan dari baterai ke sumber listrik utama begitu pula sebaliknya dan tegangan serta frekuensi output UPS juga akan sangat stabil. Pada sistem online ini pada umumnya terdapat converter AC ke DC sebagai pengganti baterai pada saat UPS bekerja dari sumber listrik utama. Jadi perpindahan itu terjadi dari converter ke baterai atau sebaliknya. Inverternya tetap bekerja untuk mensuplai tegangan AC 220V pada output UPS. Sehingga tidak ada transfer time pada saat perpindahan dari sumber listrik utama ke baterai atau sebaliknya.

 ## KOMPONEN-KOMPONEN UTAMA PADA UPS
• Baterai
![image](https://github.com/user-attachments/assets/d970dd9e-e92c-4edb-9e13-fd3738159488)

Jenis baterai yang digunakan UPS umumnya berjenis lead-acid atau jenis nikel-cadmium.
Baterai ini umumnya mampu menjadi sumber tegangan cadangan maksimal selama 30 menit.
• Rectifier
![image](https://github.com/user-attachments/assets/cbb545f3-f00f-49e2-adbe-a3293ac1b028)

Penyearah atau Rectifier berfungsi untuk mengubah arus AC menjadi arus DC (direct current) atau DC dari suplai listrik utama. Hal ini bermanfaat pada saat pengisian baterai.
• Inverter
![image](https://github.com/user-attachments/assets/668db933-bb25-4e01-a4fe-5ce553e7096b)

Kebalikan dari penyearah, inverter berfungsi untuk mengubah arus DC dari baterai menjadi arus AC. Hal ini dilakukan pada saat baterai pada UPS digunakan
untuk memberikan tegangan ke komputer.
• Transfer Switch
![image](https://github.com/user-attachments/assets/c547f3d2-163b-4e66-be78-896869495487)

Transfer Switch adalah saklar listrik yang menghubungkan sumber tenaga listrik dari sumber utama ke sebuah sumber cadangan
(UPS). Saklar ini dapat dioperasikan secara manual atau secara otomatis. Automatic Transfer Switch - ATS sering dipasang di mana sebuah sumber daya cadangan terletak, sehingga dapat memberikan daya listrik sementara jika sumber listrik terputus.

## Maintenance UPS & battery
- Dilakukan untuk menjaga kinerja perangkat pendukung system SCADA agar bekerja secara normal dan backup time yang tepat.
 Pengecekan Secara Visual UPS
 Pengukuran Tegangan Input & output Batteray
 Pengecekan Fan pada unit UPS
 Pengecekan Temperatur kondisi Ruangan

## Kesimpulan
UPS adalah perangkat penting untuk melindungi peralatan elektronik dari gangguan listrik, menyediakan daya cadangan, dan menjaga kestabilan tegangan. Dengan memilih jenis yang sesuai, UPS membantu mencegah kerusakan perangkat, kehilangan data, dan memastikan kelangsungan operasional.
