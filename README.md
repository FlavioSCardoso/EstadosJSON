# EstadosJSON
Todos estados brasileiros com suas cidades em formato JSON

## Armazene todos estados de uma só vez no MongoDB
mongoimport.exe --db ticc --collection cidades --jsonArray --file estados.json

## Armazene individualmente no MongoDB
mongoimport.exe --db ticc --collection cidades --file \<*ESTADO*\>.json
