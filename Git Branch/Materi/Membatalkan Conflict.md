Membatalkan Conflict

- Jika terjadi conflict, maka kita wajib memperbaikinya terlebih dahulu
- Semua perubahan yang tidak konflik akan secara otomatis berada di staging index
- Sedangkan perubahan yang konflik akan secara otomatis berada di Working Directory
- Jika kita ingin membatalkan merge, kita bisa gunakan perintah :
  git merge --abort
- Secara otomatis semua perubahan di branch yang ingin kita merge akan dihapus
