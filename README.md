<h1>Задача по обработке данных из таблицы в формате Excel</h1>
<h2>Описание</h2>
<p>Период наблюдения - 5 месяцев.<br>Представленные данные:</p>

<h3>Таблица Сотрудники:</h3>
1)	Период - формат Дата (пропуски не допускаются)<br>
2)	ID должности - целое число (пропуски не допускаются, уникальный на каждый период)<br>
3)	Табельный номер - целое число (допускаются пропуски)<br>
4)	Город - Текст (допускаются пропуски)<br>
5)	Должность - Текст (допускаются пропуски)<br>
6)	ФИО - Текст (допускаются пропуски)

<h3>Таблица Города:</h3>
1)	Федеральный округ - Текст (пропуски не допускаются)<br>
2)	Регион - Текст (пропуски не допускаются)<br>
3)	Город - Текст (уникальный)

<h3>Задачи:</h3>
1. Предобработка таблицы:<br>
1.1. Исправить ошибки данных (некорректный для поля тип данных, дубликат и пр.)<br>
1.2. Часть данных по некоторым должностям была утеряна, но известно, что ID имеет уникальную должность и локацию, и не меняется из периода в период, восстановить недостающие данные<br>
1.3. Вытянуть строки с новыми штатными единицами, на которые еще не распределены должности и сотрудники. В графах Табельного номера и Должности проставить признак «Резерв»;<br>
2. Построить сводную таблицу с разбивкой по месяцам со следующими показателями:<br>
2.1. Количество действующих сотрудников (должностей);<br>
2.2. Количество свободных должностей (подсказка: табельный номер пустой);<br>
2.3. Доля свободных должностей от итого должностей;<br>
3. Работа по дополнению предобработанной таблицы, добавить следующие показатели:<br>
3.1. Федеральные округа и Регионы;<br>
3.2. Количество месяцев поиска сотрудника по должности накопительно по каждому месяцу (н-р должность "директор" не заполнена в январе до марта включительно, а в апреле заполнена, результат получится следующим: январь - 1, февраль - 2, март - 3).<br>
4. Ответить на следующие вопросы, построив сводные таблицы исходя из дополненных данных пункта 3;<br>
4.1. В каких городах наблюдается нехватка кадров на последний месяц? Отсортировать по убыванию;<br>
4.2. В каком регионе работает наибольшее количество сотрудников на последний месяц? Отсортировать по убыванию;<br>
4.3. Какие должности подвержены наибольшей текучести? Вывести наименование должности и коэффициенты текучести по месяцам, отразить первыми те должности, по которым наблюдалась наибольшая текучесть.<br>
5. Визуализация;<br>
5.1. Количество действующих сотрудников по Федеральным округам;<br>
5.2. Количество свободных должностей по регионам.
