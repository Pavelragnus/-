**1. В процессе создания демонстрационной базы данных применялись такие библиотики python3, как:**
- sqlite3
- pandas
- re   

**2. В примере представлены данные о мутациях, относящихся только к 4 хромосоме**

**3. Исходная таблица данных для создания базы получена путем предшествующего анализа открытых для доступа plink таблиц c AMP-PD database. Предшесвтующий анализ включал:**
- аннотирование генома с помощью VEP annotation Docker Image
- сортировку полученных данных из файла c расширением vcf в отдельные таблицы формата csv для каждого пациента
- затем создание единой таблицы csv со всеми пациентами и их аннотациями, содержащими только редкие мутации по данным gnomAD Allele Frequency

**Описанные шаги целесообразны для решения других задач в рамках более крупного проекта по поиску редких патогенных дигенных варантов у пациентов с болезнью Паркинсона**.