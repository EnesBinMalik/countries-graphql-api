<div align="center">

<img src="docs/01-kapak.png" alt="Countries GraphQL API — Enes Öztürk imzalı proje" width="100%">

# Countries GraphQL API

**7 kıta, 51 ülke ve 38 dili ilişkili biçimde sorgulayabilen tam teşekküllü GraphQL backend ve geliştirici stüdyosu.**

[![GraphQL](https://img.shields.io/badge/GraphQL-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/countries-graphql-api)
[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/countries-graphql-api)
[![TypeScript](https://img.shields.io/badge/TypeScript-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/countries-graphql-api)
[![Express](https://img.shields.io/badge/Express-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/countries-graphql-api)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/countries-graphql-api)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

Countries GraphQL API; kıtalar, ülkeler ve diller arasındaki çift yönlü ilişkileri tarayıcı üzerinden keşfetmenizi sağlar. Express tabanlı `/graphql` uç noktası, elle yazılmış şema ve çözümleyicilerle çalışır; arayüzdeki stüdyo gerçek sorguları çalıştırır, sonuçları biçimlendirir ve cURL olarak dışa aktarır.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **GraphQL Studio** | Sorgu editörü, değişken paneli, `Ctrl + Enter` ile çalıştırma. |
| **8 örnek sorgu** | Tek tıkla çalışan gereksinim ve ilişkisel sorgu şablonları. |
| **Data Explorer** | Kıta → ülke → dil ilişkilerini görsel olarak gezinme. |
| **Schema & Docs** | Tipler, alanlar ve açıklamalarla şema dökümü. |
| **cURL & Integration** | Sorguyu doğrudan cURL komutuna dönüştürme. |
| **Format / Kopyala / İndir** | Sorgu düzenleme ve dışa aktarma araçları. |

---

## Veri seti

| Ölçü | Değer |
| --- | --- |
| Kıta | 7 |
| Ülke | 51+ |
| Dil | 38 |
| İlişki | Çift yönlü |

---

## Galeri

<img src="docs/02-ekran.png" alt="Countries GraphQL API ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="Countries GraphQL API etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="Countries GraphQL API detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/countries-graphql-api.git
cd countries-graphql-api
npm install
npm run start
```

> Hem tarayıcı içi stüdyo hem de Express sunucusu aynı çözümleyiciyi kullanır.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/graphql/data.ts       Kıta, ülke ve dil veri kümesi
src/graphql/executor.ts   Sorgu çözümleyici ve doğrulama
src/graphql/samples.ts    Hazır örnek sorgular
src/components/           Studio, Explorer, Schema, Docs
server.ts                 Express /graphql uç noktası
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
