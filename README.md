# OctoPrint-Octokeys
Плагин клавиатуры для приручения осьминога

Этот плагин является ответвлением идеи плагина: https://github.com/pkElectronics/OctoPrint-Octoremote
Также существует вариант с отдельным блоком кнопок https://github.com/eta4ever/OctoPrint-Octoremote

Аппаратная реализация плагина сделана на ардуино и полностью совместима с названными проектами.
Пульт представляет собой восемь тактовых кнопок смонтированных на макетной плате. Опрос кнопок и связь с осьминогом выполняет ардуино.
Корпус пульта выполнен в виде удиной конструкции с кожухом дисплея, для оптимизации крепления и эргономичности.

![Корпус](https://github.com/hallskelet/OctoPrint-Octokeys/blob/master/doku/instaled.jpg?raw=true)

Верхние 2 кномки имеют фиксированные команды: 1я - Старт последней печати/пауза/продолжение печати, в зависимости от текущего стостояния принтера. 2я - остановка печати.
Далее кнопки программируемые. На них можно натроить выполнение команды Г кода или скрипта из этих команд.

Основным отличием от аналогов является возможность назначить на кнопку изменение пина GPIO ежевики по нажатик кнопки. Этот режим можно применять напримен для управления подсветкой или включением принтера с места. Поскольку в том случае если оператор находится возле принтера ему крайне затруднительно управлять принтером через вебинтерфеес.

Расположение кнопок на клавиатуре:

| Старт/Пауза | Стоп |
|:----:|:----------:|
| Настраиваемая 1 | Настраиваемая 2 |
| Настраиваемая 1 | Настраиваемая 2 |
| Настраиваемая 3 | Настраиваемая 4 |
| Настраиваемая 5 | Настраиваемая 6 |

В папках Board и case есть документация для изготовления платы и курпуса.

Вот так это получилось у меня:

![Напечатанное](https://raw.githubusercontent.com/hallskelet/OctoPrint-Octokeys/master/doku/printed.jpg)

![Сборка](https://raw.githubusercontent.com/hallskelet/OctoPrint-Octokeys/master/doku/assembly.jpg)
