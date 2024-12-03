# db-first
USED_CAR
    id | BIGINT AUTO_INCREMENT
    serial_number | CHAR(7) UNIQUE NOT NULL
    model | VARCHAR(50) NOT NULL
    description | VARCHAR(500) NULL
    producer | VARCHAR(50) NOT NULL
    year | YEAR NULL
    fuel_type | VARCHAR(50) NULL
    transmission | VARCHAR(50) NULL
    km | MEDIUM-INT NULL
    price | DECIMAL(10, 2) NOT NULL
    color | VARCHAR(50) NULL
    doors | TINYINT NULL