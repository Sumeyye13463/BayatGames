Oyun fikriniz tamamen orijinal midir?
•	Hayır, orijinal değildir.
•	Piyasadaki birçok 2D platform oyunu gibi temel mekaniklere sahiptir. Orijinal olan kısmı her level’in kendine ait bir score tablosu olması ve her bir levelden sonra score’un sıfırlanmasıdır.
•	Oyunun amacı, bir karakterin hem engellerden kaçması ve score’unu yükseltmektir. Temel oyun mekaniği bu türdeki oyunlara benzer olsa da, görsel stil, can sistemi, skor yapıları ayırıcı bir özelliktedir.
Oyunuzu özel kılan oyun mekanikleri nelerdir?
•	Oyunda can puanı sistemi vardır; oyuncunun canı sıfırlandığında ekran kararır ve birkaç saniye sonra ana menüye dönülür.
•	Oyuncunun hareketleri (sağ-sol, zıplama) fiziksel tepkilerle ve sade bir kontrol şemasıyla optimize edilmiştir.
•	Level geçiş sistemi özeldir: Skorun belli bir seviyeye ulaşması ve karakterin sahnenin sonuna ilerlemesiyle bir sonraki level’e geçilir.
•	Oyun sırasında can kaybı, skor takibi, ve karakterin sahnenin dışına taşması gibi durumlar kontrol edilerek farklı sahnelere geçiş sağlanır.

Oyununuzda tamamladığınız hedefler nelerdir?
•	Ana karakterin sağa/sola hareketi ve zıplama gibi temel kontroller tamamlandı.
•	Skor sistemi çalışmakta ve sahne değişikliklerinde skoru taşıyacak yapılar tanımlandı.
•	Can sistemi ve “Kaybettin!” ekranı tamamlandı.
•	Level geçişi başarıyla sağlandı ve farklı sahneler arası geçiş kodlamaları yazıldı.
•	Ana menü, oyun içi UI ve sahne arka planları tamamlandı.
Oyununuzda eksik kalan hedefler nelerdir?
•	Arka planda oynayan müzik ve ses efektleri henüz tam entegre edilmedi.
•	Zorluk seviyeleri veya boss mekanikleri gibi daha ileri düzey öğeler henüz eklenmedi.
•	Mobil platforma veya farklı çözünürlüklere uyumlu tasarım henüz yapılmadı.

Oyunu tamamlama aşamanızı grup üyelerinin görevleri ile birlikte detaylandırması.
•	Bu proje bireysel olarak geliştirildi. Aşağıdaki süreçler tek kişi tarafından yürütülmüştür:
• Araştırma sürecinde neler yapıldı?
•	2D platform oyunlarının yapısı, Unity Engine kullanım kılavuzları ve C# script örnekleri incelendi.
•	“Can sistemi”, “sahne geçişleri”, “skor tutma” gibi konulara odaklanıldı.
•	YouTube ve Unity Learn gibi kaynaklardan benzer oyunlar analiz edilerek notlar alındı.
• Tasarım süreci ve kodlama sürecinde neler yapıldı?
•	Tilemap kullanılarak zemin ve engeller oluşturuldu.
•	Ana karakter sprite'ı, Rigidbody2D ve Collider komponentleriyle hazırlandı.
•	Animator Controller üzerinden yürüme ve zıplama animasyonları tanımlandı.
•	C# ile yazılan script dosyalarıyla oyuncu kontrolleri, skor, can ve sahne geçişleri gibi dinamikler oluşturuldu.
•	Kaybettin ekranı ve yeniden başlatma işlemleri programlandı.
