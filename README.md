# BIL372-Project

## Diyagram
![](https://raw.githubusercontent.com/asgrich/BIL372-Project/main/Diagram.png)

## Varsayımlar

 - Veliler birden fazla öğrencinin velisi olabilir
 - Öğrenciler birden fazla ders talep edebilir
 - Her ders bir öğretmen tarafından öğretilir, her öğretmen ders vermeyebilir
 - Her ders birden fazla depo malzemesi kullanabilir
 - Raporlar zaman aralıklarıyla verilir, bu nedenle aynı çalışan,malzeme ve benzeri kaynaklar birden fazla rapor çıkarabilir
 - Rapor ilişkilerinde raporun kaynağı, gideri, tarihi ve rapor id'si tutulur
 - İdari, öğretmen ve temizlik görevlisi dışında çalışan olabilir
 - Her çalışan ya tam zamanlı ya da yarı zamanlıdır

## İçerik

 - Öğrenci ders programı görüntüleme
 - Part time / Full time çalışma saatleri bilgileri
 - Öğrenci veli bilgileri
 - Toplu mail gönderme (opsiyonel, sadece içerdiğini konuştuk)
 - Filtreleyerek arama/görüntüleme arayüzü
 - Stokta az olan malzemeler için uyarma ve stok görüntüleme arayüzü
 - Haftalık ve aylık gider raporları

## Kullanılan ıvır zıvır buraya eklersiniz işte template yaptım neyse check this out ASCII UTKU ATASOY
████████████████████████████████████████████████████████████████████
████████████████████████████████████████████████████████████████████
████████████████████████████████████████████████████████████████████
████████████████████████████████████████████████████████████████████
░░░░░░░░░░░░░░░░░░░░░░░░░░░███████████████████▓░░░░░░░▒█████████████
░░░░░░░░░░░░░░░░░░░░░░░░▒█████████████████████████▒░░░░░░███████████
░░░░░░░░░░░░░▒░░░░░░░░▓██████████████████████████▓▓▓░░░░░░▒▒▓▓▓▓▓▓▓▓
░░░░░░░░░░░░░▒░░░░░░▓████████████████████████████▓▓▓▓░░░░░░▒▒▒▒▒▓▓▓▓
░░░░▒░░░░░░░░░░░░░▒▓█████████████████████████████████▒░░░░░░▒▒▒▒▓▒▒▒
░░░░▒░░░░░░▒░░░░░▒████████████████████████████████████▓▒░░░░░▒▒▒▒▒▒▒
▒░░░░░░░░░░░░░▒░▓███████████▓▓▓▓▒▒▒▒▒▒▓▓▓▓▓▓▓▓███████████░░░░▒▒▒▒▒▒▒
░░░░░░░░░░░░░░░▓████████▓▒▒▒▒▒▒▒░░░░░░░░▒▒▒▒▒▒▒▒▓▓██████▒▓▓░░░▒▒▒▒▒▒
░░░░░░░░░░░░░░▓███████▓▒▒░░░░░░░░░░░░░░░░░░░░▒▒▒▒▒▒█████████░░░▒▒▒▒▒
░░░░░░░░░░░░░▓███████▓▒░░░░░░░░░░░░░░░░░░░░░░░░░▒▒▒▒▓███████▓░░░░░░░
░░░░░░░░░░░░░▓███████▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒▒▓██████▓░░░░░░░
░░░░░░░░░░░░▒███████▓▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒▒██████▓░░░░░░░
░░░▒▒▒▒▒▒▒▒▓████████▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒▒▒▓██████░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▓████████▒▒▒▒▒▒▒░░░░░░░░░░░░░░░░░░░░░░░░░▒▒▒██████▒░░░░░░
▓▓▓▓▓▓▓▓▒▒▒▓███████▓▒▒▓▓▓▓████▓▒░░░░░░░░░░░░░░░▒▒▒▒▒▒▒▓█████▓▒░░░▒▒▒
░░░░░░░░░▒▒▒██████▓▒▒▒▒▒░░░░▒▓▒▓▒░░░░░░░░░▒▒▓████████▒█████▓░░░░░░░░
░░░░░░░░░▒▒▒▓█████▒░▒░░░░░░░░░░░░░░░░░░░░░▒▒▒▒▒▒▒▒▒▓▓▓█████░░░░░░░░░
░░░░░░░░░░░░▒████▓░░░░▒▒▒▒▒▒▒▒▒▒▒░░░░░░░░░▒▒░░░░░▒▒▒▒▒▓███░░░░░░░░░░
░░░░░░░░░░░░▒▓███▒░░░░▒▒▒▒███▒▒▒▒░░░░░░░▒▒▒▒▓▓▓▓▒▒▒▒▒▒▓██▓░░░░░░░░░░
░░░░░░░░░░░░░▓▒▒▓░░░░░░░░░░░░░░░░░░░░░░░▒▒▒▒▒▓█▓▒▓▓▒░░▒██▓░░░░░░░░░░
▒▒▒▒░░░░░░░░░▒▒▒▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒██▒░░░░░░░░░░
▒▒▒▒▒▒░░░░░░░░░▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒░░░░░░░░░░░░
▒▒▒▒▒▒▒░░░░░░░░▒▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▒▒░░░░░░░░░░░░░▒▒░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░▒░░░░░░░░░░░░░░░▒░░░░░░░░░░░░░░░░░░░░░▒░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░▒░░░░░░░░░░░░░░░░░░░░░▒▓▒░░░░░░░░░░░░▒▒░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░▒▒▒░░▒▒▒░░░░░░░░░░░░▒▒░░░░░░░░░░░░░░
▒░▒░░░░░░░░░░░░░▒▒▒░░░░░░░▒▒▒▒▓▓▓▓▓▒▓▓█▓▓░░░░░░░░░░▒▒░░░░░░░░░░░░░░░
▓▓▒░░░░░░░░░░░░░░▒░░░░░▒▒▓▓▓▒▒▒▒▒░░░▒▓▓██▓▓▓▒░░░░░▒▒▒░▒░░░░░░░░░░░░░
▓▓▒░░░░░░░░░░░░░░▒▒░░░▒▓▓▒▒▒░░░░░░░░░▒▒▒▒▒▓▓▓▓▒░░░▒▓▓▓▓▓▓▓▒▒▒▒▒▒▒░░░
▓▓▒▒░░░░░░░░░░░░░░▒▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▓▒▒▒▒▒▒▒▒▓▓▓▒▒▒██▓███████▓████▓▓▓
██▓▒░░░░░░░░░░░░▒▓▓▒▒▒▒▒▒░░░░░░░░░░░░░▒▒▒▒░░▒▓▓▓▓███████████████████
▒░░░░░░░░░░░▒▓▓███▓▒▒▒▒▒▒░░░░░░░░░░░░░░░░░░░▒███████████████████████
░░░░░░░▒▓▓██████▓█▓░▒▓▓▓▒▒░░░░░▒▒▓▓▓▓▒▒░░░░▒▓▓██████████████████████
░░▒▓▓▓▓▓▓▓▓███████▓░░▓▓▓▒▒▒▒░░░▓▓▒▒▓▓▒░░░░░▒▓██▓▒███████████████████
▓▓█▓██████████████▒░░▒██▓▓▓▓▓▓▒▓▒░░▒▒▒▒▒▒▒▒▓██▒▒████████████████████
█████████████████▓▒░░░▓██████▓▓▓▒░▒▒▒▓█▓▓████▒░▓████████████████████
███████████████▓▓█▒░░░░▒█████████▓▓▓███████▒░░▓█████████████████████
██████████████▓▒██░░░░░░░▒▓███████████████░░░▒██████████████████████
██████████████▒▓██▒░░░░░░░░░░▒▓▒▒▒▒▒▓▓▒░░░░░░███████████████████████
██████████████▒▓█▓▒░░░░░░░░░░░░░░░░░░░░░░░░░▓█████████████▓▓▓███████
███▓▓█████████░▓█▓▓▒░░░░░░░░░░░░░░░░░░░░░░░▒██████████████▓▓▓▓██████
▓▓▓▓██████████▒░▓█▓▓▒░░░░░░░░░░░░░░░░░░░░░░██████████████▓▓▓▓▓▒▒████
