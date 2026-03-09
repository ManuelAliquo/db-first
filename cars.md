# Auto in vendita

| Nome colonna  | Tipo di dato   | Attributi                  | Indice      |
| ------------- | -------------- | -------------------------- | ----------- |
| id            | BIGINT         | NOT NULL, UQ, UNSIGNED, AI | PRIMARY KEY |
| marca         | VARCHAR(25)    | NOT NULL                   | INDEX       |
| modello       | VARCHAR(35)    | NOT NULL                   | INDEX       |
| anno          | YEAR           | NOT NULL                   |             |
| tipologia     | VARCHAR(15)    | NOT NULL                   |             |
| alimentazione | VARCHAR(15)    | NOT NULL                   |             |
| potenza_kw    | SMALLINT       | NOT NULL, UNSIGNED         |             |
| km_percorsi   | MEDIUMINT      | NOT NULL, UNSIGNED         |             |
| prezzo_€      | DECIMAL(10, 2) | NOT NULL, UNSIGNED         |             |
