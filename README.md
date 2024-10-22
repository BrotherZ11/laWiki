# laWiki
## Requisitos
```bash
pip install fastapi
pip install uvicorn
pip install pymongo
```

Para ejecutar el códig
```bash
uvicorn main:app --reload
```

Para crear wiki desde cmd:
```bash
curl -X PUT "http://localhost:8000/wiki" -H "Content-Type: application/json" -d '{
    "titulo": "Nueva Wiki",
    "contenido": "Este es el contenido de la nueva wiki.",
    "fecha": "2024-10-22T12:00:00Z",
    "valoraciones": []
}'
```

Para crear wiki desde Postman:
![image](https://github.com/user-attachments/assets/cba805b8-e15c-4678-9282-61d0c2f0e301)
