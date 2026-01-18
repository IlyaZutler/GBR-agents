# GBR-agents
Agents motel in time
Agent-Based Model Over Time

Agents are located on a fixed segment of a line. Each Agent has a Home Location (Dislocation) — a fixed point on the segment (a coordinate). The home locations are evenly spaced along the segment. Agents can move along the segment at given speeds. Each Agent can be in one of two states: Free or Busy.

An object called an Alarm may appear on the segment. Each Alarm has a coordinate on the segment and a time-related characteristic called Complexity. The nearest free Agent is dispatched to the Alarm. The Agent travels to the Alarm and then spends an amount of time at the Alarm equal to its Complexity. From the moment the Agent is dispatched and throughout the entire time spent at the Alarm, the Agent is in the Busy state. After completing the service, the Agent becomes Free again, the Alarm disappears, and the Agent returns to its Home Location. The Agent remains at its Home Location until the next dispatch to an Alarm.

Alarms occur randomly:
uniformly along the segment,
with a given intensity,
with lognormally distributed Complexity.
An Alarm disappears after the Agent arrives and spends time at the Alarm equal to its Complexity.
The system must be simulated while collecting the following metrics:
total number of Alarms,
average arrival time to an Alarm,
fraction of Alarms for which the arrival time exceeded a given threshold,
fraction of time an Agent spends in the Busy state.
Time-based visualization:
The segment is displayed with Agents shown as light-blue circles.
A newly appearing Alarm is shown as a red circle.
A dispatched Agent turns blue and moves toward the Alarm.
Upon arrival, the Agent and the Alarm merge and are shown as a purple circle.
The Alarm disappears.
The Agent returns to its Home Location and is shown again as a light-blue circle.





Модель Агентов во времени.

Агенты находятся на заданном отрезке прямой.
У каждого Агента есть Дислокаций - закрепленная для него точка на отрезке (координата).
Дислокации на равном расстоянии на отрезке.
Агенты могут двигаться по отрезку с заданными скоростями.
Агенты можгут находиться в двух состояниях - Свободен или Занят.

На отрезке может возникнуть объект Тревога.
У Тревоги есть координата на отрезке.
У Тревоги есть временная характеристика - Сложность.
На Тревогу выезжает блиижайший свободный Агент.
Агент приезжает на Тревогу и проводит на ней время, равное Сложности.
С момента выезда на Тревогу и все время на Тревоге Агент в состоянии Занят.
После этого Агент переходит в состояние Свободен.
Тревога исчезает.
Агент возвращается к месту Дислокации.
Агент остается в месте Дислокации до следуюзего выезда на тревогу.

Тревоги возникают случайно:
- равномерно на отрезке,
- с заданной интенсивностью,
- с логнормальной Сложностью.
Тревога исчезает после прибытия Агента и нахождения на Тревога время равное Сложности.
Необходимо моделировать систему, собирая следующие данные:
Количество Тревог.
Среднее время прибытия на Тревогу.
Доля Тревог, на которые прибыли за время, более Порога.
Доля времени Агента в состоянии Занят.

Визуализация во времени:
Отрезок, на котором Агнты отмечены Голубыми кружками.
Появившаяся Тревога отмечается Красным кружком.
Выехавший Агент становится Синим и перемещается к Тревоге.
По прибытии Агента к Тревоге, Агент и Тревога сливаются и становятся Фиолетовым кружком.
Тревога исчезает.
Агент возвращается к дислокации в виде кружка Голубого цвета.
