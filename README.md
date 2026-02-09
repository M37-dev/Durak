# 🃏 Durak Console Game (C++) / Карточная игра «Дурак»

## 🌐 Language / Язык
**[English]** A robust console-based implementation of the traditional Russian card game "Durak".  
**[Русский]** Надежная консольная реализация традиционной русской карточной игры «Дурак».

## ✨ Features / Основные возможности

| Feature / Возможность | Description (EN) | Описание (RU) |
| :--- | :--- | :--- |
| **Deck Lifecycle** | Full 52-card deck with `std::shuffle`. | Колода из 52 карт с использованием `std::shuffle`. |
| **Trump Mechanic** | Random trump suit placed at the bottom. | Случайный козырь, помещаемый в низ колоды. |
| **Auto-Refill** | Players draw up to 6 cards after each round. | Авто-добор до 6 карт после каждого раунда. |
| **Game AI** | Smart-ish bot with attack/defense logic. | Бот с логикой атаки и защиты. |
| **Win Conditions** | Plays until the last card is gone. | Игра до последней карты в руках. |

## ⚠️ Limitations / Текущие ограничения

### 🇺🇸 English
- **Classic Mode Only:** Currently supports single-card turns (no "throwing in" multiple cards).
- **Basic AI:** Bot uses the first valid card without complex strategy.
- **CLI:** Interaction is limited to terminal input/output.

### 🇷🇺 Русский
- **Только классика:** За ход выкладывается одна карта (без подкидывания).
- **Простой ИИ:** Бот защищается первой подходящей картой без тактики.
- **Интерфейс:** Только текстовый ввод/вывод в терминале.

## 🛠 Tech Stack / Технологии
- **Language:** C++11 or higher
- **STL Components:** `std::vector`, `std::algorithm`, `std::random`, `std::string`

## ⚙️ How to Run / Как запустить

### Compile / Компиляция
```bash
g++ main.cpp -o durak


### Run / Запуск

```bash
./durak
```

## 📸 Preview / Предпросмотр

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/0d9bc0cc-0f1c-4936-8ad3-e07d5b13d4fa" />


---

### 🔍 Объяснение символов (чтобы ты понимал логику):

1.  **`#` и `##`**: Это заголовки. Один `#` — самый крупный (название проекта), два `##` — заголовки разделов. GitHub автоматически делает под ними черту.
2.  **`|` (Вертикальная черта)**: Используется для рисования таблиц.
3.  **`:---`**: Указывает выравнивание текста в таблице (по левому краю).
4.  **`-` (Тире)**: Создает маркированный список (точки).
5.  **`**Текст**`**: Делает текст **жирным**.
6.  **`` `Текст` ``**: Выделяет текст как код внутри строки (серый фон).
7.  **```bash ... ```**: Создает большой блок кода с подсветкой синтаксиса (в данном случае для команд терминала).
8.  **`>`**: Создает цитату (вертикальная серая линия слева от текста).


© 2024 M37-dev
