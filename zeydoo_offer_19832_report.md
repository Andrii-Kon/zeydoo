# Zeydoo Офер 19832 — Звіт тестування

**Офер:** [CPL] WW | Playable Dream Coin  
**ID офера:** 19832  
**Вхідний URL:** `https://ldl1.com/link?z=10875908&var={pid}_{source}&ymid={clickid}`  
**Сетап:** Octo Browser (Android fingerprint) + residential proxy  

---

## Як працює флоу

1. Вхідний URL відкривається → редіректить на playable лендинг на `cdn.ak2yy.com`
2. **Клік START** → вкладка з лендингом залишається відкритою + **Destination 1** автоматично відкривається у новій вкладці
3. Проходить coin tap гра
4. **Клік CONTINUE** → основна вкладка переходить на **Destination 2** + **Destination 3** автоматично відкривається у новій вкладці

Кожен тестовий запуск дає **3 destination** загалом:

- Destination 1 — бокова вкладка, відкривається при кліку START
- Destination 2 — основна вкладка, відкривається при кліку CONTINUE
- Destination 3 — бокова вкладка, відкривається при кліку CONTINUE

---

## Тестові запуски

---

### Запуск 001 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Скріншот                                     |
| ------------- | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [www.casinoplus.com.ph](https://www.casinoplus.com.ph/home?partnerId=1000025558&mVoluumId=w5pvlsmj641buknijctocihm)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Фінальний офер | <img src="destination 1/casino-plus-ph.png" width="150">           |
| Destination 2 | CONTINUE (основна вкладка) | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.259285&currency=usd&external_id=1083845107037513515&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=medium)                                                                                                                                                                                                                                                                                       | Прелендінг | <img src="destination 2/giveaway-urbanexplore-ph.png" width="150"> |
| Destination 3 | CONTINUE (нова вкладка)    | [cdn.ethnichomeindia.com](https://cdn.ethnichomeindia.com/tml/mammonTurnLottie2.html?v=2604222019-3#/?reqId=ad118ab9c1fa4f36b408e328c706daa3&did=178e30d3-4aae-447b-9e76-bec9f4e3b8de&dtype=1&lang=tl&uid=178e30d3-4aae-447b-9e76-bec9f4e3b8de&appk=4WEfqMmPKpyK2Wb1YbmV9B5XuMd5OmL6&d.psubid=10657865&d.pst=1&d.ptkid=1083845132343058569&os=1&jsv=2605281747&d.algId=44&d.rankab=4&pid=20710&tid=5032) | Прелендінг | <img src="destination 3/lucky-draw-free-money-ph.png" width="150"> |


---

### Запуск 002 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                | Скріншот                                             |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [www.casinoplus.com.ph](https://www.casinoplus.com.ph/home?partnerId=1000025558&mVoluumId=w4b02uamlcojclni3b7us0ra)                                                                                                                                                                                                                                                                     | Фінальний офер | <img src="destination 1/casino-plus-ph-run2.png" width="150">              |
| Destination 2 | CONTINUE (основна вкладка) | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=&currency=usd&external_id=1083854081398153275&creative_id=24845588&ad_campaign_id=10134007&zone_id=10657865&subzone_id=&zone_type=in-page-push&exit_type=not_survey)                               | Прелендінг | <img src="destination 2/urbanexplore-inpage-push-ph-run2.png" width="150"> |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.042819&currency=usd&external_id=1083854064162443763&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=&zone_type=&exit_type=giveaway&user_activity=medium) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run2.png" width="150">    |


---

