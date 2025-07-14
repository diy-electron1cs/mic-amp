[![Foo](https://img.shields.io/badge/ПОДПИСАТЬСЯ-НА%20ТГК%20DIY%20ELECTRONICS-brightgreen.svg?style=social&logo=telegram&color=blue)](https://t.me/diy_electron1cs)

# преамп для электретного микрофона

преамп на базе микросхемы NE5532 (за основу взят [проект](https://www.hi-dev.ru/projects/hi-dev-micro) с канала "Hi DEV!")

![готовый преамп](https://github.com/diy-electron1cs/mic-amp/blob/main/images/mic-amp-v-korpuse.jpg?raw=true)

## компоненты
- NE5532 в SMD корпусе - 1x
- SMD неполярный конденсатор 4.7 мкф - 2x
- SMD неполярный конденсатор 47 пкф - 1x
- SMD неполярный конденсатор 1 мкф - 1x
- SMD неполярный конденсатор 10 мкф - 1x
- SMD резистор 100 кОм - 1x
- SMD резистор 68 кОм - 2x
- SMD резистор 4.7 кОм - 1x

### плата
[Плата](https://github.com/diy-electron1cs/mic-amp/tree/main/pcb) односторонняя.
[Статья про ЛУТ](https://diy-electron1cs.github.io/DIY-electronics/article-lut)
### корпус
Модели в форматах .stp и .m3d (для старых версий КОМПАС-3D) есть в директории 3dprint.
Корпус состоит из основной части и нижней крышки.
### питание
Схема питается от 9 вольтовой батарейки типа "крона".
Минус идёт на нижний контакт на плате (см. картинку ниже), плюс через выключатель – на верхний.
![pcb](https://github.com/diy-electron1cs/mic-amp/blob/main/images/pcb.png?raw=true)

### вход и выход преампа
Вход (напрямую подключается к электретному микрофону) слева платы, выход на среднем контакте справа [(см. рисунок)](https://github.com/diy-electron1cs/mic-amp/blob/main/images/pcb.png?raw=true).

## обратная связь
По вопросам писать в [чат DIY electronics](https://t.me/diy_electronics_chat) или на [почту](mailto:diy-electronics@mail.ru).
