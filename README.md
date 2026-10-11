# Sansür Aşma Araçları Rehberi

**[English version below](#censorship-circumvention-tools-guide)**

Erişim engelleriyle karşılaşan kişiler için hazırlanmış, açık kaynaklı ve tek dosyalık bir bilgi sitesi. Engellerin nerede durduğunu, hangi aracın hangi engeli aştığını ve bu araçları kullanırken nelere dikkat edilmesi gerektiğini anlatır.

Site Türkçe ve İngilizce yayınlanır. Üstteki **TR | EN** düğmesiyle dil değiştirilir.

## Neler var?

- **Bağlantı şeması:** Doğrudan bağlantı, şifreli DNS, VPN ve Tor'un bir engelin etrafından nasıl dolandığını gösteren etkileşimli çizim
- **Engel türleri:** DNS engeli, IP engeli, trafik incelemesi (DPI) ve yavaşlatma
- **Araçlar:** Tor Browser, Snowflake, VPN, Psiphon, Lantern, Outline, Shadowsocks ve şifreli DNS
- **Denetlenmiş VPN sağlayıcıları:** Kayıt tutmama iddiası bağımsız bir firma tarafından denetlenmiş sağlayıcılar
- **Tor köprüleri:** obfs4, WebTunnel, Snowflake ve meek-azure, ve köprünün nasıl seçileceği
- **Güvenlik notları:** Araçları kullanırken yapılması ve yapılmaması gerekenler

## Nasıl çalıştırılır?

Sitenin sunucuya, derleme adımına ya da bağımlılığa ihtiyacı yoktur. Tek bir HTML dosyasıdır.

```bash
git clone https://github.com/yahya3886/sansur-asma-toollari.git
cd sansur-asma-toollari
```

Ardından `index.html` dosyasını tarayıcıda açın. Yazı tipleri Google Fonts'tan yüklenir. Çevrimdışıyken sistem yazı tipleri kullanılır, sayfa yine de çalışır.

### GitHub Pages ile yayınlamak

1. Ana HTML dosyasının adını `index.html` yapın.
2. Depoda **Settings → Pages** bölümüne gidin.
3. Kaynak olarak ana dalı ve kök klasörü seçin.

## Katkı vermek

Her türlü katkı değerlidir: yanlış ya da eski bir bilgiyi düzeltmek, eksik bir aracı eklemek, çeviriyi iyileştirmek ya da yeni bir dil eklemek.

- Hata ve öneriler için bir [issue](https://github.com/yahya3886/sansur-asma-toollari/issues) açın.
- Değişiklik göndermek için depoyu çatallayın (fork), değişikliği yapın ve bir [pull request](https://github.com/yahya3886/sansur-asma-toollari/pulls) açın.

### Bilgi eklerken

Bu sayfa insanların güvenliğiyle ilgilidir, bu yüzden bilgilerin doğru olması önemlidir.

- Bir araç ya da sağlayıcı hakkında iddia ekliyorsanız, projenin kendi sitesinden ya da bağımsız bir kaynaktan doğrulayın.
- Denetim, tarih ve sürüm bilgilerinin kaynağını pull request açıklamasına yazın.
- Bir aracı abartmayın. Her aracın neyi aşamadığını da yazın.

### Çeviri nasıl çalışır?

Türkçe metin doğrudan HTML içindedir. İngilizce karşılıklar, sayfanın en altındaki betikte bulunan `EN` sözlüğündedir. Sözlüğün anahtarı Türkçe metnin kendisidir.

Bu yüzden bir Türkçe cümleyi değiştirirseniz, sözlükteki anahtarı da aynı şekilde değiştirmeniz gerekir. Aksi halde o cümle İngilizce modda Türkçe kalır. Açıklama panelindeki metinler ise betiğin içindeki `PANEL` nesnesindedir.

## Sorumluluk reddi

Bu site genel bilgi içindir. Hukuki ya da güvenlik tavsiyesi değildir. Bu araçların kullanımı bazı ülkelerde kısıtlıdır. Kendi ülkenizdeki kuralları ve riskinizi önceden öğrenin. Araçların özellikleri ve engelleme yöntemleri zamanla değişir, karar vermeden önce her projenin güncel belgelerini okuyun.

## Kaynaklar

- [Tor Project](https://www.torproject.org)
- [Snowflake](https://snowflake.torproject.org)
- [Psiphon](https://psiphon.ca)
- [Lantern](https://getlantern.org)
- [Outline](https://getoutline.org)
- [Quad9](https://www.quad9.net)

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile yayınlanmıştır.

---

# Censorship Circumvention Tools Guide

An open-source, single-file information site for people who run into internet blocks. It explains where a block can sit, which tool gets past which kind of block, and what to watch out for when using these tools.

The site is published in Turkish and English. Use the **TR | EN** button at the top to switch languages.

## What's inside

- **Connection diagram:** An interactive drawing showing how a direct connection, encrypted DNS, a VPN and Tor each get around a block
- **Types of blocks:** DNS blocks, IP blocks, traffic inspection (DPI) and throttling
- **Tools:** Tor Browser, Snowflake, VPNs, Psiphon, Lantern, Outline, Shadowsocks and encrypted DNS
- **Audited VPN providers:** Providers whose no-logs claims have been audited by an independent firm
- **Tor bridges:** obfs4, WebTunnel, Snowflake and meek-azure, and how to choose a bridge
- **Safety notes:** Do's and don'ts when using these tools

## Running it

The site needs no server, build step or dependencies. It is a single HTML file.

```bash
git clone https://github.com/yahya3886/sansur-asma-toollari.git
cd sansur-asma-toollari
```

Then open `index.html` in a browser. Fonts load from Google Fonts. Offline, system fonts are used and the page still works.

### Publishing with GitHub Pages

1. Rename the main HTML file to `index.html`.
2. In the repository, go to **Settings → Pages**.
3. Choose the main branch and the root folder as the source.

## Contributing

All kinds of contributions are welcome: fixing wrong or outdated information, adding a missing tool, improving the translation or adding a new language.

- Open an [issue](https://github.com/yahya3886/sansur-asma-toollari/issues) for bugs and suggestions.
- To send a change, fork the repository, make your change and open a [pull request](https://github.com/yahya3886/sansur-asma-toollari/pulls).

### When adding information

This page is about people's safety, so accuracy matters.

- If you add a claim about a tool or provider, verify it against the project's own site or an independent source.
- Put the source of audit, date and version information in the pull request description.
- Don't oversell a tool. Say what each tool can't get past, too.

### How translation works

The Turkish text lives directly in the HTML. The English versions are in the `EN` dictionary in the script at the bottom of the page. The dictionary keys are the Turkish sentences themselves.

So if you change a Turkish sentence, you must change its key in the dictionary the same way. Otherwise that sentence stays in Turkish in English mode. The texts in the explanation panel are in the `PANEL` object inside the script.

## Disclaimer

This site is for general information. It is not legal or security advice. Using these tools is restricted in some countries. Learn the rules and your own risk in advance. The features of the tools and the blocking methods change over time, so read each project's current documentation before you decide.

## Sources

- [Tor Project](https://www.torproject.org)
- [Snowflake](https://snowflake.torproject.org)
- [Psiphon](https://psiphon.ca)
- [Lantern](https://getlantern.org)
- [Outline](https://getoutline.org)
- [Quad9](https://www.quad9.net)

## License

This project is released under the [MIT License](LICENSE).
