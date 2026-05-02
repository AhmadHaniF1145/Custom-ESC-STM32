# Custom Electronic Speed Controller (ESC)

Proyek desain dan implementasi Electronic Speed Controller (ESC) berbasis mikrokontroler STM32. Repositori ini mencakup *firmware*, desain skematik & PCB (Altium), serta file produksi Gerber.

## Diagram Blok Sistem
![Diagram Blok](images/Diagram%20Block%20ESC.png)

## Konfigurasi Mikrokontroler (STM32CubeIDE)
Pengaturan pinout dan peripheral pada mikrokontroler STM32.
![Konfigurasi STM32](images/stm32%20configuration.png)

## Desain PCB 3D (Altium)
Desain layout dan penempatan komponen (Top & Bottom View).
![3D PCB Top](images/top%20pcb%203d.png)
![3D PCB Bottom](images/bottom%203d%20pcb.png)

## Cetak PCB Fisik
Hasil cetak PCB sebelum komponen dipasang.
![Physical PCB Top](images/top%20pcb.jpg)
![Physical PCB Bottom](images/bottom%20pcb.jpg)

## Perakitan Fisik (PCBA)
Hasil akhir setelah penyolderan dan perakitan komponen pada PCB.
![Assembly Top](images/assembly%20pcb%20top.jpg)
![Assembly Bottom](images/assembly%20pcb%20bottom.jpg)

## Pengujian Sinyal Komutasi (Osiloskop)
Gelombang keluaran FASA ABC untuk menggerakkan motor Brushless DC.
![Sinyal Pengujian](images/FASA%20ABC%20100%25%20FGND%20500us.PNG)

## Integrasi Sistem
Pengujian ESC secara menyeluruh dengan motor dan *radio controller*.
![Total Sistem](images/total%20sistem.jpg)