1. Modules: Cada parte del proyecto tiene un dominio que aísla los códigos formados por módulos de clases relacionadas con una funcionalidad de la aplicación.

![image](https://user-images.githubusercontent.com/38531618/187103443-f8263bdb-980a-447b-927f-d1b367e75d66.png)

2. Entities: 
Existen diferentes entidades en el Sistema que desarrollamos, entre ellas podríamos mencionar las entidades Autor, Etiqueta, Post, Categoria, Paper y Usuario ya que son objeto del dominio que mantienen un estado y comportamiento más allá de la ejecución de la aplicación. A continuación se muestra la entidad Autor

![image](https://user-images.githubusercontent.com/38531618/187104230-e626c711-e120-4826-b3f9-2d0e88cdbf2f.png)

3. Value Objects:
Los Value Objects (VO) son solo valores, no entidades, por si solos no significan nada, tienen que estar acompañados de una entidad para que signifiquen algo o ser interpretados. En nuestro sistema identificamos algunos Value Objects, como el siguiente:

![image](https://user-images.githubusercontent.com/38531618/187104334-ed86d260-31b1-4430-8c20-765a460272e2.png)

4. Ubiquitous Language:
Es un concepto de gran importancia porque, además de servir de vehículo de entendimiento en el negocio y entre el negocio e IT, también sirve para identificar las particiones del Domain, que darán lugar a soluciones modulares


![image](https://user-images.githubusercontent.com/38531618/187104230-e626c711-e120-4826-b3f9-2d0e88cdbf2f.png)
![image](https://user-images.githubusercontent.com/38531618/187104861-d0dce624-67dc-4f6f-942b-5bf18fd6ef90.png)
![image](https://user-images.githubusercontent.com/38531618/187104918-dd4d38b6-1382-4dfe-bb6d-400e7a00ef26.png)


5. Repository:
En nuestro proyecto tenemos clases, o más famosamente llamados controladores (MVC), que tienen la función de repositorio, ya que, son los que controlan, dirigen, a la aplicación por dónde debe ir dependiendo de lo que el usuario requiera al interactuar con dicha aplicación.

![image](https://user-images.githubusercontent.com/38531618/187105017-135eb19e-d7d9-4193-8428-d7a393ab5e56.png)
![image](https://user-images.githubusercontent.com/38531618/187105300-3a2dbde0-c942-4397-95db-bdcb4f9f73bf.png)

Un claro ejemplo sería en controlador de Usuario, que guarda diferentes funciones en donde consultamos dichos datos a la base de datos para que luego podemos actualizar un usuario dependiendo del rol del Usuario.
