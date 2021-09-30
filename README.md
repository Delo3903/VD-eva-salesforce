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
                
  3.3 Las diferencias que se observan son que dado que en el item anterior se hizo un POST con nuetsros datos al realizar nuevamente un GET a la misma url se puede observar como       se obtuvieron los datos previamente insertados.
