# ENC28J60-Ethernet-controller
Разработка платы ENC28J60-Ethernet controller в **Altium Designer**

**Описание проекта**
Эта плата представляет собой контроллер на базе микроконтроллера ATMEGA168A-PU с поддержкой Ethernet-подключения через микросхему ENC28J60. Она предназначена для использования в сетевых устройствах, IoT-проектах и системах автоматизации.

---

## Основные характеристики

- **Микроконтроллер:** ATMEGA168A-PU (16 КБ Flash, 1 КБ SRAM, 512 Б EEPROM)
- **Ethernet-контроллер:** ENC28J60 (10Base-T, SPI-интерфейс)
- **Стабилизатор напряжения:** LM2937Z-3.3 (3.3 В)
- **Кварцевый резонатор:** 18 МГц
- **Трансформатор Ethernet:** WE-RJ45 LAN Transformer
- **Разъёмы:**
  - D-Sub 9-pin (COM-порт)
  - Разъём питания
- **Дополнительные компоненты:**
  - Резисторы (AXIAL-0.4)
  - Конденсаторы (различных типов)
  - Индуктор (L1)

---

## Возможности

- Подключение к локальной сети через Ethernet (10Base-T).
- Управление и обработка данных с помощью ATMEGA168A-PU.
- Стабильное питание 3.3 В для всех компонентов.
- Возможность подключения внешних устройств через COM-порт.

---

## Области применения

- **IoT-устройства** (Интернет вещей)
- **Сетевые контроллеры** для автоматизации
- **Учебные проекты** по изучению работы Ethernet и микроконтроллеров

---

## Схема подключения

Для подключения платы к сети используйте разъём RJ45. Питание подаётся через разъём питания (рекомендуемое напряжение: 5 В).

### Разработка электрической принципиальной схемы
<img width="2000" height="600" alt="image" src="https://github.com/user-attachments/assets/96476bd2-1458-488e-82c4-68bbe00b4e7c" />

### Трассировка печатной платы
<img width="1200" height="200" alt="image" src="https://github.com/user-attachments/assets/e966598a-9abe-49ea-ae1c-fc7cb210f093" />

<img width="974" height="282" alt="image" src="https://github.com/user-attachments/assets/883a9941-fb5b-4567-9a2d-72b7c978e73c" />

### Спецификация компонентов

<img width="924" height="714" alt="image" src="https://github.com/user-attachments/assets/f1257b0a-1e0c-4a91-812d-78f4ad946d58" />

### Схема монтажа платы

<img width="1239" height="344" alt="image" src="https://github.com/user-attachments/assets/982b5f34-8fc4-45e0-b476-6032ca56e19f" />

### Сторона монтажа
<img width="1234" height="323" alt="image" src="https://github.com/user-attachments/assets/47fdef99-bcd9-4a48-9267-f6d0ebf4fd95" />

### Сторона пайки

<img width="1242" height="313" alt="image" src="https://github.com/user-attachments/assets/2bdf7373-332d-4253-9d37-1f1386b32225" />

### 3D модель платы 

<img width="890" height="260" alt="image" src="https://github.com/user-attachments/assets/7ceea348-5185-4421-8527-fa7520b9a19b" />

<img width="882" height="282" alt="image" src="https://github.com/user-attachments/assets/1d97a216-a5fb-439e-9720-eb1eaf79f529" />


