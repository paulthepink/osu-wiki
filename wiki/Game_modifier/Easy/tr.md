---
stub: true
tags:
  - EZ
  - Easy
  - mod
  - game modifier
---

# Easy (mod)

![EZ mod icon](/wiki/shared/mods/EZ.png "Easy (EZ) mod icon")

*Tüm modların listesi için, bakınız: [Oyun Modu](/wiki/Game_modifier)*

## Hakkında

- Kısaltması: EZ
- Tipi: Zorluk Düşürme
- Skor Katlayıcısı: 0.50x
- Varsayılan Kısayol Tuşu: `Q`
- Başlık:
  - ![][o!s]: `Genel zorluğu düşürür - daha büyük daireler, daha affedici can azaltma, daha az doğruluk gerekli.`
  - ![][o!t]: `Genel zorluğu düşürür - daha büyük daireler, daha affedici can azaltma.`
  - ![][o!c]: `Genel zorluğu düşürür - daha büyük daireler, daha affedici can azaltma, daha az doğruluk gerekli.`
  - ![][o!m]: `Genel zorluğu düşürür - daha affedici can azaltma, daha az doğruluk gerekli.`
- Uyumlu oyun modları: ![][o!s] ![][o!t] ![][o!c] ![][o!m]

## Açıklama

 **Easy** [beatmap](/wiki/Beatmaps)lerin zorluğunu düşürmeyi deneyen bir [oyun modu](/wiki/Game_modifier)dur. Bunu seçilmiş beatmapin bütün zorluk ayarlarını yarıma düşürerek yapar.

[osu!taiko](/wiki/Game_mode/osu!taiko) hariç bütün [oyun modları](/wiki/Game_mode) için geçerlidir, [can barı](/wiki/Glossary#life-bar) sıfıra düşer ise Easy modu ekstradan iki "can" sağlar. Eğer bu gerçekleşirse, can barını %80 civarına geri doldurmak için oyun kendini duraklatacaktır. Bu gerçekleşirken hiçbir ses oynamayacaktır.

Bu geri doldurma olayı oyuncuya hazır sesi ile sinyal verecektir (`readysound.wav`). Can barının geri doldurma işlemi bittikten sonra, oyuncu tekrar sinyallendirilecektir, ancak bu sefer ilerle sesi ile (`gosound.wav`). Sonrasında ise beatmap oynamaya devam edecek ve oyuncuya devam etmesi için izin verecektir. Eğer oyuncunun ekstra canı kalmadıysa ve can barı sıfıre tekrar düştü ise, oyun normal bir şekilde başarısızlık ile sonuçlanacaktır.

### osu!standard

[osu!standard](wiki/Game_Modes/osu!) da, Easy modu [daire boyutu (CS)](/wiki/Beatmap_Editor/Song_Setup#circle-size), [yaklaşma oranı (AR)](/wiki/Beatmapping/Approach_rate), [genel zorluk (OD)](/wiki/Beatmap_Editor/Song_Setup#overall-difficulty), ve [can azaltmayı (HP)](/wiki/Beatmap_Editor/Song_Setup#hp-drain-rate) yarıya düşürür.

![EZ Gameplay o!s](img/GM_EZ2.jpg "osu!standard gameplay with the Easy mod enabled")

Yine de söylemek gerekir ki, çoğu oyuncu Easy modunun şu anki beatmaplerde zorluğu düşürme kullanımını yardımcı olarak görmez, özellikle yüksek vurgulu olanlarda. Bu argüman; düşürülmüş yaklaşma oranının karışık, okuması zor bir durum oluşturduğuna ve beatmapin hızını düzgün görsel şekilde yansıtamadığına değinir. (yukarıda görüntülenmiştir).

*Not: Yukarıdaki noktalar, "[Let's talk Easy Mod](https://osu.ppy.sh/community/forums/topics/56606)" üzerinde moda özellik isteğinde değinilmiştir.

### osu!taiko

[osu!taiko](/wiki/Game_mode/osu!taiko) da, Easy modu [kaydırıcı hızını](/wiki/Glossary#slider-velocity) düşürür, genel zorluk (OD) ve can düşürmeyi yarıya indirir.

*Not: [döndürücüyü](/wiki/Hit_object/Spinner) bitirmek için gereken vuruş sayısı, OD değerine düşürülür.*

Diğer oyun modlarına nazaran, Easy modunun osu!taikoda kullanımı can kazanmak için olan skor gereksinimini düşürür. Bu ekstra iki "can" yerine can barının daha hızlı dolmasının sağlar, bu sayede taiko oynarken şarkının ortasında başarısız olmak imkansızdır.

### osu!catch

[osu!catch](/wiki/Game_mode/osu!catch)de özellikler osu!standard ile birkaç düzenleme ile neredeyse aynıdır: tüm meyveler daha yavaş düşer (düşürülmüş AR), ekran "yakınlaştırılır" (düşürülmüş CS), ekstradan iki "can" verilir.

Sadece tek bir eksen kullanmasına rağmen, büyük meyveler ve yavaşlatılmış düşme hızı meyvelerin bir araya girip yığınlanmasına neden olarak, zorluk düşürmede osu!standard benzeri bir sıkıntı çıkarabilir.

<!-- image needed here -->

### osu!mania

[osu!mania](/wiki/Game_mode/osu!mania)da iki "can"ın oyuncuya verilmesi, kaydırıcı hızı ve varsayılan tuş sayısının aynı kalması haricinde, özellikler taiko ile aynıdır.

## Trivia

- Ekstra canın kullanıldığı bir tekrarı izlerken, can doldurma animasyonu yerine tekrar [No Fail](/wiki/Game_modifier/No_fail) modu ile oynanıyormuş gibi devam edecektir.
- [Multi](/wiki/Multi) modunda, [Tag Co-op or Tag Team Vs.](/wiki/Multi#tag-coop-tag-team-vs)de ki "can" özellikleri çalışmayacaktır.
- Easy modu [Hard Rock](/wiki/Game_modifier/Hard_Rock) modunu iptal edecektir, vs.

[o!s]: /wiki/shared/mode/osu.png "osu!standard"
[o!t]: /wiki/shared/mode/taiko.png "osu!taiko"
[o!c]: /wiki/shared/mode/catch.png "osu!catch"
[o!m]: /wiki/shared/mode/mania.png "osu!mania"
