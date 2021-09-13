# Отчёт о тестировании Money Transfer

## Тестирование части JAVA кода 

12.09.2021 12:07 - 12.09.2021 12:40 было проведено в приложении IntelliJ IDEA.

На тестирование затрачено: 33 минуты

В результате тестирования выявлены следующие дефекты:
* [Некорректное отображение значения переменной int total в java коде #1](https://github.com/AzNavyr/Money-Transfer/issues/1#issue-994684032)


В качестве тестовых данных использовались данные файла Test-data.txt:
* Часть JAVA кода :
```
public class HW1 {
    public static void main(String[] args) {
        int price = 2_000_000_000;
        int count = 500_000_000;
        int total = price + count;
        System.out.println(total);
    }
}
```


Тестирование производилось в следующем окружении:
* PC, Windows 7 64-bit
* Java v.11
* IntelliJ IDEA v2021.2.1