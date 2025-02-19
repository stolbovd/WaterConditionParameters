#  Видение
Краткое наименование: **WaterConditionParameters**  
Полное наименование: **WaterConditionParameters – Система для определения параметров состояния воды**

## Введение
**WaterConditionParameters** – система, предназначеннная для определения параметров состояния воды, а также отображения их в мобильном приложении. 

## Возможности
Система может определять:
- температуру воды
- мутность воды
- плотность воды
- кислотность воды
- уровень воды в сосуде
- концентрацию любых растворённых в воде ионов: катионов (+) и анионов (-), минералов, солей и металлов

Отображение этих параметров происходит в мобильном приложении.

Мобильное приложение:
- отображение параметров состояния воды 
- ведение статистики параметров состояния воды за определённый период
- настраиваемое время работы системы
- настраиваемые push-уведомления (напоминания о чём-либо)
...

## Область применения
Система предназначена для мест, оснащённых источником питьевой воды.

## Компоненты
Система для определения качества воды включает в себя как аппаратную часть, так и программную. Аппаратным обеспечением системы является плата Arduino с определённым набором модулей и датчиков. Программным обеспечением системы является скетч для работы микроконтроллера, а также мобильное приложение.

## Источники входа / выхода
**Вход:**
- информация с датчиков

**Выход:**
- отображение параметров в мобильном приложении (bluetooth, wi-fi, постредством Интернет удалённо)
- отображение параметров в web-приложении (постредством Интернет удалённо)
- отображение параметров на LCD дисплее (непостредственно вблизи с аппаратной частью системы)
- уведомление по SMS (мобильная связь)

*Нужно выбрать один источник выхода. В дальнейшем, можно добавить ещё один или несколько источников выхода.

## Нерешённые вопросы и дальнейшие шаги разработки!!!
1. Актуальна ли ситема на сегодняшний день?
2. Существуют ли конкуренты? Если да, то какие отличия будут у системы?
3. Определить точное и окончательное название системы.
4. Какие ещё датчики можно дополнительно подключить?
5. Какой(-ие) источник(-и) вывода необходим(-ы)?
6. Какие функции можно добавить в мобильное приложение?
7. Разработать идеальный сценарий.
8. В каком виде должен быть прототип?
9. Можно и нужно ли подлключить какие-либо ещё датчики?
