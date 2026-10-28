# Nabız Özet — web demosu

Canlı demo: https://kutlu53.github.io/nabiz-ozet-demo/

Poliklinik hekimi için tek ekranlık hasta özeti ve kural tabanlı karar destek prototipinin sunucusuz demosu.
Bu depo yalnızca derlenmiş web uygulamasını ve önceden hesaplanmış demo verisini içerir; kaynak kod burada değildir.

- **Veri:** 25 hasta, tamamı [Synthea](https://github.com/synthetichealth/synthea) ile üretilmiş sentetik kayıtlardır. Gerçek hasta verisi yoktur; isimler rastgele Türkçe isimlerle değiştirilmiştir.
- **Bulgular:** 15 YAML kuralından (12 tip 2 diyabet, 3 hipertansiyon) doğar ve her biri kayıttaki tahlil, tanı veya reçete satırına bağlıdır. Yapay zekâ karar vermez.
- **Demo sınırları:** Geri bildirim butonları çalışır ama yalnızca açık sekmede tutulur. Yapay zekâ anlatısı bu sürümde kapalıdır.

Tanı koymaz, tedavi önermez; klinik kullanım için değildir.
