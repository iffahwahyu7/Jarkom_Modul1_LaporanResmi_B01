# Jarkom_Modul1_LaporanResmi_B01


#### B. Capture Filter

11. Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!
    `tcp.port == 21 || udp.port == 21`
    ![alt text](images/11.1.jpg)
    `port 21`
12. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!
`src port 80`
13. Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!
`dst port 443`
14. Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

15. Filter sehingga wireshark hanya mengambil paket yang tujuannya ke monta.if.its.ac.id!
`dst host monta.if.its.ac.id`
