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

! [скриншот] (https://github.com/MashaOsipova/Java-1.2.2/blob/74ea5517f353dcde4a882288597b5d9359ff304a/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0.png)

**Окружение**

- Windows 10
- Java version "11.0.9.1"
- IntelliJ IDEA Community Edition 2020.3.1
