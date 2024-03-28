# ATV_07_SINTAXE_SQL

### Código SQL
```sql
-- Adicionar coluna 'estado' à tabela 'alunos'
ALTER TABLE alunos
ADD estado VARCHAR(2);

-- Atualizar todos os registros para definir os valores de 'estado' e 'cidade'
UPDATE alunos
SET estado = 'SP', cidade = 'Osasco'
WHERE id IN (9, 16, 17, 23, 32, 28);

UPDATE alunos
SET estado = 'RJ', cidade = 'Belford Roxo'
WHERE id IN (4, 10, 15, 21, 19);

UPDATE alunos
SET estado = 'MG', cidade = 'Uberlândia'
WHERE id IN (2, 8, 14, 26, 22, 30);

UPDATE alunos
SET estado = 'SC', cidade = 'Florianópolis'
WHERE id IN (3, 11, 18, 29, 24, 34);

UPDATE alunos
SET estado = 'PR', cidade = 'Curitiba'
WHERE id IN (1, 7, 20, 33, 25, 31);

UPDATE alunos
SET estado = 'TO', cidade = 'Palmas'
WHERE id IN (5, 6, 12, 13, 27);

-- Verificar os dados atualizados
SELECT * FROM alunos;
```

### Para listar as músicas pelo 'id', executamos o código:
```sql
-- Ordem decrescente
SELECT * FROM alunos ORDER BY id;

-- Ordem decrescente
SELECT * FROM alunos ORDER BY id DESC;
```

### Para listar as músicas pelo 'nome', executamos o código:
```sql
-- Ordem decrescente
SELECT * FROM alunos ORDER BY nome;

-- Ordem decrescente
SELECT * FROM alunos ORDER BY nome DESC;
```

### Para listar as músicas pelo 'estado', executamos o código:
```sql
-- Ordem decrescente
SELECT * FROM alunos ORDER BY estado;

-- Ordem decrescente
SELECT * FROM alunos ORDER BY estado DESC;
```

### Para listar as músicas pela 'idade', executamos o código:
```sql
-- Ordem decrescente
SELECT * FROM alunos ORDER BY idade;

-- Ordem decrescente
SELECT * FROM alunos ORDER BY idade DESC;
```

