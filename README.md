# Proyectofinal-tolerante-a-fallas
Proyecto final de implementacion de una app de microservicios
Para desplegar el proyecto (Windows) el tener instalada la aplicacion de docker
en la cual instalaremos la extension de Portainer: la cual nos facilitara la creacion del proyecto ya que crearemos volumenes redes y contenedores
primero al tener muchos problemas en lo personal al tener compatibilidad decidi buscar una plantilla de wordpress para ser mas rapido mi trabajo ya que estaba muy atrasado
una vexz encontrando la plantilla opte por leer la documentacion de https://hub.docker.com/_/wordpress la cual mencionaba como era su instalacion y su implememntacion al usar
portainer fue aun mas rapido ya que esta extencion te permite crear contenedores volumenes y redes primero opte por decidir como seria la app seria una app simple una cuenta que almacenara lo que un usuario escrbia en wordpress asiq ue se dividio en 2 contenedores el primero almacena la base de datos y con uno de los volumenes lo almacena en la computadora y la otra parte la que carga la app es la que con su propio volumen almacena la app y genera sus consultas

