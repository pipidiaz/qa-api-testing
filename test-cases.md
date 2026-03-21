# Casos de prueba

## Caso 1
Endpoint: /posts  
Método: GET  
Esperado: 200 + lista de posts  

## Caso 2
Endpoint: /posts/1  
Esperado: devuelve un post válido  

## Caso 3
Endpoint: /posts/99999  
Esperado: respuesta vacía o error  

## Caso 4
Endpoint: POST /posts  
Esperado: crea un recurso con status 201
