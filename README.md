# classification_banking_blocks
Классификация входящих заявок на открытие расчетно-кассового обслуживания (РКО) на 2 класса: есть/нет блокировки в следующие 180 дней после открытия счета

## Постановка задачи:
Необходимо разработать модель, которая будет классифицировать поступающие заявки на два класса:
•	Заявка от организации, счет которой не будет заблокирован в течение 6 месяцев после открытия.
•	Заявка от организации, счет которой будет заблокирован в течение 6 месяцев после открытия.

## Условия
### Заявки
В Банк поступают заявки от индивидуальных предпринимателей и юридических лиц на открытие расчетно-кассового обслуживания (РКО). Список всех поступивших заявок в период 2018-06-18 – 2019-12-14 находится в файле Заявки.xlsx
### Открытие счета
Банк рассматривает все заявки и принимает одно из двух решений – открыть счет или отказать
### Блокировки
Банк рассматривает все заявки и принимает одно из двух решений – открыть счет или отказать
### Наличие_кредитного_продукта
список ИНН у организаций из заявок, у которых на данный момент открыт кредитный продукт в Банке
### Spark данные 
Сведения из СПАРК по всем организациям из заявок РКО. Переменные получены из исторических отчетов (логов) на момент поступления заявки 

