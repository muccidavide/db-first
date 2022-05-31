
## CAR DEALER DB SCHEME

## MOdels: Car

## Table Cars

- id:                   Bigint                  PRIMARYKEY(NOTNULL,AUTOINCREMENTS, UNIQUE)
- model:                VARCHAR(100)            NOTNULL INDEX
- brand:                VARCHAR(50)             NOTNULL INDEX
- price:                DECIMAL(5,2)            NOTNULL
- year:                 YEAR                    NULL
- km:                   MEDIUMINT               NULL
- power_supply:         VARCHAR(50)             NULL
- image: V              VARCHAR(255)             NULL
- available:            TINYINT                 NULL DEFAULT(1)
- color:                VARCHAR(50)             NOTNULL
- doors:                TINYINT                 NULL 	
- seats                 TINYINT                 NULL
- displacement: S       MALLINT                 NULL
- origin_country:       VARCHAR(56)             NULL
- plate: V              ARCHAR(20)              NULL
- bluetooth:            TINYINT                 NULL DEFAULT(0)
- navigation_system:    TINYINT                 NULL DEFAULT(0)
- decription:           TEXT                    NULL
- note:                 TEXT                    NULL




