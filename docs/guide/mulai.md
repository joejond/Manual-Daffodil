# Koneksi Ethernet

> Gunakan PC atau laptop dengan Operating System Windows atau Linux. Pengujian ini menggunakan kabel Ethernet.


  - Sambungkan kabel ethernet (straight mode) dari konektor ethernet di modul ke konetor ethernet di PC
  - IP default dari Module adalah <span style="color:blue; font-weight:bold">192.168.0.10</span>
  - untuk uji coba koneksi modul dan komputer
    ```bash
    ping 192.168.0.10
    ```  
    _hasilnya :_
    ```
    Pinging 192.168.0.10 with 32 bytes of data:
    Reply from 192.168.0.10: bytes=32 time=3ms TTL=254
    Reply from 192.168.0.10: bytes=32 time=4ms TTL=254
    Reply from 192.168.0.10: bytes=32 time=9ms TTL=254
    Reply from 192.168.0.10: bytes=32 time=70ms TTL=254
    ```

  - apabila ping berhasil, maka selanjutnya kita dapat terhubung ke Modul 

_**Jika PING response berhaisl, maka modul daffodil siap untuk di gunakan tahap berikutnya.**_ 

