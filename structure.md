# Database Car dealership:
## (table)Cars:

- id               PRIMARY KEY UNIQUE AUTOINCREMENT NOTNULL INDEX             
- Manufacturer (Make)            VARCHAR(30) NOTNULL INDEX
- Model                          VARCHAR(40) NOTNULL INDEX                 
- Manufacturing Year             YEAR NOTNULL
- Milleage (KM)                  MEDIUMINT NOTNULL
- Description                    TEXT NULL
- photo                          VARCHAR(250) NULL
- Price                          DECIMAL (6,2) NULL
- Seats                          TINYINT NULL
- Doors                          TINYINT NULL
- Environmental impact           VARCHAR(40) NOTNULL
- Mass(KG)                       INT NULL NULL
- Airbag                         VARCHAR(3) NULL DEFAULT
- fuel type                      VARCHAR(30) NOTNULL
- Fuel consumption               VARCHAR(10) NULL
- Transmission                   VARCHAR(10) NOTNULL                    
- Engine Power                   VARCHAR(10) NULL
- Maximum Speed                  VARCHAR(15) NULL
- chasssie number                CHAR (17) NULL UNIQUE
- Notes                          TEXT NULL
- Published                      TINYINT NULL
- created_at                     DATETIME
- updated_at                     DATETIME


