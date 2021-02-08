## Part 1 ‐ Exploratory data analysis
An attached archive contains financial and qualitative data for a number of companies. It also has 'flags.csv' table with default dates. Perform cleaning and explore the data, try to find some underlying patterns.
Visualize the results and briefly comment on your insights.

## Data description
#### Qualitative data
* **id**: ID компании   
* **activities**:   Основной, дополнительный виды деятельности 
* **regInfo**:  Сведения о регистрации (Дата присвоения ОГРН; Наименование органа, зарегистрировавшего юрлицо до 1 июля 2002 года)
* **regBody**:  Сведения о постановке на учет в налоговом органе
* **statedCapital**: Уставный капитал 
#### Financial data
* **id**: ID компании 
* **buhForms**: Бухгалтерские формы
    * **year**: Год отчетности
    * **organizationType**: Размер организации
    * **form1**: Форма 1 бухгалтерской отчетности (form2 аналогично)
        * **code**: РСБУ-код
        * **name**: Расшифровка РСБУ-кода
        * **startValue**: Значение на начало года
        * **endValue**: Значение на конец года
#### Flags data
* **id**: ID компании
* **default_date**: Дата дефолта (решение суда о признании компании банкротом)
