# Pair Selection Analysis — Consumer Staples

> Business-fit scores are subjective qualitative assessments.

## 2. Full company names, all 15 candidate pairs

Sebenarnya ada **14 unique companies** dalam 15 pairs tersebut.

| Ticker | Full company name                  | Main business / brands                                           |
| ------ | ---------------------------------- | ---------------------------------------------------------------- |
| CL     | Colgate-Palmolive                  | Oral care, personal care, home care; Colgate, Palmolive, Hill's  |
| KMB    | Kimberly-Clark                     | Personal hygiene, diapers, tissues; Huggies, Kleenex, Kotex      |
| KO     | The Coca-Cola Company              | Soft drinks, water, juices; Coca-Cola, Sprite, Fanta             |
| SYY    | Sysco Corporation                  | Foodservice wholesaler and distributor to restaurants            |
| BF-B   | Brown-Forman Corporation (Class B) | Whiskey, spirits; Jack Daniel's, Woodford Reserve                |
| STZ    | Constellation Brands               | Beer, wine, spirits; Modelo, Corona, Kim Crawford                |
| PM     | Philip Morris International        | Tobacco and nicotine products; Marlboro (outside the US in 2022) |
| PG     | Procter & Gamble                   | Household and personal care; Pampers, Tide, Crest, Gillette      |
| PEP    | PepsiCo                            | Soft drinks and convenient foods; Pepsi, Gatorade, Lay's         |
| SJM    | The J.M. Smucker Company           | Coffee, pet food, spreads; Folgers, Jif, Smucker's               |
| KDP    | Keurig Dr Pepper                   | Soft drinks and coffee; Dr Pepper, 7UP, Keurig                   |
| KHC    | The Kraft Heinz Company            | Packaged foods and condiments; Heinz, Kraft, Philadelphia        |
| MDLZ   | Mondelēz International             | Biscuits, chocolate and snacks; Oreo, Ritz, Cadbury              |
| MKC    | McCormick & Company                | Spices, seasoning and condiments; McCormick, French's            |

The business descriptions are supported by company filings, including 2022 annual reports for Colgate-Palmolive, Kimberly-Clark, PepsiCo, Keurig Dr Pepper, Smucker, Sysco, Mondelēz and McCormick.

_Original source marker: sec.gov +7._

## 3. Evaluasi seluruh 15 pairs

Aku nilai kedekatan bisnisnya dari **1–5**. Ini qualitative judgment, bukan angka statistik dari notebook.

| Rank | Pair     | SSE    | Business fit | Recommendation                                                |
| ---- | -------- | ------ | ------------ | ------------------------------------------------------------- |
| 1    | CL–KMB   | 0.2450 | 3/5          | Alternative. Consumer hygiene, tetapi core products berbeda   |
| 2    | KO–SYY   | 0.3527 | 2/5          | Reject. Beverage producer vs foodservice distributor          |
| 3    | BF-B–STZ | 0.4721 | 4/5          | Select. Alcoholic beverages                                   |
| 4    | KO–PM    | 0.4745 | 1/5          | Reject. Beverages vs tobacco                                  |
| 5    | CL–PG    | 0.4800 | 5/5          | Select. Direct competition in oral, personal and home care    |
| 6    | PEP–SJM  | 0.5292 | 3/5          | Conditional select. Some packaged food overlap                |
| 7    | KMB–PG   | 0.5607 | 5/5          | Select. Direct competition in diapers, tissues, feminine care |
| 8    | CL–STZ   | 0.5769 | 1/5          | Reject. Personal care vs alcohol                              |
| 9    | KDP–PEP  | 0.5797 | 5/5          | Select. Direct soft drink competitors                         |
| 10   | KHC–KO   | 0.6235 | 2/5          | Reject. Small beverage overlap, different core businesses     |
| 11   | CL–MDLZ  | 0.6323 | 1/5          | Reject. Personal care vs snacks                               |
| 12   | KMB–MDLZ | 0.6351 | 1/5          | Reject. Hygiene vs snacks                                     |
| 13   | MDLZ–STZ | 0.6807 | 1/5          | Reject. Snacks vs alcoholic beverages                         |
| 14   | MKC–PG   | 0.7108 | 1/5          | Reject. Spices vs household care                              |
| 15   | KMB–STZ  | 0.7455 | 1/5          | Reject. Hygiene vs alcoholic beverages                        |

## 4. Why these five? With evidence

### CL–PG

**Business fit: 5/5 · SSE: 0.4800 · Rank: 5**

Both directly compete in oral care, personal care and home cleaning products. Colgate competes against Crest, while Palmolive dishwashing products overlap with P&G's Dawn business.

**Evidence:** Colgate's 2022 revenue mix was 43% oral care, 19% personal care and 17% home care. These categories represent substantial overlap with P&G's existing product divisions.

### KMB–PG

**Business fit: 5/5 · SSE: 0.5607 · Rank: 7**

One of the clearest competitor pairs.

Directly overlapping brands include Huggies vs Pampers (diapers), Kotex vs Always (feminine care), and Kleenex/Scott vs Puffs/Charmin (tissue products).

**Evidence:** Both companies' 2022 annual reports identify these product categories and brands as major business lines. They therefore share exposure to hygiene demand, raw-material costs and retail pricing conditions.

### KDP–PEP

