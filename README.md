# VD-eva-salesforce
resolucion de evaluacion practica
    
  
  2.1 Un servidor HTTP es un programa que tiene la función de procesar los scripts del lado del servidor para dar una salida en HTML y otros lenguajes del lado del cliente al           navegador web del cliente.
  
  2.2 En HTTP se define como verbos HTTP a las "palabras reservadas" para indicar la acción que se desea realizar para un recurso determinado. Los mas conocidos son: GET,  POST,         HEAD, DELETE.
      
  2.3 *request* y *response* son los dos tipos de mensajes HTTP tal que si el cliente le envia un pedido (request) el servidor le devuelve la respuesta (response), Las cabeceras         transmiten informacion necesaria para la comunicacion como tipo de navegadoro, informacion de la pagina o servidor mismo.
  
  2.4 Una cadena de consulta es parte de la URL que asigna valores a parámetros especificados.
  
  2.5 El responseCode es un codigo de 3 digitos que donde el primero digito define que tipo de respuesta estamos obteniendo hay 5 valores para el primer digito:
          *1XX(informativo);
           2XX (Exito);
           3XX(Redireccionamiento);
           4XX(Error de cliente);
           5XX(Error de servidor).*
      Para cada uno de estos los siguientes dos digitos definen que codigo puntual se nos esta respondiendo.
      
  2.6 Usamos links para ejecutar llamadas GET ya que la idea del link es simplemente “solicitar” una información (pagina) al servidor y que sea devuelta como una respuesta.             En cambio POST usamos formularios para actualizar datos, como artículos, usuarios, etc.
  
  2.7 Utiliza GET.
  
  2.8 Las estructuras de datos en JSON son los objetos enceraado entre *{objeto}* y los \[array] en XML estas mismas estructuras se encierran entre etiquetas al estilo HTML             ejemplos:
         
         XML:
              <EjXML>
                <alumnos>
                  <alumno>
                    <alumno_nya>Ramiro De Lorenzo<alumno_nya>
                    <alumno_edad>21<\alumno_edad>
                  <\alumno>
                  <alumno>
                    <alumno_nya>Martin Perez<alumno_nya>
                    <alumno_edad>23<\alumno_edad>
                  <\alumno>
                <alumnos>
              <EjXML>
              
------------------------ 
         
         JSON:
              <EjJSON>
                "alumnos":  [
                            {
                            "alumno": {
                                      "alumno_nya":"Ramiro De Lorenzo",
                                      "alumno_edad":"21"
                                      },
                            "alumno": {
                                      "alumno_nya":"Martin Perez",
                                      "alumno_edad":"23"
                                      }
                            }
                            ]
              <EjJSON>
  
  2.9 SOAP es un protocolo que define de que manera pueden comunicarse dos objetos mediante el intercambio de datos XML.
  
  2.10 *REST* es una tecnología mucho más flexible que transporta datos por medio del protocolo HTTP, pero este permite utilizar los diversos verbos que proporciona HTTP para          comunicarse y utiliza los responseCode nativos de HTTP. *RESTful* es un servicio web basado en *REST*.
                
  2.11 Los headers transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. El  Content-Type se utiliza para indicar el tipo de medio        del recurso. Por ejemplo para el archivo de imagen, su tipo de medio será como image / png o image / jpg, etc.
  
  --------
  
  ![3_1](https://user-images.githubusercontent.com/84874555/135533818-31059dcb-f68f-4161-8f05-d128c1c8bab4.PNG)
  ![3_2](https://user-images.githubusercontent.com/84874555/135533812-a44cd62e-8af5-40be-8bd3-c3768264ab2d.PNG)
  ![3_3](https://user-images.githubusercontent.com/84874555/135533821-beed2a82-e18a-452b-9efb-441dc816d3d3.PNG)
  
  3.3 Las diferencias que se observan son que dado que en el item anterior se hizo un POST con nuetsros datos al realizar nuevamente un GET a la misma url se puede observar como       se obtuvieron los datos previamente insertados.

  --------
  
  4 https://trailblazer.me/id/rdelorenzo
  
  --------
  
  ![Diagrama](https://user-images.githubusercontent.com/84874555/135633073-75eb6ea3-dad0-41f2-b979-cafacfff14fe.jpg)
  
  5.1 Lead: Una *lead* es un objeto predeterminado que se crea cuando se recibe nueva información de contacto en su base de datos.
  
  5.2 Account: Una *account* representa una cuenta de cliente individual, una organización o un socio involucrado con el negocio. Almacenan todos los detalles de la cuenta         relacionados con su negocio, como Clientes y Competidores.
  
  5.3 Contact: Los *contacts* en *Salesforce* almacenan información de las personas, como números de teléfono y direcciones de correo electrónico, y están vinculados a                 *account*. Si un *contact* no está vinculado a una *account*, entonces es un *contact* "privado" y solo lo puede ver el propietario del mismo o el administrador.
  
  5.4 Opportunity: En *Salesforce*, una *opportunity* es una venta o un trato pendiente. Varias *opportunity* conforman su canal de ventas, lo que contribuye a su pronóstico de       ventas.
  
  5.5 Product: Los *products* son los artículos y servicios que vende a los clientes.
  
  5.6 Pricebook: Un *pricebook* es una lista de *productos* y sus precios.
  
  5.7 Quote: Las *quotes* en *Salesforce* representan los precios propuestos de los productos y servicios de su empresa. Creas una *quote* a partir de una *oportunidad* y sus         productos. Cada *oportunidad* puede tener varias *quotes* asociadas y cualquiera de ellas se puede sincronizar con la *oportunidad*.
  
  5.8 Asset: Un *asset* en *Salesforce* representa un producto específico comprado o instalado. Pudiendo rastrear los activos de sus clientes en *Salesforce*, puede ver y             registrar fácilmente el cronograma de compra de cada *asset*, el historial de mantenimiento y más. Puede asociar *asset* con varios *registros de Salesforce* además de           productos.
  
  5.9 Case: Un *case* es una pregunta, un comentario o un problema de un cliente. Los agentes de soporte pueden revisar los *cases* para ver cómo pueden brindar un mejor               servicio. Los representantes de ventas pueden usar *cases* para ver cómo afectan el proceso de ventas.
  
  5.10 Article: la base de *salesforce knowledge* se crea a partir de *artículos de knowledge*, que son documentos de información. Los artículos pueden incluir información sobre        el proceso, por ejemplo cómo restablecer su producto a sus valores predeterminados, o preguntas frecuentes, como la cantidad de almacenamiento que admite su                      producto.

  --------
  
  
