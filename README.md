# VPN / DIRECT Rules Config для Koala Clash

Этот репозиторий содержит готовый набор правил для VPN-клиентов (Clash)

## 🔹 Что внутри
- **DIRECT** (мимо VPN):
   Игры (Steam, CS:GO, Dota 2, PUBG, Valorant, Fortnite, Blizzard, Ubisoft, Minecraft и др.)
   Античиты (BattlEye, Vanguard, EasyAntiCheat)
   Сервисы Valve (IP-диапазоны, домены)

- **VPN** (через VPN):
   Аниме-сайты (shikimori, jut.su, anilib, animego и др.)
   Музыкальные площадки (Spotify, Deezer, Pandora, Tidal, YouTube Music и др.)
   Популярные block РФ сервисы (YouTube, Twitch, Discord, Telegram, Twitter, Facebook, Instagram, Reddit и др.)

## 📌 Использование
1. Скопируй содержимое `rules.json` в свой конфиг..
2. Перезапусти клиент и проверь в логах, что правила применяются.

## ⚠️ Примечания
Правила `PROCESS-NAME` работают только на Windows и при поддержке клиента.
Если у тебя MacOS/Linux — используй только `DOMAIN` и `IP-CIDR`.
Список можно расширять под свои нужды.

### 📌 ВАЖНО В МАРШРУТАХ ИДЕТ СЛОВО VPN -> 'DOMAIN-SUFFIX,DS.COM,VPN' ЭТО ВАШЕ ПРАВИЛО КОТОРОЕ НАЗЫВАЕТСЯ В САМОМ CLASH,нужно чтобы оно совпадало с правилами в маршрутах

