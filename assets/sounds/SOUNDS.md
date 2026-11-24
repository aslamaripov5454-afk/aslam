# Звуки интерфейса (assets/sounds)

Все звуки — **CC0 1.0 (общественное достояние)**, скачаны с [kenney.nl](https://kenney.nl):
- [Interface Sounds](https://kenney.nl/assets/interface-sounds) — 100 звуков, CC0
- [Casino Audio](https://kenney.nl/assets/casino-audio) — 150 звуков, CC0

Атрибуция не требуется, но автор — Kenney (https://kenney.nl).

## Файлы, которые использует `aslam.ahk`

| Файл | Назначение в скрипте | Источник |
|------|----------------------|----------|
| `ok.wav` | `AslamSound("ok")` — успех/подтверждение | confirmation_001 |
| `warn.wav` | `AslamSound("warn")` — предупреждение | error_004 |
| `alarm.wav` | `AslamSound("alarm")` — тревога | error_006 |
| `bell.wav` | `AslamSound("bell")` — уведомление/звонок | bong_001 |
| `dice.wav` | `AslamSound("dice")` — бросок кубика | dice-shake-2 (Casino Audio) |
| `startup.wav` | `AslamSound("startup")` — запасной звук заставки | confirmation_003 |

## Дополнительные (частые UI-звуки)

| Файл | Назначение | Источник |
|------|-----------|----------|
| `click.wav` | клик по кнопке | click_001 |
| `toggle.wav` | переключатель | toggle_001 |
| `open.wav` | открытие панели/окна | open_001 |
| `close.wav` | закрытие | close_001 |
| `select.wav` | выбор пункта | select_001 |
| `scroll.wav` | прокрутка | scroll_001 |

## Формат

WAV, PCM 16 бит, моно, 44 100 Гц — воспроизводится через `SoundPlay()` (AutoHotkey v2) без сторонних кодеков.
