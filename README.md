# clientserver-upload-remove
## Tugas 4 Pemrograman Jaringan Kelas C
| Nama  | NRP |
| ------------- | ------------- |
| Duevano Fairuz Pandya  | 5025211052  |

Instruksi Tugas <a href="https://docs.google.com/document/d/12rvdFHDNKw_BOJRtMvHwTQ_2-Tv1Dx4uk0Jk65SNgtk/edit">Disini</a>

### Cara menjalankan program:
1. Jalankan `file_server.py`
2. Jalankan `file_client_cli.py` di terminal lain atau di mesin (node) lain
3. Gunakan command `remote_[command]([parameter])` pada client untuk mengakses fitur yang tersedia di <a href="https://github.com/duevanofairuz/clientserver-upload-remove/blob/main/PROTOKOL.txt">Protokol</a><br>
Contoh:
```py
remote_list()
remote_get('pokijan.jpg')
remote_remove('pokijan.jpg')
remote_uplaod('pokijan.jpg')
```
