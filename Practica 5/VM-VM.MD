# Practica 5 VM dentro de una VM

![VM](IMG\virtual-machine.png)

para esta practica necesitaremos crear una maquina virtual dentro de otra maquina virtual, hay que recordar que las maquinas virtuales nos ayudan a extender centros de datos, hacer pruebas etc.

**Requisitos**
- Tener una cuenta De Azure
- iniciar sesion en [Azure](portal.azure.com)
- contar con credito de estudiante
-------------------------------------------------------------------------------------------
1. Primero tenemos que crear dos maquinas virtuales, en el apartado de redes tienen que estar en la misma vred para poder entrar una dentro de la otra, una vez que ya tengamos nuestras maquinas virtuales listas se veran de la siguente manera.

![S4-P1-I2](IMG\S4-P1-I2.jpg)

2. le damos en cualquiera de nuestras maquinas virtuales, le damos en conectar y precionamos RDP, le damos en el boton de descargar RDP.

![S4-P1-I3](IMG\S4-P1-I3.jpg)

3. ya que tengamos abierta nuestra maquina virtual se vera de la siguente manera, es un windows normal, solo que esta en un servidor en alguna parte del mundo.

![S4-P1-I4](IMG\S4-P1-I4.jpg)

4. para conectarnos a nuestra segunda maquina virtual necesitamos colocar el siguente comando en powershell, mstsc v/(iserta la direccion ip privada), aqui ya deveriamos poder acceder a nuestra maquina virtual y aqui completariamos la practica de hoy 👌🙌.

![S4-P1-I4](IMG\S4-P1-I5.jpg)
