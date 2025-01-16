# ELT_Redfin_data_with_AWS_EMR

ELT проект в якому за допомогою Amazon EMR (Elastic MapReduce), Amazon EMR studio та Jupyterlab завантажуємо датасет з даними рижку житла з https://www.redfin.com/news/data-center/ до S3 bucket для подальшої обробки. 

Обробка полягає в очищенні даних від NULL значень, вилученні непотрібних колонок та додаванні нових колонок на основі існуючих в таблиці даних.

Очищенний та підготвлений файл зберігається в S3 bucket для подальшого аналізу.

