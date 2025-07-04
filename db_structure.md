# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## used_cars

- id | PRIMARY_KEY UNIQUE NOT_NULL
- brand | VARCHAR(50) INDEX NOT_NULL
- model | VARCHAR(50) INDEX NOT_NULL
- registration_date | DATE NOT_NULL
- selling_price | DECIMAL NOT_NULL INDEX
- km_done | MEDIUMINIT NOT_NULL
- ~~ market_price ? ~~
- license_plate | VARCHAR(7) NOT_NULL
- auto_check | TINYINT NOT_NULL
- type | VARCHAR(15) NULL
- feed | VARCHAR(25) NULL
- horse_power | SMALLINT NULL
- displacement | FLOAT(4,2) NULL
- note | TEXT NULL 