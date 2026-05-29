# Zeydoo Офер 19832 — Звіт тестування 🇧🇩 Bangladesh

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
