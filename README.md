# Kalkan

Kalkan is a lightweight ad blocker for Chrome that handles ads, trackers and cookie banners in one extension.
Blocking runs on Chrome's own rule engine (declarativeNetRequest): it doesn't slow pages down and sends no data anywhere.

This repository holds Kalkan's public pages: the [privacy policy](PRIVACY.md) and the issue tracker for support.
The extension's source code is not published here.

## Features

- **Ads and trackers:** blocks requests to ad networks and tracking services and hides the empty ad boxes they leave behind.
- **Cookie banners:** clicks "Reject all" on 90 consent platforms. If there is no reject option, it hides the banner. It never clicks "Accept".
- **YouTube ads:** removes video ads before they reach the player and hides sponsored cards.
- **Other video players:** players that use Google IMA get an empty answer to their ad requests, so the video starts right away.
- **Who was tracking you?** The popup lists the domains blocked on the page, who owns them and what they tried to collect, sorted into four risk levels.
- **Pick an element to hide:** click any leftover ad to hide it on that site for good.
- **Per-site control:** pause Kalkan on a single site if something breaks.

Languages: English, Turkish, German, French, Spanish.

## Privacy

Kalkan needs no account, has no server and collects no data. Read the full [privacy policy](PRIVACY.md).

## Support

Found a broken site, a missed ad or a cookie banner that stayed?
[Open an issue](../../issues/new/choose). The issue tracker is public, so please don't post personal information.

---

## Türkçe

Kalkan; reklamları, izleyicileri ve çerez pencerelerini tek eklentide engelleyen hafif bir Chrome reklam engelleyicisidir.
Hesap istemez, sunucusu yoktur, hiçbir veri toplamaz: [Gizlilik politikası](PRIVACY.md#türkçe).

Bir sitede sorun mu var? Kalkan'ı o sitede duraklatın, simgedeki "Test raporunu kopyala" ile raporu alın ve
[yeni bir kayıt açın](../../issues/new/choose). Kayıtlar herkese açıktır; kişisel bilgi paylaşmayın.
