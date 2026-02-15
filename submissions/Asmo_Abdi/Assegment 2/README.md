# Assignment 2 — Data Foundations for Machine Learning

## Title & Collection Method

**Title:** Online Small Business Activity Dataset  

Dataset-kan wuxuu ku saabsan yahay ganacsiyada yaryar ee online-ka ah ee ay leeyihiin dadka Soomaaliyeed.

Xogta waxaa lagu ururiyey Google Form oo aan sameeyey, kadibna waxaan la wadaagay dadka ganacsiyada online-ka leh. Dadka ayaa si toos ah uga jawaabay su’aalaha, xogtana si otomaatig ah ayaa loo keydiyey. Ugu dambeyn, CSV file ayaan kasoo dejiyey Google Forms.

---

## Description of Features & Label

### Features (X)

1. **Taariikhda jawaabta (Timestamp)**  
   — Waqtiga uu qofku buuxiyey form-ka  

2. **Nooca ganacsiga** (Categorical)  
   — Tusaale: Dhar, Cosmetics, Electronics, Cunto, Beauty Products  

3. **Mudada ganacsiga socday (bilaha)** (Numeric)

4. **Ma isticmaashaa xayeysiin?** (Categorical: Haa / Maya)

5. **Lacagta bishii lagu bixiyo xayeysiinta** (Numeric — Dollar)

6. **Platform-ka ugu badan ee aad ku iibiso** (Categorical)  
   — TikTok, Facebook, WhatsApp, Instagram  

7. **Celceliska farriimaha macaamiisha maalintii** (Numeric)

---

### Label (y)

**Heerka faa’iidada ganacsiga bishii** (Categorical)

- Faa’iido Hoose (Low)
- Faa’iido Sare (High)

➡️ Tani waxay ka dhigeysaa dataset-kan **classification problem**

---

## Dataset Structure

- Rows (samples): 51 ganacsi
- Columns: 8 (7 features + 1 label)

### Sample Table

Fiiro gaar ah: Timestamp column lama gelin sample table-ka si loo fududeeyo aragtida xogta.

| Business Type | Months Active | Advertising | Ad Cost | Platform | Messages/Day | Profit |
|---------------|--------------|-------------|---------|----------|---------------|--------|
| Dhar          | 5            | Haa         | 20      | TikTok   | 10            | Low    |
| Beauty        | 4            | Maya        | 0       | TikTok   | 2             | Low    |
| Electronics   | 15           | Haa         | 6       | TikTok   | 5             | High   |
| Dhar          | 6            | Haa         | 7       | Instagram| 7             | High   |
| Cunto         | 34           | Maya        | 0       | TikTok   | 20            | High   |

---

## Quality Issues

Dataset-kan wuxuu leeyahay dhibaatooyin caadi ah oo laga helo xog dhab ah:

- Qoraal kala duwan oo isku macno ah (Cosmetics vs Beauty Products)
- Qaab isku dhafan oo Somali iyo English ah
- Xog aan isku dheellitirnayn (High profit ayaa badan marka loo eego Low)
- Qaar ka mid ah ganacsiyada ma isticmaalaan xayeysiin (Ad Cost = 0)
- Outliers (tusaale: ganacsi socday 800+ bilood)
- Kala duwanaansho jawaabaha platform-ka

Dataset-kan waa mid “messy”, taas oo ku habboon preprocessing-ka Lesson 3.

---

## Use Case

Dataset-kan waxaa loo isticmaali karaa mashruuc Machine Learning ah si loo saadaaliyo heerka faa’iidada ganacsiga online-ka ah iyadoo lagu saleynayo astaamaha ganacsiga.

### Possible ML Tasks

- Classification — saadaalinta faa’iido (Low vs High)
- Business performance analysis
- Customer engagement insights
- Decision support for small business owners

### Possible Algorithms

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine  

---

## Conclusion

Dataset-kan wuxuu ka tarjumayaa xaaladda dhabta ah ee ganacsiyada yaryar ee online-ka ah ee Soomaalida, wuxuuna ku habboon yahay barashada Data Foundations, Data Preprocessing, iyo Machine Learning.

By Asmo Abdi