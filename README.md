# env

Реализовать BASH-скрипт с передачей переменных окружения и аргументов и использованием утилит find и file (опционально использование конструкций if и for).
# Скрипт

#!/bin/bash  
again=yes #присваиваем значение "yes" переменной again  
while [ "$again" = "yes" ] #Будем выполнять цикл, пока $again будет равно "yes"  
do  
echo "Please enter a name:"  
read name  
echo "The name you entered is $name"  
  
echo "Do you wish to continue?"  
read again  
done  
echo "Bye-Bye"  

# Вывод

![image](https://user-images.githubusercontent.com/71909269/163090147-b4dbac66-8427-4c1c-a956-dfd7a08b09f0.png)
