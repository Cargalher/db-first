# Database Car dealership:
## (table)Cars:

- id                             PRIMARY KEY UNIQUE NOTNULL INDEX             
- Manufacturer (Make)            VARCHAR(30) NOTNULL
- Model                          VARCHAR(40) NOTNULL                 
- Manufacturing Year             YEAR NOTNULL
- Milleage (KM)                  MEDIUMMINT NOTNULL
- Description                    TEXT NOTNULL
- Price                          DECIMAL (6,2) NOTNULL
- Seats                          TINYINT NULL
- Doors                          TINYINT NULL
- Environmental impact           VARCHAR(40) NOTNULL
- Mass(KG)                       INT NULL NULL
- Airbag                         VARCHAR(3) NULL DEFAULT
- fuel type                      ARCHAR(30) NOTNULL
- Fuel consumption               VARCHAR(10) NULL
- Transmission                   VARCHAR(10) NOTNULL                    
- Engine Power                   VARCHAR(10) NULL
- Maximum Speed                  VARCHAR(15) NULL



