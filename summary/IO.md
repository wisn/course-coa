# Input/Output

1. **Berikut ini merupakan alasan dari adanya modul input output, kecuali:**

- Ukuran data yang ditransfer dalam satu saat berbeda
- Kecepatan transfer berbeda untuk tiap modul
- Format data berbeda

2. **Device eksternal yang terhubung ke modul I/O disebut:**

- Peripheral

3. **Yang merupakan jenis-jenis device eksternal adalah:**

- Human readable
- Machine readable
- Communication

4. **Screen, printer, keyboard, merupakan jenis device:**

Human readable

5. **Sensor, aktuator, merupakan jenis device:**

Machine readable

6. **Untuk mengirimkan status dari device (ready atau error),
I/O menggunakan sinyal:**

Status

7. **Untuk menampung data dari/ke modul I/O sementara waktu digunakan:**

Buffer

8. **Untuk menentukan aktifitas dan status device eksternal digunakan:**

Control logic

9. **Untuk mengubah bentuk data dari signal elektrik, mekanik, temperatur,
tekanan, dll menjadi data digital dan sebaliknya digunakan:**

Transducer

10. **Untuk menentukan apa yang harus dilakukan oleh device,
I/O menggunakan sinyal:**

Kontrol

11. **Berikut ini merupakan fungsi dari modul I/O:**

- Control
- Timing
- CPU Communication
- Data Buffering
- Error Detection

12. **Modul I/O berfungsi sebagai pengatur aliran data antara resource internal
(CPU, memori) dengan device eksternal. Merupakan fungsi I/O sebagai:**

Control & Timing

13. **Modul I/O berfungsi sebagai media komunikasi dari CPU menuju
device eksternal. Merupakan fungsi I/O sebagai:**

CPU Communication

14. **Modul I/O berfungsi sebagai media komunikasi dari device eksternal menuju
CPU. Merupakan fungsi I/O sebagai:**

Device Communication

15. **Modul I/O berfungsi sebagai penampung data sementara baik dari CPU/memori
maupun dari peripheral. Merupakan fungsi I/O sebagai:**

Data Buffering

16. **Modul I/O berfungsi sebagai pendeteksi kesalahan yang ditimbulkan oleh
device. Merupakan fungsi I/O sebagai:**

Error Detection

17. **Jika status ready, CPU minta agar device mengirimkan data.
Merupakan langkah nomor berapa dari prosedur transfer data dari device
ke CPU via I/O? (Jawab dengan angka)**

3

18. **Men-decode alamat yang dikirimkan oleh CPU istilahnya disebut:**

Address recognition

19. **Men-decode perintah/command dari CPU merupakan hal yang dilakukan modul
I/O tatkala berfungsi sebagai:**

CPU Communication

20. **Meneruskan perintah/command dari CPU ke device merupakan hal yang
dilakukan modul I/O tatkala berfungsi sebagai:**

Device Communication

21. **Bit parity biasanya digunakan untuk:**

- Error detection
- Metode deteksi
- Metode deteksi error
- Metode deteksi kesalahan

22. **Mekanisme untuk menghentikan sementara waktu urutan eksekusi program
yang normal tatkala ada program lain yang lebih mendesak
untuk dieksekusi disebut:**

Interrupt

23. **Yang menjadi penyebab terjadinya interrupt diantaranya adalah:**

- Program
- Timer
- I/O
- Hardware failure

24. **Interrupt yang disebabkan adanya overflow merupakan jenis interrupt
yang disebabkan:**

Program

25. **Interrupt yang disebabkan adanya division by zero merupakan jenis
interrupt yang disebabkan:**

Program

26. **Pre-emptive multi-tasking biasanya menggunakan interrupt
yang disebabkan oleh:**

Timer

27. **Interrupt yang dihasilkan oleh I/O akibat adanya kesalahan merupakan
jenis interrupt yang disebabkan oleh:**

I/O

28. **Interrupt yang disebabkan adanya memory parity error merupakan
jenis interrupt yang disebabkan:**

Hardware failure

![Soal 28](IO-28.jpg)

29. **Tanda \"X\" pada siklus yang digambarkan oleh state diagram merupakan:**

Interrupt check

30. **Pada saat terjadi interrupt, maka alamat pada PC diganti menjadi:**

Alamat awal routine interrupt handler

31. **Kapan dapat terjadi kondisi: CPU mengalami waktu tunggu**

Long I/O Wait

32. **Mana yang lebih menguntungkan untuk implementasi interrupt?**

Short I/O Wait

33. **Multiple interrupt diatasi dengan cara:**

> Isi bagian ini.

34. **Eksekusi I/O terus menerus melibatkan prosesor, merupakan teknik I/O
untuk:**

Programmed I/O

35. **Eksekusi I/O tidak secara terus menerus melibatkan prosesor,
merupakan teknik I/O untuk:**

Interrupt driven I/O

36. **Transfer data ditangani oleh sebuah prosesor I/O khusus, merupakan teknik
I/O untuk:**

Direct Memory Access (DMA)

37. **Pada programmed I/O, apa yang dilakukan CPU tatkala operasi I/O
belum selesai?**

CPU tidak melakukan apa-apa

38. **Memori dan I/O menggunakan ruang alamat yang sama secara bersama-sama
merupakan jenis pengalamatan I/O:**

Memory mapped I/O

39. **Teknik Identifikasi Interrupt menggunakan software poll mengakibatkan
kelemahan berupa:**

Lambat, karena harus memeriksa modul I/O satu persatu

40. **Vector digunakan sebagai pointer untuk menunjuk langsung ke device sumber
interrupt sebelum menjalankan interrupt handler pada hardware poll disebut:**

Vectored interrupt
