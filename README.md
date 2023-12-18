### ESERCIZIO

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

### MODELLO TABELLA

1. id:                 INT UNSIGNED - PRIMARY KEY
2. offer_number:       VARCHAR(8) - NOTNULL
3. brand:              VARCHAR(255) - NOTNULL
4. model:              VARCHAR(255) - NOTNULL
5. model_code:         VARCHAR(10) - NOTNULL
6. first_registration: YEAR - NOTNULL
7. kilometers:         MEDIUMINT - UNSIGNED - NOTNULL
8. color:              VARCHAR(255) - NOTNULL
9. purchase_price:     DECIMAL(9, 2) - UNSIGNED - NOTNULL
10. sale_price:        DECIMAL(9, 2) - UNSIGNED - NOTNULL
11. fuel_type:         VARCHAR(255) - NOTNULL
12. power_kw:          TINYINT - UNSIGNED - NOTNULL
13. engine_size:       SMALLINT - UNSIGNED - NOTNULL
14. gearbox:           VARCHAR(255) - NOTNULL
15. seats:             TINYINT - UNSIGNED - NOTNULL
16. doors:             TINYINT - UNSIGNED - NOTNULL
17. drivetrain:        VARCHAR(255) - NULL
18. warranty_mounth:   TINYINT - UNSIGNED - NOTNULL
19. last_service:      DATE - NULL
20. body_type:         VARCHAR(255) - NULL
21. emission_class:    VARCHAR(255) - NOTNULL

### ESEMPIO TABELLA

|id|offer_number|brand|model|model_code|first_registration|kilometers|color|purchase_price|sale_price|fuel_type|power_kw|engine_size|gearbox|seats|doors|drivetrain|warranty_mounth|last_service|body_type|emission_class|
|--|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|1|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|2|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|3|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|4|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|5|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|6|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|
|7|------------|-----|-----|----------|------------------|----------|-----|--------------|----------|---------|--------|-----------|-------|-----|-----|----------|---------------|------------|---------|--------------|




