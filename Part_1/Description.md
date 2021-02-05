## Part 1 ‐ Exploratory data analysis
The attached archive contains financial and qualitative data for a number of companies. It also has 'flags.csv' table with event description - we count an event as a default ONLY if it mentions bankruptcy. Perform cleaning, determine default flags and explore the data, try to find some underlying patterns.
Visualize the results and briefly comment your insights.

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
#### Flags data
* **id**: ID компании
* **flag**: Описание события в свободной форме
