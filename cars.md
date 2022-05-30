Macchine: 

- id: INT NOTNULL AUTO_INCEMENT UNIQUE
- model_name: VARCHAR(20) NOTNULL
- car_manufacturer: VARCHAR(35) NOTNULL
- price: FLOAT(9,2)  NULL
- model_release_year: SMALLINT NULL
- model_version: VARCHAR(20) NULL
- model_version_release_year: SMALLINT NULL
- optionals: TINYTEXT NULL
- descriptions: TEXT NOTNULL