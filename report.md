# Отчёт о тестировании валидации номера банковской карты в IntelliJ IDEA.
## Краткое описпние
20.11.2020 было проведено тестирование установки IntelliJ IDEA и Unit test функциональности валидации номера банкоской карты.

На тестирование затрачено: 1 час.

В результате тестирования выявлен следующий дефект:
* [Bur report 1](https://github.com/SergeyQA13/Start-Java-1.1-2/issues/1#issue-746850944)

## Описание процесса тестирования
### В процессе тестирования использовались следующие артефакты:
* [Тестове данные для IntelliJ IDEA в п. "Шаг 20"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) 
* [Тестове данне по номерам карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

### В качестве тестовых данных использовались данные из артефактов:

Данне для тестирования IntelliJ IDEA:

Код: 

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello programming!");
  }
}

Ответ:

Hello programming!

Данне для тестирования функциональности валидации номера банкоской карты:

Валидне данные:

* VISA
4532784299679447
4532786530565533
* MasterCard:
2720998524010980
5369232964867264
* American Express (AMEX):
375052065880948

Не валидне данные:
* VISA
4556206245345178172

### Тестирование производилось в следующем окружении:
* IntelliJ IDEA
* 64-разрядная ОС Windows
