# Лабораторная работа 4

Для решения понадобится установить VirtualBox. Он ставится только на машины с гипервизором. В случае, если на вашем устройстве нет гипервизора, обратитесь к другу или преподавателю.

В данной работе будет необходимо работать с сетями, для проверки связи между двумя устройствами потребуется утилита ping. Попробуйте запустить в терминале на существующей виртуальной машине
```
ping yandex.ru
```
По результату определите, есть ли доступ. Попробуйте отправить ping туда, куда доступа точно нет. Какой будет результат?  

Задание:

1. Поднять виртуальную машину с Ubuntu в VirtualBox. (допустим другой linux дистрибутив)  
   
2. Сделать так, чтобы из неё был доступ в Интернет. Приложить скриншот из терминала. (Подсказка: при доступе в Интернет пингуются сайты).  
3. Поднять ещё одну виртуальную машину.  
4. Сделать так, чтобы был доступ из машины А в машину Б. Приложить скриншот из терминала. 
Для выполнения этого пункта вам потребуется узнать ip адрес вашей виртуальной машины и отправить ping напрямую по ip (ведь домена, аналогично yandex.ru, у неё нет). 
1. Поднять ещё одну виртуальную машину.  
2. Настроить сеть так, чтобы был доступ из машины А в машину Б, из машины А в машину В, но не было доступа из машины Б в машину В. Приложить скриншот, на котором видно терминалы всех трёх машин. Для решения последнего пункта рекомендуется изучить больше о типах подключения в VirtualBox.   
