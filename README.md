# Sql7corespopulares

-- Cria a tabela "cores"
CREATE TABLE cores (
    id INT PRIMARY KEY,
    nome VARCHAR(50) NOT NULL
);

-- Insere as cores populares na tabela
INSERT INTO cores (id, nome)
VALUES
    (1, 'Azul'),
    (2, 'Vermelho'),
    (3, 'Verde'),
    (4, 'Amarelo'),
    (5, 'Laranja'),
    (6, 'Roxo'),
    (7, 'Branco');

-- Exibe as cores inseridas
SELECT * FROM cores;

