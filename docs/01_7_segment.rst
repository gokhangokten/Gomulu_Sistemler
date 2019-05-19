********************************************************************************
7 Segment LED
********************************************************************************

   İlk örnek olarak 7 segment LCD display ile başlayacağız. 

1. 7 Segment Bağlantı 
================================================================================

   Aşağıdaki şemada ATmega328p mikrodenetleyicisine bağlanmış iki adet 7 segment LED display ve iki buton bulunmaktadır. Şema simulasyon için yeterli elemanlara sahiptir. 
   
   İlk şemada yeni başlayanlara kolaylık olması için 7 segment LED display olarak `4056 <https://www.st.com/resource/en/datasheet/cd00002658.pdf>`_ entegre edilmiş direk BCD sürülebilen ekranlar seçtim. 

   `Buradan <_static/packs/7segment.7z>`_ bu örneğe ait Proteus projesini indirebilirsiniz.

   .. figure:: ../schematics/7_segment_01.PNG
      :align: center
      :alt: 7-Seeegment Şema
      :figclass: align-center
      
      7-Segment Şema


2.1. Kullanılacak Yazılımlar ve Donanımlar
================================================================================

   .. note:: 
      Özellikle gömülü sistemler alanında eğitim veren mühendislik bölümlerinde **sadece** Arduino öğretilmesine karşıyım. Buradaki örneklerin aynı zamanda gerçek donanım üzerinde de test edilebilmesi için en ucuz ve kolay bulunan protorip bordu olan Arduino örneklerine de yer vereceğiz.
      
   * Şemalar simulasyon odaklı verilecektir. Simulasyon için Proteus yazılımı kullanılacaktır. Proteus versiyon 8.7 SP3'dür. Proteus nereden bulunur vb. soruları lütfen sormayınız.
   * Arduino Atmega328p çipine sahip UNO veya NANO 
   * `Arduino geliştirme ortamı <https://www.arduino.cc/en/Main/Software>`_ 
 