## NTFS – ext4 – APFS farkları?
NTFS, ext4 ve APFS farklı işletim sistemlerinde kullanılan dosya sistemleridir. Dosya sistemi; dosyaların nasıl saklanacağını, düzenleneceğini ve erişileceğini belirleyen yapıdır. Her işletim sistemi kendi ihtiyaçlarına göre farklı dosya sistemi kullanır.
## NTFS (New Technology File System)
Microsoft tarafından geliştirilmiştir ve genellikle Windows işletim sistemlerinde kullanılır. Güvenlik izinleri, şifreleme ve büyük dosya desteği gibi özelliklere sahiptir. Windows için en yaygın ve gelişmiş dosya sistemlerinden biridir.
Özellikleri:
-Windows’un varsayılan dosya sistemi
-Büyük dosya ve disk desteği
-Dosya izinleri ve güvenlik özellikleri
-Hata düzeltme desteği
Örnek:Bilgisayarda Windows kurulu bir SSD genellikle NTFS formatındadır.
## ext4 (Fourth Extended File System)
Linux işletim sistemlerinde yaygın olarak kullanılan dosya sistemidir. Hızlı, kararlı ve açık kaynaklıdır. Linux sunucularında ve dağıtımlarında sık tercih edilir.
Özellikleri:
-Linux’un yaygın dosya sistemi
-Yüksek performans ve kararlılık
-Açık kaynaklı yapı
-Büyük depolama desteği
Örnek:Ubuntu veya Kali Linux kurulurken disk genellikle ext4 olarak biçimlendirilir.
## APFS (Apple File System)
Apple tarafından geliştirilmiştir ve macOS ile iOS cihazlarında kullanılır. SSD diskler için optimize edilmiştir ve yüksek hız ile güvenlik sağlar.
Özellikleri:
-Apple cihazları için geliştirilmiştir
-SSD’ler için optimize edilmiştir
-Güçlü şifreleme sistemi
-Hızlı dosya kopyalama ve yönetim
Örnek:MacBook’larda kullanılan disk sistemi genellikle APFS formatındadır.
Temel farkları:
Dosya Sistemi  Kullanıldığı Sistem         Özelliği
NTFS	        Windows	            Güvenlik ve geniş uyumluluk
ext4	        Linux	            Hızlı ve kararlı yapı
APFS	     macOS / iOS	        SSD optimizasyonu ve şifreleme
## Blok yapısı (block structure)
verilerin veya bilgilerin belirli bölümlere ayrılarak düzenli şekilde saklanmasını sağlayan yapıdır. Bilgisayar sistemlerinde büyük veriler küçük bloklara bölünür ve bu bloklar ayrı ayrı işlenir, saklanır veya iletilir.
Özellikle depolama sistemlerinde ve ağ iletişiminde kullanılır. Her blok belirli boyutta veri içerir ve sistem bu blokları kullanarak veriye daha kolay erişir. Böylece veri yönetimi daha düzenli ve hızlı hale gelir.
Örneğin dosya sistemlerinde bir dosya diske tek parça halinde değil, bloklar halinde kaydedilir. Aynı şekilde blockchain sistemlerinde de bilgiler bloklar içinde tutulur ve birbirine bağlanır.
Blok yapısının avantajları:
Verilerin düzenli saklanmasını sağlar
Veri erişimini kolaylaştırır
Hata kontrolünü kolaylaştırır
Büyük verilerin yönetimini hızlandırır
## HDD (Hard Disk Drive) ve SSD (Solid State Drive) çalışma prensibi
bilgisayarlarda veri depolamak için kullanılan iki farklı depolama teknolojisidir. Aralarındaki en büyük fark çalışma prensipleridir.
## HDD (Hard Disk Drive)
HDD mekanik yapıyla çalışan bir depolama birimidir. İçerisinde dönen manyetik diskler bulunur. Veriler bu disklerin üzerine yazılır ve okunur. Okuma-yazma işlemini yapan hareketli bir kafa vardır. Disk döndükçe kafa gerekli veriyi bulur ve işlem gerçekleştirir.
Çalışma prensibi:
Disk sürekli döner
Okuma/yazma kafası hareket eder
Veriler manyetik olarak saklanır
Özellikleri:
Daha ucuzdur
Depolama kapasitesi yüksektir
Mekanik olduğu için daha yavaştır
Ses çıkarabilir ve darbeye karşı hassastır
## SSD (Solid State Drive)
SSD ise mekanik parça kullanmaz. Verileri flash bellek çipleri üzerinde elektronik olarak saklar. Bu nedenle verilere erişim çok daha hızlı gerçekleşir.
Çalışma prensibi:
Veri elektronik hücrelerde saklanır
Hareketli parça bulunmaz
Veriye doğrudan erişilir
Özellikleri:
Çok daha hızlıdır
Sessiz çalışır
Daha dayanıklıdır
Daha az enerji tüketir
HDD’ye göre daha pahalıdır
Temel farkları:
Özellik	             HDD	           SSD
Çalışma sistemi 	Manyetik disk	Flash bellek
Hareketli parça	      Var	           Yok
Hız	              Daha yavaş	      Daha hızlı
Dayanıklılık	   Daha düşük  	    Daha yüksek
Ses	               Çıkarabilir	      Sessiz
Fiyat	              Daha ucuz 	Daha pahalı