**Business fit: 5/5 · SSE: 0.5797 · Rank: 9**

Both compete in North American carbonated soft drinks and other non-alcoholic beverages. PepsiCo owns Pepsi and Mountain Dew, while KDP owns Dr Pepper and other soft-drink brands.

**Evidence:** KDP's 2022 Form 10-K identifies carbonated soft drinks as a major business; PepsiCo's 2022 filing identifies beverages as a dedicated division. Both are exposed to beverage demand, packaging costs and distribution economics.

### BF-B–STZ

**Business fit: 4/5 · SSE: 0.4721 · Rank: 3**

Both manufacture and market alcoholic beverages. Brown-Forman focuses on whiskey and spirits, while Constellation sells beer, wine and spirits.

**Evidence:** Constellation's FY2022 sales included $6.75B in beer and $2.07B in wine and spirits. Brown-Forman's 2022 results highlight Jack Daniel's, Woodford Reserve and tequila brands.

**Limitation:** STZ was predominantly beer, while BF-B was predominantly spirits. The businesses are related, but not identical.

### PEP–SJM

**Business fit: 3/5 · SSE: 0.5292 · Rank: 6**

Both have packaged consumer food businesses. PepsiCo sells Frito-Lay snacks and Quaker foods, while Smucker sells Uncrustables frozen sandwiches, Jif peanut butter and Smucker's fruit spreads.

**Evidence:** Smucker's FY2022 U.S. Retail Consumer Foods sales were about $1.71B, approximately 21% of its total reported sales. PepsiCo also had substantial convenient food businesses.

**Limitation:** Smucker's was heavily exposed to coffee and pet food, so this is not a close competitor pairing across the companies' entire portfolios.

## 5. The important tradeoff: CL–KMB or PEP–SJM?

Ini bagian yang paling layak kita diskusikan sebelum mengunci keputusan.

Awalnya kamu memilih:

```text
CL–KMB, BF-B–STZ, CL–PG, KMB–PG, KDP–PEP
```

Masalahnya, **CL–KMB, CL–PG, dan KMB–PG membentuk triangle**. Artinya tiga dari lima pair terfokus pada tiga perusahaan yang sama.

Aku akan bandingkan dua pilihan berikut:

| Criterion           | Keep CL–KMB                 | Replace with PEP–SJM                |
| ------------------- | --------------------------- | ----------------------------------- |
| SSE                 | 0.2450 (better)             | 0.5292                              |
| Business similarity | Moderate                    | Moderate                            |
| Sector coverage     | 3 broad business groups     | 4 broad business groups             |
| Redundancy          | Three-pair hygiene triangle | PG and PEP each appear twice        |
| Main advantage      | Best formation SSE          | Broader business exposure           |
| Main weakness       | Considerable overlap        | Weaker direct business relationship |

My preferred selection, given the professor's emphasis on avoiding redundant pairs:

### Final 5 proposal — Qualitative selection

| No. | Pair     | Business rationale         |
| --- | -------- | -------------------------- |
| 1   | CL–PG    | Oral, personal & home care |
| 2   | KMB–PG   | Hygiene & household paper  |
| 3   | KDP–PEP  | Non-alcoholic beverages    |
| 4   | BF-B–STZ | Alcoholic beverages        |
| 5   | PEP–SJM  | Packaged foods             |

Tetapi ini bukan keputusan mutlak. Kalau kita menilai business similarity lebih penting daripada mengurangi redundancy, CL–KMB justru lebih defensible daripada PEP–SJM. Belum ada pengujian out-of-sample yang membuktikan salah satunya lebih profitable.

## 6. Data tambahan yang perlu kita pertimbangkan

Contoh kenapa tidak cukup hanya melihat company name:

**KO–SYY** memiliki SSE 0.3527, tetapi Sysco adalah foodservice distributor, bukan beverage manufacturer seperti Coca-Cola. Bahkan pada 2022, beverage products hanya menyumbang 3% penjualan Sysco, sedangkan restoran merupakan 63% dari customer sales mix. Itu alasan kuat untuk tidak menganggap keduanya direct competitors.

**KHC–KO** juga punya sedikit overlap melalui Kool-Aid dan Capri Sun. Namun Kraft Heinz melaporkan platform Flavorful Hydration hanya 8% dari total sales 2022, sehingga kemiripannya dengan Coca-Cola tidak dominan.

Kita bisa menggunakan bukti seperti ini untuk menjelaskan kenapa ranking SSE 2 dan 10 tidak dipilih.

Sumber terbaik untuk report adalah **Form 10-K, Item 1: Business**, lalu product categories, segment revenues dan competition. Angka-angka di atas berasal dari FY2022 filings (beberapa diterbitkan pada awal 2023 dan menggambarkan kondisi 2022). Untuk aturan ex-ante yang benar-benar ketat, gunakan juga dokumen yang sudah dipublikasikan sebelum Januari 2023.

### Next decision

Aku lebih condong ke empat pasangan yang jelas, yaitu **CL–PG, KMB–PG, KDP–PEP, BF-B–STZ**. Untuk pasangan kelima, kita perlu memutuskan apakah lebih menghargai SSE yang sangat rendah dan business fit cukup baik pada CL–KMB, atau cakupan industri yang lebih luas dengan PEP–SJM.

Itulah tradeoff terpenting yang harus diselesaikan, daripada sekadar mengikuti ranking.