### Запуск 003 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Скріншот                                          |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [www.casinoplus.com.ph](https://www.casinoplus.com.ph/home?partnerId=1000029574&mVoluumId=wnvr9n9s2b2p6lnijb6hfg0f&cid=wnvr9n9s2b2p6lnijb6hfg0f)                                                                                                                                                                                                                       | Фінальний офер | <img src="destination 1/casino-plus-ph-run3.png" width="150">           |
| Destination 2 | CONTINUE (основна вкладка) | [telepleaseapp.cfd](https://telepleaseapp.cfd/hello1/?lp_key=1779955e418d593d9cb59eafdc9fea4fc686975172&xts=44&xco=4&xcd=autoversions.com&xan=16&clickid=d8c45m5j19hc73977vp0)                                                                                                                                                   | Прелендінг | <img src="destination 2/teleplease-app-ph-run3.png" width="150">        |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.173928&currency=usd&external_id=1083855753674233279&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=medium) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run3.png" width="150"> |


---

### Запуск 004 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Скріншот                                          |
| ------------- | -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [1xlite-62368.bar](https://1xlite-62368.bar/tl/slots?tag=d_131637m_14189c_[]MS[]null[]PB_slots[]slots[]118146240_d27082_l220463_clickunder&pb=ca7c0b52e4d34f819b39b4863c3bf0c0&click_id=06bf1f84a5418aee8ec26a05c929f3c4&r=slots)                                                                                                                                                                                                                                                                                                                                                                                               | Фінальний офер | <img src="destination 1/1xbet-slots-ph-run4.png" width="150">           |
| Destination 2 | CONTINUE (основна вкладка) | [cdn.ethnichomeindia.com](https://cdn.ethnichomeindia.com/tml/giftSetMC.html?v=2604171705-3#/?osv=13.0.0&d.pext=201969&d.pst=1&d.psubid=10657861&d.rankab=4&did=5e320e9c-f1f0-413d-98b2-49e8338ffdbf&dtype=1&os=1&lang=tl&model=NTH-NX9&jsv=2605281747&pid=20812&uid=5e320e9c-f1f0-413d-98b2-49e8338ffdbf&appk=oJpKU26bMqATXyAUNPoirm44iYjF0oHd&tid=1664&d.algId=44&reqId=11cc683e21a249ef95b8c81b45387715&d.ptkid=1083856815969805107) | Прелендінг | <img src="destination 2/gift-set-lucky-draw-ph-run4.png" width="150">   |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.204789&currency=usd&external_id=1083856815969805207&creative_id=25367845&ad_campaign_id=10452386&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=medium)                                                                                                                                                                                                                                                                                                                                                     | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run4.png" width="150"> |


---

### Запуск 005 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                          |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [www.casinoplus.com.ph](https://www.casinoplus.com.ph/home?partnerId=1000029574&mVoluumId=wiekfkr9afbntlni39b0ikk6&cid=wiekfkr9afbntlni39b0ikk6)                                                                                                                                                                                                                 | Фінальний офер | <img src="destination 1/casino-plus-ph-run5.png" width="150">           |
| Destination 2 | CONTINUE (основна вкладка) | [telepleaseapp.cfd](https://telepleaseapp.cfd/hello1/?lp_key=1779955e418d593d9cb59eafdc9fea4fc686975654&xts=44&xco=4&xcd=autoversions.com&xan=16&clickid=d8c49elj19hc7397atj0)                                                                                                                                             | Прелендінг | <img src="destination 2/teleplease-app-ph-run5.png" width="150">        |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.188532&currency=usd&external_id=1083857785969713401&creative_id=25367845&ad_campaign_id=10452386&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run5.png" width="150"> |


---

### Запуск 006 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                          |
| ------------- | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [telepleaseapp.cfd](https://telepleaseapp.cfd/hello1/?lp_key=1779955e418d593d9cb59eafdc9fea4fc686975806&xts=44&xco=4&xcd=autoversions.com&xan=16&clickid=d8c4aklj19hc7397bprg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Прелендінг | <img src="destination 1/teleplease-app-ph-run6.png" width="150">        |
| Destination 2 | CONTINUE (основна вкладка) | [cdn.ethnichomeindia.com](https://cdn.ethnichomeindia.com/tml/LuckyBonus.html?v=2604201710-3#/?appk=4WEfqMmPKpyK2Wb1YbmV9B5XuMd5OmL6&jsv=2605281747&osv=13.0.0&d.pst=1&reqId=d29833624e824031aecb86f3be64544f&pid=20710&tid=8569&dtype=1&d.psubid=10657865&d.algId=24&os=1&uid=3f50643b-a31b-4f43-9767-3338b6b03c26&d.rankab=2&did=3f50643b-a31b-4f43-9767-3338b6b03c26&lang=tl&model=NTH-NX9&d.ptkid=1083858481105608865) | Прелендінг | <img src="destination 2/lucky-bonus-ph-run6.png" width="150">           |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.140685&currency=usd&external_id=1083858480785535041&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low)                                                                                                                                                                                                                                                                                                                                 | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run6.png" width="150"> |


---

### Запуск 007 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                           |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [landing.winzir.ph](https://landing.winzir.ph/?btag=WZPH_l379959)                                                                                                                                                                                                                                                                                                                                                                       | Фінальний офер | <img src="destination 1/winzir-casino-ph-run7.png" width="150">          |
| Destination 2 | CONTINUE (основна вкладка) | [getmediavids.cfd](https://getmediavids.cfd/safevideo/?lp_key=17799bd8e9070595951719c78f5ac3888da6075988&xts=4&xz=10657865&xcd=mediaruns1.click&xco=4&xcc=PH&xan=4&clickid=d8c4c2011plc739if030)                                                                                                       | Прелендінг | <img src="destination 2/getmediavids-safevideo-ph-run7.png" width="150"> |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.133036&currency=usd&external_id=1083859167929964483&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run7.png" width="150">  |


---

### Запуск 008 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                          |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [landing.winzir.ph](https://landing.winzir.ph/?btag=WZPH_l379959)                                                                                                                                                                                                                                                                                                                                                                       | Фінальний офер | <img src="destination 1/winzir-casino-ph-run8.png" width="150">         |
| Destination 2 | CONTINUE (основна вкладка) | [telepleaseapp.cfd](https://telepleaseapp.cfd/hello1/?lp_key=1779955e418d593d9cb59eafdc9fea4fc686976183&xts=44&xco=4&xcd=autoversions.com&xan=16&clickid=d8c4ditj19hc7397e3ag)                                                                                                                                             | Прелендінг | <img src="destination 2/teleplease-app-ph-run8.png" width="150">        |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.129775&currency=usd&external_id=1083859986641336117&creative_id=25367845&ad_campaign_id=10452386&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run8.png" width="150"> |


---

### Запуск 009 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  

Результат ідентичний Запуску 008. Ті самі три destination.

---

### Запуск 010 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                           |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [puiselink.xyz](https://puiselink.xyz/?sub1=3vk389b.38.p2icto&fb_dynamic_pixel=886505614038463&subid=3vk389b.38.p2icto)                                                                                                                                                                                                                                                   | Прелендінг | <img src="destination 1/puiselink-ph-run10.png" width="150">             |
| Destination 2 | CONTINUE (основна вкладка) | [telepleaseapp.cfd](https://telepleaseapp.cfd/hello1/?lp_key=1779955e418d593d9cb59eafdc9fea4fc686976518&xts=44&xco=4&xcd=autoversions.com&xan=16&clickid=d8c4g6lj19hc7397g7p0)                                                                                                                                             | Прелендінг | <img src="destination 2/teleplease-app-ph-run10.png" width="150">        |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.121545&currency=usd&external_id=1083861404790035145&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run10.png" width="150"> |


---

### Запуск 011 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  

Результат ідентичний Запуску 010. Ті самі три destination.

---

### Запуск 012 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  


| #             | Тригер                     | Фінальний URL                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Скріншот                                           |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- --- |
| Destination 1 | START (нова вкладка)       | [puiselink.xyz](https://puiselink.xyz/?sub1=3vk389b.38.p2j0t2&fb_dynamic_pixel=886505614038463&subid=3vk389b.38.p2j0t2)                                                                                                                                                                                                                                                   | Прелендінг | <img src="destination 1/puiselink-ph-run12.png" width="150">             |
| Destination 2 | CONTINUE (основна вкладка) | [saasprint.com](https://saasprint.com/?var_1=1083862590842742107&var_2=10657861)                                                                                                                                                                                                                                                                                                                                 | Прелендінг | <img src="destination 2/saasprint-ph-run12.png" width="150">             |
| Destination 3 | CONTINUE (нова вкладка)    | [urbanexplorenow.com](https://urbanexplorenow.com/n9PSLJ5w?cost=0.119335&currency=usd&external_id=1083862603471786891&creative_id=25038424&ad_campaign_id=10253627&zone_id=10657719&subzone_id=200699&zone_type=&exit_type=giveaway&user_activity=low) | Прелендінг | <img src="destination 3/urbanexplore-giveaway-ph-run12.png" width="150"> |


---

### Запуск 013 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  

Без нових destination. Всі три вже були раніше: Puiselink, LuckyBonus (ethnichomeindia), Urban Explore Giveaway.

---

### Запуск 014 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  

Без нових destination. Всі три вже були раніше.

---

### Запуск 015 — 🇵🇭 Філіппіни

**Проксі:** Gonzo — Philippines (PH)  

Без нових destination. Всі три вже були раніше.

---

