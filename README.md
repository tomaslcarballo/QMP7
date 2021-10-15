# QMP7
1. Como usuarie de QueMePongo quiero ver todas las prendas que tengo en mi guardarropas desde el navegador para poder administrarlas
```bash
https://quemepongo-server.herokuapp.com/prendas/?usuario=tomi
Metodo: GET 
Codigo de respuesta: 200 OK / 404 Not found 
Body:
  {
    "id": 6,
    "tipo": "pantalon",
    "talle": 40
    "usuario":"tomi"
    ....
  }
```  

2. Como usuario de QueMePongo, quiero crear una prenda desde el navegador 
```bash
https://quemepongo-server.herokuapp.com/prendas/?usuario=tomi  
Metodo: POST
Codigo de respuesta: 201 Created / 404 Not found
Body: 
 {
    "id": 7
 }
 ``` 
 
3. Como usuarie de QueMePongo quiero ver una prenda en particular que tengo en mi guardarropas para poder editarla
```bash
https://quemepongo-server.herokuapp.com/prendas/5/?usuario=tomi&prenda=remera  
Metodo: GET
Codigo de respuesta: 200 OK / 404 Not found
Body: 
  {
    "id": 5,
    "tipo": "remera",
    "talle": s
    "usuario":"tomi"
  }
 ```  
 
4. Como usuarie de QueMePongo, quiero poder eliminar una prenda de mi guardarropas
```bash
https://quemepongo-server.herokuapp.com/prendas/5/?usuario=tomi  
Metodo: DELETE 
Codigo de respuesta: 200 OK / 404 Not found
Body: 
  {
    "id": 5,
    "tipo": "remera",
    "talle": s
    "usuario":"tomi"
  }
 ``` 
 
 5. Como usuarie de QueMePongo, quiero poder ver mis eventos para administrarlos
```bash
https://quemepongo-server.herokuapp.com/eventos/?usuario=tomi  
Metodo: GET
Codigo de respuesta: 200 OK / 404 Not found
Body: 
  {
    "id": 1,
    "tipo": "empresarial",
    fecha:"10/02/2021"
    "usuario":"tomi"  
    ....
  }
 ``` 
 
 6. Como usuarie de QueMePongo, quiero poder abrir las sugerencias de prendas para un evento en mi navegador
```bash
https://quemepongo-server.herokuapp.com/sugerencias/?evento=2  
Metodo: GET
Codigo de respuesta: 200 OK / 404 Not found
Body: 
  {
    "id": 5,
    "tipo": "remera",
    "talle": s
    "evento":2
    ....
  }
 ``` 





