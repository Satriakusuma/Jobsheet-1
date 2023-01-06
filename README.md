# Jobsheet-1
# JOB-1
DASAR PEMROGRAMAN ESP32 UNTUK PEMROSESAN DATA INPUT/OUTPUT ANALOG DAN DIGITAL


Alat dan Bahan :
1) Kabel Jumper
2) Breadboard
3) ESP32
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)


A. GPIO
1. Pada program ini diharapkan bisa menyalakan satu LED dengan menekan push button dan jika push button dilepaskan akan mati

https://user-images.githubusercontent.com/121172074/209278488-fd56521a-e1fe-4978-b0f2-8e86041bdf72.mp4

2. Lalu selanjutnya pada program GPIO yang kedua ditambahkan 1 LED dengan estimasi waktu 5 detik yang mana LED akan menyala selama 5 setik dan sebaliknya yaitu lampu akan mati selama 5 detik, jadi apabila tetap ditekan push buttonnya namun waktu sudah habis LED akan tetap mati

https://user-images.githubusercontent.com/121172074/209063304-6791ca81-854a-452d-a14d-6ad36a9a8094.mp4

3. Selanjutnya percobaan GPIO yang ketiga menggunakan 3 LED yang dikendalikan dengan satu push button, lalu program ini dijalankan dengan push button ditekan maka lampu akan menyala dengan berurutan

https://user-images.githubusercontent.com/121172074/209064986-9cb8c0b3-2421-48bf-b092-3b5cb46f4042.mp4


B. PWM
1. Percobaan selanjutnya yaitu metode Pulse Width Modulation yaitu pendekatan pelebaran pulsa dengan menghasilkan nilai tegangan analog dengan maksimal tegangan HIGH 3,3 V dan LOW 0 V. Pin pada PWM ini mengeluarkan sinyal digital yang dihasilkan dari dutty cycle (perbandingan HIGH dan LOW dalam 1 periode) pada percobaan PWM 1 dengan 1 LED. Pada program PMW ini LED akan menyala 5x lebih terang, karena terdapat delay 0,015 maka LED akan redup dengan kecepatan 0,015 sekon, kemudian akan terang kembali.

https://user-images.githubusercontent.com/121172074/209066498-01275e63-3359-40e3-821c-4cff233d1df6.mp4

2. Percobaan selanjutnya pada PWM ini hampir sama dengan PWM yang pertama diatas hanya saja menggunakan 3 LED

https://user-images.githubusercontent.com/121172074/209067060-24155b49-0197-4393-a30e-c5ecc0b2ef29.mp4


C. ADC dan DAC
1. Pada terakhi untuk Program ADC dan DAC ini menghasilkan output, jika potensiometer diputar semakin ke kanan maka nilainya akan semakin bertambah dan apabila diputar ke kiri semakin berkurang. 

https://user-images.githubusercontent.com/121172074/209260152-9453205d-2e8a-49fe-8c5d-2fe2d85ba86e.mp4

2. Lalu percobaan kedua ini LED ditambahkan dan juga ditambahkan GPIO pada program ini, jika dijalankan akan menghasilkan output apabila pentisiometer diputar ke kanan maka lampu akan semakin menyala dan begitupun sebaliknya

https://user-images.githubusercontent.com/121172074/209268953-ebf8bc94-e46b-4a13-8a37-f848641e2988.mp4




 

