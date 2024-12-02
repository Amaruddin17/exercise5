**Exercise 5: Demonstrate	access	contention	problems 
when	using	shared	resources	in	a	multitasking	system.**

**Tujuan**

1. Menunjukkan bahwa akses pada sumber daya yang sama tanpa adanya mekanisme perlindungan dapat menyebabkan gangguan antar tugas.
2. Memberi pemahaman bahwa interfensi terjadi karena tugas-tugas dapat secara bersamaan mengases sumber daya.
3. memberikan pemahaman tentang pentingnya penggunaan mekanisme pengelolaan sumber daya.

**Peralatan**
1. STM32F103C8T6
2. STM32 Cube IDE
3. FreeRTOS
4. Debugger

**Langkah-langkah**
1. membuat proyek baru di STM32CubeIDE
2. Aktifkan fitur FreeRTOS
3. tambahkan dua tugas yang akan melakukan penggunaan sumber daya bersama.
4. Pastikan kedua tugas mencoba untuk mengakses sumber daya bersama tanpa mekanisme pengelolaan.
5. Gunakan fungsi osDelay() untuk membuat jeda eksekusi.
6. Jalankan program dan perhatikan perilaku dari tugas melalui LED, UART output, atau alat debugging.

**Hasil implementasi**


https://github.com/user-attachments/assets/b95b80aa-f20e-476a-ad3c-244940d73c60

