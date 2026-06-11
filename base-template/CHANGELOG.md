# CHANGELOG — base-template

Версия = номер верхней записи. base — источник правды type-независимой механики. Его изменение раскатывается на классовые шаблоны и мета-проект операцией «распространить base» ([methodology/propagate.md](../../methodology/propagate.md)); у каждого потомка поднимается своя версия с записью `[base]`. Версию двигает только изменение, которое стоит распространять (косметика — нет).

## v1 — 2026-06-10
Учредительная версия. Состояние base после выделения скелета ([ADR-0008](../../wiki/decisions/adr-0008-base-template.md)), дисциплины синтеза при закрытии ([ADR-0009](../../wiki/decisions/adr-0009-sintez-znanij-pri-zakrytii-raboty.md)) и переноса `output/` в фиксированную часть ([ADR-0010](../../wiki/decisions/adr-0010-output-universal-working-root.md)). Граница base↔класс — 8 слотов S1–S8.
