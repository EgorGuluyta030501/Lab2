# Требования к проекту
### Содержание
1. [Введение](#1) <br>
  1.1. [Назначение](#1.1) <br>
  1.2. [Бизнес-требования](#1.2) <br>
      1.2.1. [Границы проекта](#1.2.1) <br>
  1.3 [Аналоги](#1.3) <br>
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователя](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
  2.4. [Предположения и зависимости](#2.4) <br>
3. [Системные требования](#3.) <br>
  3.1. [Функциональные требования](#3.1) <br>
  3.2. [Нефункциональные требования](#3.2) <br>
     3.2.1. [Атрибуты качества](#3.2.1) <br>
     3.2.2. [Внешний интерфейс](#3.2.2) <br>

### Автоматизации финансового учета
* Cоздать эффективную систему обработки информации и управления финансами компании
  
### 1. Введение <a name="1"></a>
#### 1.1 Назначение <a name="1.1"></a>
Автоматизация финансового учета - основа эффективного управления предприятием. Для грамотного внедрения программного обеспечения и его дальнейшего использования необходимо выбрать оптимальный вариант автоматизации. При этом следует сравнить несколько программ по различным критериям, а также разработать план перехода на автоматизированный учет.

Для того чтобы устранить данные недостатки и улучшить жизнь пользователей я и создал данный проект - GEFINANC.
#### 1.2 Бизнес-требования <a name="1.2"></a>
##### 1.2.1. Границы проекта <a name="1.2.1"></a>
-Cбор и объединение информации в одной программе, что позволяет создавать единую базу данных, обработка которых даст достоверные результаты;
-Уменьшение трудовых и временных затрат на обработку информации, вследствие чего возможно снижение объема необходимых ресурсов
#### 1.3 Аналоги <a name="1.3"></a>
Данный проект является в каком-то роде упрощенным вариантом ["Uchetkin.by"](https://www.uchetkin.by/?utm_source=yandex&utm_medium=cpc&utm_campaign=master_kampaniy&utm_content=uchet_raskhodov_i_dokhodov&_openstat=ZGlyZWN0LnlhbmRleC5ydTs3NTQ1OTYxNDsxMjU4MTI0NzA1MDt5YW5kZXguYnk6cHJlbWl1bQ&yclid=13814816733431332863) который значительно упрощает использование.
### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>
Проект создан с помощью Android SDK и языка программирования Kotlin.
#### 2.2. Интерфейс пользователя <a name="2.2"></a>
Графический интерфейс проекта представлен с помощью мокапов [главного окна] и [способа регулирования громкости и цветовой палитры].
Отдельного рассмотрения требует главное окно:

Клавиша | Реакция
--- | ---
"Brightness" | Выплывает полоса прокрутки, при помощи которой можно настроить яркость
"Start" | Начало программы 
"Cost calculations " | подсчеты расходов
"Color" | Открываются варианты цветовой палитры
"Add" | Добавление расходов и доходов
"Remove" | Удаление выбранных расходов или доходов

#### 2.3. Характеристики пользователей <a name="2.3"></a>
Целевая аудиория:
* Все пользователи выше дошкольного возраста, финансовые работники и предприятия.
#### 2.4. Предположения и зависимости <a name="2.4"></a>
Приложение запускается за счёт внутренних ресурсов Android,Windows,Linux,Mac OC.
### 3. Системные требования <a name="3"></a>
Запуск и работа приложения на следующих операционных системах:
* Android 1.6 и выше,Windows 7 и выше и тд
#### 3.1. Функциональные требования <a name="3.1"></a>
Пользователю предоставлены возможности, представленные в таблице.

Функция | Требования
--- | ---
Возможность внедрения бюджетирования и планирования, что облегчает и упрощает принятие решений по управлению бизнесом| Приложение должно предоставить пользователю возможность добавить выбранные расходы и доходы, при нажатии на клавишу "Add"
Удаление | Приложение должно предоставить возможность удалить выбранные расходы или доходы, при нажатии на клавишу "Remove"
Изменение яркости | Приложение должно предоставить возможность изменения яркости  при помощи полосы прокрутки, которая вызывается нажатием на клавишу "Brightness"
Подсчет расходов | Приложение должно предоставить возможность подсчета расходов, при нажатии на клавишу "Cost calculations "
Изменение цветовой палитры | Приложение должно предоставить варианты цветовой палитры, при нажатии на клавишу "Color"
Начало программы | Приложение должно предоставить возможность начала работы с расходами и доходами нажатиям клавиши "Start" 

#### 3.2. Нефункциональные требования <a name="3.2"></a>
  ##### 3.2.1. Атрибуты качества <a name="3.2.1"></a>
Важными атрибутами качества данного приложения являются: быстрый запуск, малое потребление ресурсов и высокая производительность, а именно быстрый подсчет. <br/>
Также атрибутами качества являются : легкость использования засчет прияттного минималистичного интерфейса, быстрая скорость реагирования на изменение состояния кнопки, низкого энергопотребления приложения
  ##### 3.2.2 Внешний интерфейс <a name="3.2.2"></a>
Приложение должно быть разработано в одном стиле с добавлением разных шрифтов и цветовой палитры# Требования к проекту


