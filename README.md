# EstadosJSON
Todos estados brasileiros com suas cidades em formato JSON

#### Obs:
Os arquivos .min.json são arquivos sem indentação os arquivos .json são indentados para melhor leitura

## Armazene todos estados de uma só vez no MongoDB
mongoimport.exe --db ticc --collection cidades --jsonArray --file estados.json

## Armazene individualmente no MongoDB
mongoimport.exe --db ticc --collection cidades --file \<*ESTADO*\>.json

