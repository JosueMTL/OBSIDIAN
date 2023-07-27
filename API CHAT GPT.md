- npm: versión mas rápida
	
  
```

npm i -g @nestjs/cli // instalar el clic

  

nest new example // crear el proyecto

```
***
<h5>Controladores</h5>
Escucha solicitudes y envía respuestas
<h5>nest g controller cats</h5>  

<h3>Para Acceder a postman</h3> 

```

Para acceder en postman

http://localhost:3000/cats

```



```JS

import { Controller , Get} from '@nestjs/common';

  

  

@Controller('cats')

  

export class CatsController {

  

    @Get()

  

    findAll():string{

  

        return 'Cats Controller Get Succesfull';


    }

  

}
```

EndPoint: Salidas del Controller

Codigos status:

Informational

Succesful

Redirection

Client Error

Server Error

  

Para hacer un post:

```JS

import { Controller , Get , Post} from '@nestjs/common';

  

  

@Controller('cats')

  

export class CatsController {

  

    @Post()

  

    create():string{

  

        return 'Agrega un POST';

  

    }

  

    @Get()

  

    findAll():string{

  

        return 'Cats Controller Get Succesfull';

  

    }

  

}

```

  

Operaciones CRUD

Create

Read

Unite

Delete

  

```c

npx nest generate resource

```

  

Postman:

```

http://localhost:3000/creatures/646

```



- como se instala nesjs/cli
![[Pasted image 20230727092247.png]]

OPERACIONES CRUD
- create 
- read
- unite
- delete