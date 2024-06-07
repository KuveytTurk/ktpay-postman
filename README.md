# ktpay-postman 

[![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)](https://www.postman.com/osmanozencom/workspace/ktpay)
[![GitHub Release](https://img.shields.io/github/v/release/kuveytturk/ktpay-postman?style=flat-square&color=ff4f00)](https://github.com/kuveytturk/ktpay-postman/releases)
[![GitHub License](https://img.shields.io/github/license/kuveytturk/ktpay-postman?style=flat-square)](https://github.com/kuveytturk/ktpay-postman/blob/main/LICENSE)

Bu proje, Kuveyt Türk Katılım Bankası Sanal POS servisleri için geliştirilen entegrasyon methodlarını içermektedir. Proje içerisinde yer alan method ve istek yapıları, Kuveyt Türk Katılım Bankası tarafından sunulan çevrimiçi ödeme hizmetlerini entegre etmek ve sanal pos işlemlerini gerçekleştirmek amacıyla kullanılabilir. Aksi kullanımlar banka tarafından tespit edilip cezai yaptırımlar uygulanmaktadır.

Entegrasyon sırasında karşılaşılan hataların çözümü için [Kuveyt Türk Sanal POS Destek](mailto:sanalposdestek@kuveytturk.com.tr) ekibi ile iletişime geçebilirsiniz.

[English](https://github.com/kuveytturk/ktpay-postman/blob/main/README-EN.md)

## Gereksinimler

* **Postman**

## Kurulum

 ```bash
# Proje dosyalarını yerel bilgisayarınıza klonlayın ve .json dosyalarını Postman arayüzünden içeri aktarın. 
git clone https://github.com/kuveytturk/ktpay-postman.git
```

## Kullanım

> Kuveyt Türk Sanal POS methodlarının tümü Postman üzerinden istek atılarak manuel testler gerçekleştirilebilir.

![methods](https://raw.githubusercontent.com/kuveytturk/ktpay-postman/main/img/1-methods.png)

> Hazırlanan Postman koleksiyonu esnek yapısı sayesinde ortamsal bazlı testler gerçekleştirilebilir.

![environments](https://raw.githubusercontent.com/kuveytturk/ktpay-postman/main/img/2-environments.png)

> Dinamik istek yapısı ve otomatik HashData hesaplamaları ile yük testleri gerçekleştirilebilir.

![pre-request-script](https://raw.githubusercontent.com/kuveytturk/ktpay-postman/main/img/3-pre-request-script.png)

> Sanal POS methodlarına ait test senaryoları ile regresyon testleri gerçekleştirilebilir.

![tests](https://raw.githubusercontent.com/kuveytturk/ktpay-postman/main/img/4-tests.png)

> Kuveyt Türk Sanal POS methodlarını farklı programlama dilleri ve yazılım frameworklerine ait kod blokları kolaylıkla üretilebilir.

![code-snippet](https://raw.githubusercontent.com/kuveytturk/ktpay-postman/main/img/5-code-snippet.png)

## Lisans

Bu proje MIT altında lisanslanmıştır. Ayrıntılar için [LİSANS](https://github.com/kuveytturk/ktpay-postman/blob/main/LICENSE) dosyasını inceleyin.