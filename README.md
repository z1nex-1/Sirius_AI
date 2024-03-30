# **Сириус ИИ** Весна 2024

<p float="left">
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/logo1.png" width="300" />
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/logo2.png" width="150" />
</p>

## Инструмент для анализа клиентских отзывов

### Проектная команда:

- Кончаков Павел
- Григорьев Илья
- Ведешкин Тимофей
- Шабаев Андрей

________

# 1 Этап

Для первого этапа мы решили использовать модель **zephyr beta 7B Q4_K_S**

Мы запускаем ее в **LM Studio**, а потом уже в программе на языке программирования **python** обращаемся к серверу.

## Демонстрация работы

<p float="left">
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/im4.png" width="500" />
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/img5.png" width="500" />
</p>

## Результат

<p float="left">
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/img6.png" width="500" />
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/img7.png" width="500" />
</p>

## Видеодемострация работы для первого этапа

<p float="left">
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/qr.png" width="300" />
</p>

________________________________

# 2 Этап
### Вот второй этап опишем подробно
## План реализации 
1. Сбор информации
2. Чистим от лишнего и структурируем собранные данные для последующего анализа
3. Извлечение признаков

## Сбор информации
### Для сбора информации мы использовали 2 вида парсерова с 2 источников

Colons can be used to align columns.

|   Сайт           | banki.ru            | sravni.ru                            |
| -------------    |:-------------:      | :-----:                               |
| Что использовали?| **bs4** и **urlib** | **selenium** и **webdriver_manager** |
| Как работает?    | Просто через **get** запросы     | Ходим по сайт через **ChromeDriver** и нажимем на кнопки |

<p float="left">
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/img8.png" width="450" />
  <img src="https://github.com/z1nex-1/Sirius_AI/blob/main/img/img9.png" width="550" />
</p>
