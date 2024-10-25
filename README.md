# Hardware Encryption on Arduino

Данный репозиторий будет отражать моё продвижение в изучении и воплощении аппаратного шифрования посредством микроконтроллера. 

## Источники , применённые для изучения "прадивой" генерации случайных чисел и её реализации на Arduino:

[Two Fast Methods of Generating True Random Numbers on the Arduino]https://gist.github.com/bloc97/b55f684d17edd8f50df8e918cbc00f94

Данная статья подробно описывает развитие True Random Number Generation (далее TRNG, RNG), концепцию его работы на конкретных примерах и два относительно лёгких метода её воссоздания.

[Arduino Random Password Generator]https://github.com/Kidel/Arduino-Random-Password-Generator

Данный репозиторий показывает пример того продукта, который я собираюсь воссоздать.

[Arduino hardware true random number generator]https://gist.github.com/endolith/2568571

Здесь так же представлен пример похожей, по моей тематике, работы по воссозданию TRNG на Arduino, но уже описывая кодовую его составляющую.

## Аппаратная составляющая

Данная часть проекта пока осталась не тронутой, в плане определения конкретной модели Arduino. В вышеописанных примерах использовались [Arduino Pro Micro]https://www.sparkfun.com/tutorials/337 ввиду возможности её использования как клавиатуры, а также [Arduino Mega2560]https://docs.arduino.cc/hardware/mega-2560
