# Endpoints

## Listagem de Endpoints

- Importar tabelas: Site Embrapa
- Importar tableas: Local
- Consulta tabela Comércio 
- Consulta tabela Exportação 
- Consulta tabela Importação 
- Consulta tabela Processamento 
- Consulta tabela Produção

---

### Importar tabelas: Site Embrapa

`GET` - **/api/importar_csv_site_embrapa**

Exemplo de resposta:

```json
    "Arquivos CSVs importados com sucesso do site da Embrapa!"
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os arquivos foram importados com sucesso.|
|500     | Servidor fora do ar |

---

### Importar tabelas: Local

`GET` - **/api/importar_csv_arquivos**

Exemplo de resposta:

```json
    "Arquivos CSVs importados com sucesso!"
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os arquivos foram importados com sucesso.|
|500     | Sem arquivos para ler|

---

### Comércio

`GET` - **/api/comercializacao/**

Exemplo de resposta:

```json
    [
        {
            "produto": "VINHO DE MESA",
            "ano_1970": 98327606,
            "ano_1971": 114399031,
            "ano_1972": 118377367,
            "ano_1973": 116617910,
            "ano_1974": 94173324,
            "ano_1975": 108031792,
            "ano_1976": 139238614,
            "ano_1977": 140813114,
            ...
        }
    ]
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os dados foram retornados com sucesso.|
|500     | Servidor fora do ar ou falta de importação dos arquivos|

---

### Exportação

`GET` - **/api/exportacao/**

Exemplo de resposta:

```json
    [
        {
            "pais": "Afeganistão",
            "quantidade_1970": 0,
            "valor_1970": 0,
            "quantidade_1971": 0,
            "valor_1971": 0,
            "quantidade_1972": 0,
            "valor_1972": 0,
            "quantidade_1973": 0,
            "valor_1973": 0,
            ...
        }
    ]
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os dados foram retornados com sucesso.|
|500     | Servidor fora do ar ou falta de importação dos arquivos|

---

### Importação

`GET` - **/api/importacao/**

Exemplo de resposta:

```json
    [
        {
            "pais": "Africa do Sul",
            "quantidade_1970": 0,
            "valor_1970": 0,
            "quantidade_1971": 0,
            "valor_1971": 0,
            "quantidade_1972": 0,
            "valor_1972": 0,
            "quantidade_1973": 0,
            "valor_1973": 0,
            ...
        }
    ]
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os dados foram retornados com sucesso.|
|500     | Servidor fora do ar ou falta de importação dos arquivos|

---

### Processamento

`GET` - **/api/processamento/**

Exemplo de resposta:

```json
    [
        {
            "control": "TINTAS",
            "cultivar": "TINTAS",
            "ano_1970": 10448228,
            "ano_1971": 11012833,
            "ano_1972": 10798824,
            "ano_1973": 8213674,
            "ano_1974": 17457849,
            "ano_1975": 22593885,
            "ano_1976": 20265190,
            "ano_1977": 24830345,
            ...
        }
    ]
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os dados foram retornados com sucesso.|
|500     | Servidor fora do ar ou falta de importação dos arquivos|

---

### Produção

`GET` - **/api/producao/**

Exemplo de resposta:

```json
    [
        {
            "produto": "VINHO DE MESA",
            "ano_1970": 217208604,
            "ano_1971": 154264651,
            "ano_1972": 146953297,
            "ano_1973": 116710345,
            "ano_1974": 193875345,
            "ano_1975": 177401209,
            "ano_1976": 144565438,
            "ano_1977": 195359778,
            ...
        }
    ]
```

Códigos da Resposta

| Código | Descrição                            |
|--------|--------------------------------------|
|200     | Os dados foram retornados com sucesso.|
|500     | Servidor fora do ar ou falta de importação dos arquivos|