# Geo-Aggregator

Автономный агрегатор GeoIP и GeoSite данных. Объединяет мировые и российские базы в текстовые списки по категориям, обновляется ежедневно.

## Использование

Прямая ссылка на домены категории (N — номер папки от 1):
```
https://raw.githubusercontent.com/OLAF74/Geo-Aggregator/main/data-<N>/<tag>/domains.txt
```
Прямая ссылка на ip категории (N — номер папки от 1):
```
https://raw.githubusercontent.com/OLAF74/Geo-Aggregator/main/data-<N>/<tag>/ips.txt
```
Прямая ссылка на домены+ip категории (N — номер папки от 1):
```
https://raw.githubusercontent.com/OLAF74/Geo-Aggregator/main/data-<N>/<tag>/all.txt
```
| :exclamation:  Учтите, что ips.txt или domains.txt могут отсутствовать. all.txt присутствует всегда |
|-----------------------------------------------------------------------------------------------------|


## Источники

| Репозиторий | Данные |
|---|---|
| [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) | IP + домены (proxy, gfw, reject и др.) |
| [v2fly/geoip](https://github.com/v2fly/geoip) | IP-диапазоны по странам и сервисам |
| [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) | Домены (1400+ тегов) |
| [runetfreedom/russia-v2ray-rules-dat](https://github.com/runetfreedom/russia-v2ray-rules-dat) | IP + домены РФ (заблокированные) |
| [itdoginfo/allow-domains](https://github.com/itdoginfo/allow-domains) | Домены РФ (inside/outside) |
| [antifilter.download](https://antifilter.download) | IP-адреса + домены (АнтиФильтр) |
| [DanielLavrushin/b4geoip](https://github.com/DanielLavrushin/b4geoip) | IP-диапазоны (расширенная база RUNETFREEDOM) |

---

*Автоматически сгенерировано GitHub Actions · 1727 категорий · 2026-07-24 05:44 UTC*
