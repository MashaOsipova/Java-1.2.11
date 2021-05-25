**Материалы для тестирования**

- [Домашнее задание](https://github.com/netology-code/javaqa-homeworks/blob/master/programming/README.md)

**Шаги для воспроизведения**

1. Открыть IDEA
2. Завести новый проект
3. Создать ClassMain
4. Переменная
<pre><code> public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
} </code></pre>
5. Команда для вывода результата System.out.printLn
6. Запустить метод Ctrl+Shift+F10

**Результат**

Ожидаемый:

0.9

Фактический:

0.8999999999999999

**Cкриншот ошибки**
! [скриншот] (C:\Users\Lenovo\Desktop\Issue1.2.2)

**Окружение**

- Windows 10
- Java version "11.0.9.1"
- IntelliJ IDEA Community Edition 2020.3.1