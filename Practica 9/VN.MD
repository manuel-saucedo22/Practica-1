# Practica 9 Azure Virtual Network

![Logo](IMG\Virtual-Networks-Azure-Virtual-Networks-Edureka.png)

**Requisitos**
- iniciar sesion en [Azure](portal.azure.com)
- contar con credito en azure.
-------------------------------------------------------------------------------------------
1. primero cremos un grupo de recursos y despues creamos una Red virtual en donde configuraremos el subneteo a 10.0.0.0/24, nuevamente creamos otra red virtual.
![IMG]()
2. una vez creado vamos a crear una maquina virtual en donde llenaremos los pasos como nombre, grupo de recursos etc, en el apartado de redes nos tienen que aparecer nuestroa Red virtual ya sea la uno o la dos, dependiendo de que maquina sea le colocaremos esa red Virtual.
![IMG](\IMG\S5-P1-I1.png)
3. ya una vez que nuestras maquinas virtuales esten listas y enlazadas nos vamos al apartado de cloud shell aqui iniciamos sesion con nuestra maquina virtual no apareceran bastante texto y tu nombre de usuario cambiara asi que podemos ejecutar el "comando sudo apt.get moo"

![IMG](IMG\S5-P1-I2.png)

4. si hacemos ping no podremos por que nuestras redes no se conocen asi que ahora los conectaremos desde redes virtuales y en emparejamientos, agregamos un emparejamiento y colocamos los datos que nos piden, al final colocaremos RV2 en emparejamiento.

![IMG](\IMG\S5-P1-I4.png)

5. un avez ya conectados podremos hacer un pign exitoso debido a que las maquinas ya se conocen.

![IMG](\IMG\S5-P1-I5.png)

**Nota**
- este es uno de los metodos para administrar la nuve de azure