# db-first
    id | BIGINT AUTO_INCREMENT PRIMARY KEY
    serial_number | CHAR(17) UNIQUE NOT NULL
    model | VARCHAR(200) NOT NULL
    description | TEXT(500) NULL
    producer | VARCHAR(255) NOT NULL
    year | YEAR NULL
    fuel_type | VARCHAR(50) NULL
    transmission | VARCHAR(50) NULL
    km | INT NULL
    price | DECIMAL(10, 2) NOT NULL
    color | VARCHAR(50) NULL
    doors | TINYINT NULL, -- Numero di porte