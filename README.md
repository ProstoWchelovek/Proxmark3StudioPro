# Proxmark3 Studio Pro

<div align="center">
  <img src="resources/icons/app_icon.png" width="128" alt="Logo">
  <h3>Professional GUI for Proxmark3</h3>
  <p>Мощный графический интерфейс для работы с RFID/NFC устройством Proxmark3</p>
</div>

## ✨ Возможности

### 🔽 Низкие частоты (125 kHz / 134 kHz)
- Автоматическое определение и чтение всех типов LF меток
- Поддержка EM4100, HID, Indala, AWID, Viking, FDX-B, Hitag, T55xx и др.
- Клонирование на T55x7 с настройкой конфигурации
- Эмуляция LF меток
- Перехват LF сигналов

### 🔼 Высокие частоты (13.56 MHz)
- Полная поддержка Mifare Classic (1K/4K)
- Mifare Ultralight / NTAG
- Mifare DESFire (EV1/EV2/EV3)
- iClass, ISO15693, ISO14443-4, LEGIC, FeliCa

### ⚔️ Атаки
- Nested Attack
- Hardnested Attack
- Darkside Attack
- Sniff Attack
- Словарная атака
- LF Bruteforce

### 📊 Анализ
- Визуализация сигналов
- FFT анализ
- Демодуляция
- Анализ трассировки
- Экспорт в Wireshark

### 🔑 Управление ключами
- База ключей (SQLite)
- Импорт/экспорт словарей
- Анализ ключей
- Генератор ключей

### 📜 Скрипты
- Поддержка Lua скриптов
- Редактор с подсветкой
- Выполнение скриптов
- Библиотека скриптов

## 📦 Установка

```bash
# Клонирование репозитория
git clone https://github.com/yourname/proxmark3-studio-pro.git
cd proxmark3-studio-pro

# Установка зависимостей
pip install -r requirements.txt

# Запуск
python main.py