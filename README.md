# Postman API Testing — JSONPlaceholder

Colección de Postman para practicar y demostrar testing básico de APIs REST usando JSONPlaceholder.

## Qué incluye
- Requests: GET /posts, POST /posts
- Tests básicos en Postman:
  - Validación de status code (200 / 201)
  - Validación de estructura JSON (array no vacío, existencia de id)
  - Validación de campos en respuesta (title/body/userId)

## Cómo usar
1. Importa en Postman:
   - `postman/JSONPlaceholder.postman_collection.json`
2. Ejecuta las requests y revisa **Test Results**.

## Estructura
- `postman/JSONPlaceholder.postman_collection.json`

## Notas
JSONPlaceholder es una API pública para pruebas. El POST devuelve un `id` simulado.
