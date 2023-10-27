# web-security

Conocer como funciona internet y la web es fundamental crear aplicaciones, servicios seguros y escalables.

Construir aplicaciones y servicios en Internet para aprovechar su potencia y conectividad.



|| Introducción a Internet

	Antes de saber qué es Internet, tenemos que entender qué es una red (Network).

	Una red es un grupo de ordenadores u otros dispositivos conectados entre sí.

	Por ejemplo, tú en tu casa puedes tener una red de ordenadores y dispositivos.

	Su amigo, vecino o familiar puede tener una red similar de dispositivos. 

	Todas estas redes conectadas entre sí forman Internet.

	    Internet es una red de redes.

	Internet fue desarrollada a finales de los años 60 por el Departamento de Defensa de Estados Unidos para crear una red de comunicación descentralizada que pudiera resistir un ataque nuclear.

	Con los años, ha evolucionado hasta convertirse en una red compleja y sofisticada que se extiende por todo el planeta.

	Hoy en día, Internet es una parte esencial de la vida moderna, utilizada por miles de millones de personas en todo el mundo para acceder a la información, comunicarse con amigos y familiares, hacer negocios y mucho más.



|| Cómo funciona Internet: Visión general

	A grandes rasgos, Internet funciona conectando dispositivos y sistemas informáticos mediante un conjunto de protocolos estandarizados. 

	Estos protocolos definen cómo se intercambia la información entre dispositivos y garantizan que los datos se transmitan de forma fiable y segura.

	El núcleo de internet es una red global de routers interconectados, que se encargan de dirigir el tráfico entre distintos dispositivos y sistemas.

	Cuando se envían datos por Internet, se dividen en pequeños paquetes (packets) que se envían desde el dispositivo a un router. 

	El enrutador examina el paquete y lo reenvía al siguiente en la ruta hacia su destino. 

	Este proceso continúa hasta que el paquete llega a su destino final.	


	Para garantizar que los paquetes se envían y reciben correctamente, Internet utiliza una serie de protocolos, entre ellos el Protocolo de Internet (IP) y el Protocolo de Control de Transmisión (TCP). 

	IP se encarga de encaminar los paquetes a su destino correcto, mientras que TCP garantiza que los paquetes se transmitan de forma fiable y en el orden correcto.

	Además de estos protocolos básicos, existe una amplia gama de otras tecnologías y protocolos que se utilizan para permitir la comunicación y el intercambio de datos a través de Internet, como el Sistema de Nombres de Dominio (DNS), el Protocolo de Transferencia de Hipertexto (HTTP) y el protocolo Secure Sockets Layer/Transport Layer Security (SSL/TLS). 

	Como desarrollador, es importante tener una sólida comprensión de cómo estas diferentes tecnologías y protocolos trabajan juntos para permitir la comunicación y el intercambio de datos a través de Internet.



|| Conceptos básicos y terminología

	Para entender Internet, es importante familiarizarse con algunos conceptos y terminología básicos:

    Paquete/Packets: 

    	Pequeña unidad de datos que se transmite por Internet.


    Enrutador/Router: 

    	Dispositivo que dirige paquetes de datos entre diferentes redes.


    Dirección IP: 

    	Identificador único asignado a cada dispositivo de una red, utilizado para encaminar los datos al destino correcto.


    Nombre de dominio: 

    	Nombre legible por humanos que se utiliza para identificar un sitio web, como google.com.


    DNS: 

    	El Sistema de Nombres de Dominio se encarga de traducir los nombres de dominio en direcciones IP.


    HTTP: 

    	El Protocolo de Transferencia de Hipertexto se utiliza para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web).


    HTTPS: 

    	versión cifrada de HTTP que se utiliza para proporcionar una comunicación segura entre un cliente y un servidor.


    SSL/TLS: 

    	Los protocolos Secure Sockets Layer y Transport Layer Security se utilizan para proporcionar una comunicación segura a través de Internet.



|| El rol de los protocolos en Internet
	
	Los protocolos desempeñan un papel fundamental a la hora de posibilitar la comunicación y el intercambio de datos en Internet.

	Un protocolo es un conjunto de reglas y normas que definen cómo se intercambia información entre dispositivos y sistemas.

	Hay muchos protocolos diferentes que se utilizan en la comunicación por Internet, como el Protocolo de Internet (IP), el Protocolo de Control de Transmisión (TCP), el Protocolo de Datagramas de Usuario (UDP), el Sistema de Nombres de Dominio (DNS) y muchos otros.

	El IP se encarga de encaminar los paquetes de datos a su destino correcto, mientras que el TCP y el UDP garantizan que los paquetes se transmitan de forma fiable y eficiente. 

	El DNS se utiliza para traducir los nombres de dominio en direcciones IP, y el HTTP para transferir datos entre clientes y servidores.

	Una de las principales ventajas de utilizar protocolos estandarizados es que permiten que dispositivos y sistemas de distintos fabricantes y proveedores se comuniquen entre sí sin problemas. 

	Por ejemplo, un navegador web desarrollado por una empresa puede comunicarse con un servidor web desarrollado por otra, siempre que ambos se adhieran al protocolo HTTP.



|| 	Direcciones IP y nombres de dominio

	Tanto las direcciones IP como los nombres de dominio son conceptos importantes que hay que entender cuando se trabaja con Internet.

	Una dirección IP es un identificador único asignado a cada dispositivo de una red. 
	
	Se utiliza para encaminar los datos al destino correcto, garantizando que la información se envía al destinatario previsto. 

	Las direcciones IP suelen representarse como una serie de cuatro números separados por puntos, como "192.168.1.1".

	Los nombres de dominio, por su parte, son nombres legibles por humanos que se utilizan para identificar sitios web y otros recursos de Internet.

	Suelen estar compuestos por dos o más partes, separadas por puntos. 

	Por ejemplo, "google.com" es un nombre de dominio. 

	Los nombres de dominio se traducen en direcciones IP mediante el Sistema de Nombres de Dominio (DNS).

	El DNS es una parte fundamental de la infraestructura de Internet, responsable de traducir los nombres de dominio en direcciones IP. 

	Cuando usted introduce un nombre de dominio en su navegador web, su ordenador envía una consulta DNS a un servidor DNS, que devuelve la dirección IP correspondiente. 

	Su ordenador utiliza entonces esa dirección IP para conectarse al sitio web u otro recurso que haya solicitado.



|| Introducción a HTTP y HTTPS

	HTTP (Hypertext Transfer Protocol) y HTTPS (HTTP Secure) son dos de los protocolos más utilizados en aplicaciones y servicios basados en Internet.

	HTTP es el protocolo utilizado para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web). 

	Cuando visitas un sitio web, tu navegador envía una petición HTTP al servidor, solicitando la página web u otro recurso que hayas pedido. 

	El servidor devuelve al cliente una respuesta HTTP con los datos solicitados.

	HTTPS es una versión más segura de HTTP, que cifra los datos que se transmiten entre el cliente y el servidor mediante el cifrado SSL/TLS (Secure Sockets Layer/Transport Layer Security). 

	Esto proporciona una capa adicional de seguridad, ayudando a proteger información sensible como credenciales de acceso, información de pago y otros datos personales.

	Cuando visite un sitio web que utilice HTTPS, su navegador mostrará el icono de un candado en la barra de direcciones, indicando que la conexión es segura. También es posible que vea las letras "https" al principio de la dirección del sitio web, en lugar de "http".



||	Creación de aplicaciones con TCP/IP

	TCP/IP (Transmission Control Protocol/Internet Protocol) es el protocolo de comunicación subyacente utilizado por la mayoría de aplicaciones y servicios basados en Internet. 

	Proporciona una entrega de datos fiable, ordenada y con comprobación de errores entre aplicaciones que se ejecutan en distintos dispositivos.

	A la hora de crear aplicaciones con TCP/IP, hay que entender algunos conceptos clave:

    Puertos: 

    	Los puertos se utilizan para identificar la aplicación o el servicio que se ejecuta en un dispositivo. 

    	A cada aplicación o servicio se le asigna un número de puerto único, lo que permite que los datos se envíen al destino correcto.


    Sockets: 

    	Un socket es una combinación de una dirección IP y un número de puerto, que representa un punto final específico para la comunicación. 

    	Los sockets se utilizan para establecer conexiones entre dispositivos y transferir datos entre aplicaciones.


	Conexiones: 

		Una conexión se establece entre dos sockets cuando dos dispositivos quieren comunicarse entre sí. 

		Durante el proceso de establecimiento de la conexión, los dispositivos negocian diversos parámetros, como el tamaño máximo del segmento y el tamaño de la ventana, que determinan cómo se transmitirán los datos a través de la conexión.


	Transferencia de datos: 

		Una vez establecida la conexión, se pueden transferir datos entre las aplicaciones que se ejecutan en cada dispositivo. 

		Los datos suelen transmitirse en segmentos, cada uno de los cuales contiene un número de secuencia y otros metadatos para garantizar una entrega fiable.


	Cuando construyas aplicaciones con TCP/IP, necesitarás asegurarte de que tu aplicación está diseñada para trabajar con los puertos, sockets y conexiones apropiados. 

	También tendrás que estar familiarizado con los distintos protocolos y estándares que se utilizan habitualmente con TCP/IP, como HTTP, FTP (File Transfer Protocol) y SMTP (Simple Mail Transfer Protocol). 

	Comprender estos conceptos y protocolos es esencial para crear aplicaciones y servicios basados en Internet eficaces, escalables y seguros.



|| Asegurando la Comunicación en Internet con SSL/TLS (Securing Internet Communication)

	Como hemos comentado anteriormente, SSL/TLS es un protocolo utilizado para cifrar los datos que se transmiten a través de Internet. 

	Se utiliza habitualmente para proporcionar conexiones seguras a aplicaciones como navegadores web, clientes de correo electrónico y programas de transferencia de archivos.

	Cuando se utiliza SSL/TLS para asegurar la comunicación en Internet, hay algunos conceptos clave que hay que entender:

    Certificados (Certificates): 

    	Los certificados SSL/TLS se utilizan para establecer la confianza entre el cliente y el servidor. 

    	Contienen información sobre la identidad del servidor y están firmados por un tercero de confianza (una autoridad de certificación) para verificar su autenticidad.


    Intercambio (Handshake): 

    	Durante el proceso de negociación SSL/TLS, el cliente y el servidor intercambian información para negociar el algoritmo de cifrado y otros parámetros de la conexión segura.


    Cifrado (Encryption): 

    	Una vez establecida la conexión segura, los datos se cifran utilizando el algoritmo acordado y pueden transmitirse de forma segura entre el cliente y el servidor.


	Al crear aplicaciones y servicios basados en Internet, es importante comprender cómo funciona SSL/TLS y asegurarse de que su aplicación está diseñada para utilizar SSL/TLS cuando transmita datos confidenciales como credenciales de inicio de sesión, información de pago y otros datos personales. 

	También tendrá que asegurarse de que obtiene y mantiene certificados SSL/TLS válidos para sus servidores, y de que sigue las mejores prácticas para configurar y proteger sus conexiones SSL/TLS.

	De este modo, puede ayudar a proteger los datos de sus usuarios y garantizar la integridad y confidencialidad de la comunicación de su aplicación a través de Internet.



|| El futuro: Tendencias y tecnologías emergentes

	Internet evoluciona constantemente, y no dejan de surgir nuevas tecnologías y tendencias. 

	Como desarrollador, es importante estar al día de los últimos avances para crear aplicaciones y servicios innovadores y eficaces.

	Estas son algunas de las tendencias y tecnologías emergentes que están dando forma al futuro de Internet:

    5G: 

    	5G es la última generación de tecnología de redes móviles, que ofrece velocidades más rápidas, menor latencia y mayor capacidad que las generaciones anteriores. 

  	 	Se espera que permita nuevos casos de uso y aplicaciones, como los vehículos autónomos y la cirugía a distancia.


    Internet de las Cosas (IoT): 

    	IoT se refiere a la red de dispositivos físicos, vehículos, electrodomésticos y otros objetos que están conectados a Internet y pueden intercambiar datos. 

    	A medida que IoT siga creciendo, se espera que revolucione sectores como la sanidad, el transporte y la fabricación.


    Inteligencia Artificial (IA): 

    	Las tecnologías de IA, como el aprendizaje automático y el procesamiento del lenguaje natural, ya se están utilizando para impulsar una amplia gama de aplicaciones y servicios, desde asistentes de voz hasta la detección del fraude. 

    	A medida que la IA siga avanzando, se espera que permita nuevos casos de uso y transforme sectores como la sanidad, las finanzas y la educación.


    Blockchain: 

    	Blockchain es una tecnología de libro mayor distribuido que permite transacciones seguras y descentralizadas. 

    	Se está utilizando para impulsar una amplia gama de aplicaciones, desde la criptomoneda hasta la gestión de la cadena de suministro.


    Edge computing: 

    	La computación de borde se refiere al procesamiento y almacenamiento de datos en el borde de la red, en lugar de en centros de datos centralizados. 

    	Se espera que permita nuevos casos de uso y aplicaciones, como análisis en tiempo real y aplicaciones de baja latencia.


	Si se mantiene al día de estas y otras tendencias y tecnologías emergentes, podrá asegurarse de que sus aplicaciones y servicios se crean para aprovechar las últimas capacidades y ofrecer la mejor experiencia posible a sus usuarios.


	
|| Whitepaper de Internet

	Explica la infraestructura y las tecnologías subyacentes que hacen que Internet funcione. 

	
	Direcciones de Internet (Internet Address):
		
		Dado que Internet es una red mundial de ordenadores, cada ordenador conectado a Internet debe tener una dirección única. 

		Las direcciones de Internet tienen la forma nnn.nnn.nnn.nnn donde nnn debe ser un número del 0 al 255. 

		Esta dirección se conoce como dirección IP. (Internet Protocol)


		Diagrama de Internet: 

			La imagen siguiente ilustra dos ordenadores conectados a Internet: tu ordenador con la dirección IP 1.2.3.4 y otro ordenador con la dirección IP 5.6.7.8. 

			Internet se representa como un objeto abstracto intermedio.
	

		Pilas de protocolos y paquetes/Protocol Stacks and Packets:
			
			Su ordenador está conectado a Internet y tiene una dirección única. 

			¿Cómo "habla" con otros ordenadores conectados a Internet? Sirva un ejemplo: Supongamos que tu dirección IP es 1.2.3.4 y quieres enviar un mensaje al ordenador 5.6.7.8.

			El mensaje que quieres enviar es "¡Hola ordenador 5.6.7.8!". Obviamente, el mensaje debe transmitirse a través de cualquier tipo de cable que conecte tu ordenador a Internet. 

			Digamos que has marcado a tu ISP desde casa y el mensaje debe transmitirse a través de la línea telefónica. 

			Por lo tanto, el mensaje debe traducirse de texto alfabético a señales electrónicas, transmitirse por Internet y, a continuación, volver a traducirse a texto alfabético.

			¿Cómo se consigue esto? Utilizando una pila de protocolos. 

			Todos los ordenadores necesitan una para comunicarse en Internet y suele estar integrada en el sistema operativo del ordenador (por ejemplo, Windows, Unix, etc.).

			La pila de protocolos utilizada en Internet se denomina pila de protocolos TCP/IP debido a los dos principales protocolos de comunicación utilizados. 


			Diagrama de la pila TCP/IP:	

				Tenemos la pila de protocolas de nuestra pc que se conectará a Internet y está se conectará con la pila de otro ordenador. 


			Capa de protocolos de aplicación (APL):

				Protocolos específicos de aplicaciones como WWW, correo electrónico, FTP, etc.


			Capa de protocolo de control de transmisión (TCP):

				TCP dirige los paquetes a una aplicación específica en un ordenador utilizando un número de puerto.


			Capa de Protocolo de Internet (IP):

				IP dirige los paquetes a un ordenador específico utilizando una dirección IP.


			Capa de hardware:

				Convierte los paquetes de datos binarios en señales de red y viceversa.

				(Por ejemplo, tarjeta de red Ethernet, módem para líneas telefónicas, etc.)


			Si siguiéramos el camino que siguió el mensaje "¡Hola ordenador 5.6.7.8!" desde nuestro ordenador hasta el ordenador con dirección IP 5.6.7.8, sucedería algo así



			1. El mensaje empezaría en la parte superior de la pila de protocolos de tu ordenador y seguiría hacia abajo.


		    2. Si el mensaje que se va a enviar es largo, cada capa de la pila por la que pase el mensaje puede dividirlo en trozos de datos más pequeños.

		    Esto se debe a que los datos enviados por Internet (y la mayoría de las redes informáticas) se envían en trozos manejables. En Internet, estos trozos de datos se conocen como paquetes.


		    3. Los paquetes pasan por la capa de aplicación y continúan hasta la capa TCP. 

		    A cada paquete se le asigna un número de puerto.

		    Los puertos se explicarán más adelante, pero baste decir que muchos programas pueden estar utilizando la pila TCP/IP y enviando mensajes. 

		    Necesitamos saber qué programa en el ordenador de destino necesita recibir el mensaje porque estará escuchando en un puerto específico.


		    4. Después de pasar por la capa TCP, los paquetes pasan a la capa IP. Aquí es donde cada paquete recibe su dirección de destino, 5.6.7.8.


		    5. Ahora que nuestros paquetes de mensajes tienen un número de puerto y una dirección IP, están listos para ser enviados a través de Internet. 

		    La capa de hardware se encarga de convertir los paquetes que contienen el texto alfabético de nuestro mensaje en señales electrónicas y transmitirlas a través de la línea telefónica.


		    6. En el otro extremo de la línea telefónica, su ISP tiene una conexión directa a Internet. 

		    El router del ISP examina la dirección de destino de cada paquete y determina dónde enviarlo. 

		    A menudo, la siguiente parada del paquete es otro router.

		    Más adelante hablaremos de los routers y la infraestructura de Internet.


			7. Finalmente, los paquetes llegan al ordenador 5.6.7.8.

			Aquí, los paquetes empiezan en la parte inferior de la pila TCP/IP del ordenador de destino y van subiendo.

			8. A medida que los paquetes ascienden por la pila, todos los datos de enrutamiento que la pila del ordenador remitente ha añadido (como la dirección IP y el número de puerto) se eliminan de los paquetes.


			9. Cuando los datos llegan a la parte superior de la pila, los paquetes se han vuelto a ensamblar en su forma original: "¡Hola ordenador 5.6.7.8!".



|| Infraestructura de red (network)

	Pero, ¿qué hay entre medias? ¿Qué conforma Internet? Diagrama:
		
		Intervienen tu computadora, su modem y el cable de tu proveedor que viaja por su red en las calles a su grupo de modem. 

		Los dispositivos del proveedor son sus servidor de puertos y su red de routers. 

		La conexión física a través de la red telefónica con el proveedor de servicios de Internet puede ser fácil de adivinar, pero más allá de eso puede requerir alguna explicación.


	El ISP mantiene un grupo de módems para sus clientes de acceso telefónico. 

	Esto se gestiona mediante algún tipo de ordenador (normalmente uno dedicado) que controla el flujo de datos desde el grupo de módems a un router troncal o de línea dedicada.

	Esta configuración puede denominarse servidor de puertos, ya que "sirve" de acceso a la red. 

	Aquí también se suele recoger la información de facturación y uso.

	Después de que tus paquetes atraviesen la red telefónica y el equipo local de tu ISP, se dirigen a la red troncal del ISP o a una red troncal a la que el ISP compra ancho de banda. 

	A partir de aquí, los paquetes suelen viajar a través de varios routers y por varias redes troncales, líneas dedicadas y otras redes hasta que encuentran su destino, el ordenador con la dirección 5.6.7.8. 

	Pero, ¿no estaría bien conocer la ruta exacta que siguen nuestros paquetes por Internet? Pues resulta que hay una manera...



|| Infraestructura de Internet	

	La red tronca de Internet (Internet backbone) está formada por muchas grandes redes que se interconectan entre sí. 

	Estas grandes redes se conocen como Proveedores de Servicios de Red o PSN (Network Service Providers or NSPs). 

	Estas redes se conectan entre sí para intercambiar tráfico de paquetes. 

	Cada NSP debe conectarse a tres puntos de acceso a la red o NAP (Network Access Points or NAPs). 

	En los NAP, el tráfico de paquetes puede saltar de la red troncal de un NSP a la de otro NSP. 

	Los NSP también se interconectan en intercambiadores de área metropolitana o MAE. 

	Los MAE (Metropolitan Area Exchanges or MAEs) cumplen la misma función que los NAP, pero son de propiedad privada. 

	Los NAP fueron los puntos de interconexión originales de Internet.

	Tanto los NAP como los MAE se denominan Puntos de Intercambio de Internet o IX. 

	Los NSP también venden ancho de banda a redes más pequeñas, como ISP y proveedores de ancho de banda más pequeños. 

	Diagrama de la red NAP, NSP y ISP: 

		Vemos como los puntos de acceso a la red (NAP) permiten la conexión de los Proveedores de Servicios de Red (NSP) que permiten la conexión de los Provedores de Servicios de Internet (ISP) regionales y locales que usan los consumidores finales. 

	No se trata de una representación fiel de un trozo real de Internet. 

	El diagrama pretende demostrar cómo los PSN podrían interconectarse entre sí y con los PSI más pequeños. 

	En diagrama no muestra ninguno de los componentes físicos de la red, como en el diagrama anterior. 

	Esto se debe a que un único PSN puede interconectarse entre sí. 

	Esto se debe a que la infraestructura troncal de un único PSN es un dibujo complejo en sí mismo. 

	La mayoría de los NSP publican mapas de su infraestructura de red en sus sitios web y se pueden encontrar fácilmente. 

	Dibujar un mapa real de Internet sería casi imposible debido a su tamaño, complejidad y estructura siempre cambiante.



|| Jerarquía de enrutamiento en Internet/The Internet Routing Hierarchy
	
	¿Cómo encuentran los paquetes su camino a través de Internet? ¿Sabe cada ordenador conectado a Internet dónde están los demás? ¿Los paquetes se "difunden" a todos los ordenadores de Internet? La respuesta a las dos preguntas anteriores es "no". 

	Ningún ordenador sabe dónde están los demás y los paquetes no se envían a todos los ordenadores. 

	La información que se utiliza para que los paquetes lleguen a su destino está contenida en las tablas de enrutamiento (routing tables) que guarda cada router conectado a Internet.

	Los routers son conmutadores de paquetes (packet switches). 

	Un router suele estar conectado entre redes para enrutar paquetes entre ellas. 

	Cada router conoce sus subredes y las direcciones IP que utilizan. 

	El router normalmente no sabe qué direcciones IP están "por encima" de él.

	
	Diagrama de enrutamiento:

		Los routers de los proveedores de servicios de red (NSP) e internet (ISP) se utilizan para interconectar sus infraestructuras con los puntos de acceso (NAP). 


	Las cajas negras que conectan las redes troncales son routers. 

	Las redes troncales NSP más grandes de la parte superior están conectadas a un NAP. 

	Debajo de ellas hay varias subredes, y debajo de ellas, más subredes. 

	En la parte inferior hay dos redes de área local con ordenadores conectados.


	Cuando un paquete llega a un router, éste examina la dirección IP colocada allí por la capa del protocolo IP en el ordenador de origen. 

	El enrutador comprueba su tabla de enrutamiento. 

	Si encuentra la red que contiene la dirección IP, el paquete se envía a esa red. 

	Si no se encuentra la red que contiene la dirección IP, el router envía el paquete por una ruta por defecto, normalmente por la jerarquía de la red troncal hasta el siguiente router. 

	Con suerte, el siguiente router sabrá dónde enviar el paquete. 

	Si no lo sabe, de nuevo el paquete se enruta hacia arriba hasta que llega a una red troncal NSP. 

	Los routers conectados a las redes troncales NSP tienen las tablas de enrutamiento más grandes y aquí el paquete será enrutado a la red troncal correcta, donde comenzará su viaje "hacia abajo" a través de redes cada vez más pequeñas hasta que encuentre su destino.



|| Nombres de dominio y resolución de direcciones/Domain Names and Address Resolution

	Pero, ¿qué ocurre si no conoce la dirección IP del ordenador al que desea conectarse? ¿Y si necesita acceder a un servidor web denominado www.anothercomputer.com? ¿Cómo sabe su navegador en qué lugar de Internet se encuentra ese ordenador? La respuesta a todas estas preguntas es el Servicio de Nombres de Dominio o DNS. 

	El DNS es una base de datos distribuida que lleva la cuenta de los nombres de los ordenadores y sus correspondientes direcciones IP en Internet.

	Muchos ordenadores conectados a Internet alojan parte de la base de datos DNS y el software que permite a otros acceder a ella. 

	Estos ordenadores se conocen como servidores DNS. 

	Ningún servidor DNS contiene toda la base de datos; sólo contienen un subconjunto de ella. 

	Si un servidor DNS no contiene el nombre de dominio solicitado por otro ordenador, el servidor DNS redirige al ordenador solicitante a otro servidor DNS.

	 
	El Servicio de Nombres de Dominio está estructurado como una jerarquía similar a la jerarquía de enrutamiento IP. 

	El ordenador que solicita una resolución de nombre será redirigido "hacia arriba" en la jerarquía hasta que se encuentre un servidor DNS que pueda resolver el nombre de dominio de la solicitud. 


	Diagrama del Sistema de Nombres de Dominio (DNS):

		En la parte superior del árbol se encuentran las raíces de los dominios. 

		Algunos de los dominios más antiguos y comunes se ven cerca de la parte superior. 

		Lo que no se muestra es la multitud de servidores DNS de todo el mundo que forman el resto de la jerarquía.


	Cuando se configura una conexión a Internet (por ejemplo, para una LAN o una red de acceso telefónico en Windows), se suelen especificar un servidor DNS primario y uno o varios secundarios como parte de la instalación.

	De esta forma, cualquier aplicación de Internet que necesite resolución de nombres de dominio podrá funcionar correctamente. 

	Por ejemplo, cuando se introduce una dirección web en el navegador, éste se conecta primero al servidor DNS primario. 

	Una vez obtenida la dirección IP del nombre de dominio introducido, el navegador se conecta al ordenador de destino y solicita la página web deseada.



|| Los protocolos de Internet/Internet Protocols:

	En Internet se utilizan muchos protocolos de comunicación para funcionar. 

	Entre ellos se incluyen los protocolos TCP e IP, los protocolos de enrutamiento, los protocolos de control de acceso al medio, los protocolos de nivel de aplicación, etc. 

	En los siguientes apartados se describen algunos de los protocolos más importantes y utilizados en Internet. 

	En primer lugar se describen los protocolos de nivel superior y, a continuación, los de nivel inferior.



|| Protocolos de aplicación: HTTP y la World Wide Web
	
	Uno de los servicios más utilizados en Internet es la World Wide Web (WWW).

	El protocolo de aplicación que hace funcionar la web es el Protocolo de Transferencia de Hipertexto o HTTP. 

	No hay que confundirlo con el Lenguaje de Marcado de Hipertexto (HTML). 

	HTML es el lenguaje utilizado para escribir páginas web. 

	HTTP es el protocolo que utilizan los navegadores y servidores web para comunicarse entre sí a través de Internet. 

	Se trata de un protocolo de nivel de aplicación porque se sitúa sobre la capa TCP de la pila de protocolos y es utilizado por aplicaciones específicas para comunicarse entre sí. 

	En este caso, las aplicaciones son navegadores y servidores web.

	HTTP es un protocolo basado en texto sin conexión. 

	Los clientes (navegadores web) envían peticiones a los servidores web para obtener elementos web como páginas web e imágenes. 

	Una vez que el servidor atiende la petición, se desconecta la conexión entre cliente y servidor a través de Internet. 


	Cuando se teclea una URL en un navegador web, esto es lo que ocurre:

	    1. Si la URL contiene un nombre de dominio, el navegador se conecta primero a un servidor de nombres de dominio y obtiene la dirección IP correspondiente del servidor web.

	    2. El navegador se conecta al servidor web y envía una petición HTTP (a través de la pila de protocolos) para la página web deseada.

	    3. El servidor web recibe la petición y comprueba si existe la página deseada. 

	    Si la página existe, el servidor web la envía. 

	    Si el servidor no puede encontrar la página solicitada, enviará un mensaje de error HTTP 404. (404 significa "Página no encontrada", como probablemente sepa cualquiera que haya navegado por Internet).

	    4. El navegador recibe la página de vuelta y se cierra la conexión.
	    
	    5. A continuación, el navegador analiza la página y busca otros elementos necesarios para completarla. Estos elementos suelen ser imágenes, applets, etc.

	    6. Para cada elemento necesario, el navegador realiza conexiones adicionales y peticiones HTTP al servidor para cada elemento.

	    7. Cuando el navegador haya terminado de cargar todas las imágenes, applets, etc., la página estará completamente cargada en la ventana del navegador.


	La mayoría de los protocolos de Internet se especifican en documentos de Internet conocidos como Request For Comments o RFC. 

	Las RFC pueden encontrarse en varios lugares de Internet. 

	Consulte la sección Recursos más adelante para obtener las URL adecuadas. 

	La versión 1.0 de HTTP está especificada en el RFC 1945.



|| Protocolos de aplicación: SMTP y correo electrónico/Application Protocols: SMTP and Electronic Mail

	Otro servicio de Internet muy utilizado es el correo electrónico. 

	El correo electrónico utiliza un protocolo de nivel de aplicación llamado Protocolo Simple de Transferencia de Correo o SMTP. 

	SMTP también es un protocolo basado en texto, pero a diferencia de HTTP, SMTP está orientado a la conexión. 

	SMTP también es más complicado que HTTP. Hay muchos más comandos y consideraciones en SMTP que en HTTP.

	Cuando abres tu cliente de correo para leer tu e-mail, esto es lo que suele ocurrir:

	    1. El cliente de correo (Yahoo!, Hotmail, Outlook y Gmail, etc.) abre una conexión con su servidor de correo predeterminado. 

	    2. La dirección IP o el nombre de dominio del servidor de correo suele configurarse cuando se instala el cliente de correo.

	    El servidor de correo siempre transmitirá el primer mensaje para identificarse.

	    3. El cliente enviará un comando SMTP HELO al que el servidor responderá con un mensaje 250 OK.

		4. Dependiendo de si el cliente está comprobando el correo, enviando correo, etc. 

		Se enviarán los comandos SMTP apropiados al servidor, que responderá en consecuencia.

    	5. Esta transacción de solicitud/respuesta continuará hasta que el cliente envíe un comando SMTP QUIT. 

    	El servidor se despedirá entonces y se cerrará la conexión. 


	A continuación se muestra una "conversación" sencilla entre un cliente SMTP y un servidor SMTP. 

	R: denota los mensajes enviados por el servidor (receptor) y S: denota los mensajes enviados por el cliente (remitente).

  	Este ejemplo SMTP muestra el correo enviado por Smith en el host USC-ISIF, a Jones, Green y Brown en el host BBN-UNIX.  

  	Suponemos que USC-ISIF contacta directamente con BBN-UNIX.  

  	El correo es aceptado para Jones y Brown.  

  	Green no tiene buzón en
  	BBN-UNIX.

  		R: 220 BBN-UNIX.ARPA Simple Mail Transfer Service Ready
        S: HELO USC-ISIF.ARPA
        R: 250 BBN-UNIX.ARPA

        S: MAIL FROM:<Smith@USC-ISIF.ARPA>
        R: 250 OK

        S: RCPT TO:<Jones@BBN-UNIX.ARPA>
        R: 250 OK

        S: RCPT TO:<Green@BBN-UNIX.ARPA>
        R: 550 No such user here

        S: RCPT TO:<Brown@BBN-UNIX.ARPA>
        R: 250 OK


    Esta transacción SMTP está tomada del RFC 821, que especifica SMTP.



|| Protocolo de Control de Transmisión/Transmission Control Protocol

	Bajo la capa de aplicación de la pila de protocolos se encuentra la capa TCP. 

	Cuando las aplicaciones abren una conexión con otro ordenador en Internet, los mensajes que envían (utilizando un protocolo específico de la capa de aplicación) pasan a la capa TCP. 

	TCP es responsable de enrutar los protocolos de aplicación a la aplicación correcta en el ordenador de destino. 

	Para ello, se utilizan números de puerto. 

	Los puertos pueden considerarse como canales separados en cada ordenador.

	Por ejemplo, puedes navegar por Internet mientras lees el correo electrónico. 

	Esto se debe a que estas dos aplicaciones (el navegador web y el cliente de correo) utilizan números de puerto diferentes. 

	Cuando un paquete llega a un ordenador y asciende por la pila de protocolos, la capa TCP decide qué aplicación recibe el paquete basándose en un número de puerto.


	TCP funciona así:

	    Cuando la capa TCP recibe los datos del protocolo de la capa de aplicación desde arriba, los segmenta en "trozos" manejables y, a continuación, añade a cada "trozo" una cabecera TCP con información específica de TCP. 

	    La información contenida en la cabecera TCP incluye el número de puerto de la aplicación a la que deben enviarse los datos.

	    Cuando la capa TCP recibe un paquete de la capa IP inferior, la capa TCP extrae los datos de la cabecera TCP del paquete, reconstruye los datos si es necesario y los envía a la aplicación correcta utilizando el número de puerto extraído de la cabecera TCP. 


	Así es como TCP dirige los datos que se mueven a través de la pila de protocolos a la aplicación correcta.

	TCP no es un protocolo textual. 

	TCP es un servicio de flujo de bytes fiable y orientado a la conexión (connection-oriented, reliable, byte stream service). 

	Orientado a la conexión significa que dos aplicaciones que utilizan TCP deben establecer primero una conexión antes de intercambiar datos. 

	TCP es fiable porque por cada paquete recibido se envía un acuse de recibo al remitente para confirmar la entrega. 

	TCP también incluye una suma de comprobación en su cabecera para verificar los errores de los datos recibidos (header for error-checking the received data). 
	
	Diagrama de la cabecera de un de TCP: 	
		16-bit source port number | 16-bit destination port number

		32-bit secuence number

		32-bit acknowledgement number

		misc. data including header legth | 16-bit windows size 

		16-bit TCP check sum | 16-bit urgent pointer

		{20 bytes}

		Options (if any)

		data 


	Observa que no hay lugar para una dirección IP en la cabecera TCP. 

	Esto se debe a que TCP no sabe nada sobre direcciones IP.

	El trabajo de TCP es obtener datos a nivel de aplicación de aplicación a aplicación de forma fiable. 

	La tarea de obtener datos de ordenador a ordenador es el trabajo de IP.



|| Protocolo de Internet (Internet Protocol)

	A diferencia de TCP, IP es un protocolo no fiable y sin conexión. 

	A IP no le importa si un paquete llega a su destino o no. 

	Tampoco conoce las conexiones ni los números de puerto. 

	El trabajo de IP es enviar y enrutar paquetes a otros ordenadores. 

	Los paquetes IP son entidades independientes y pueden llegar fuera de orden o no llegar en absoluto.

	El trabajo de TCP es asegurarse de que los paquetes llegan y están en el orden correcto. 

	Lo único que IP tiene en común con TCP es la forma en que recibe los datos y añade su propia información de cabecera IP a los datos TCP. 

	Diagrama de la cabecera IP tiene este aspecto:

		version, header length, type of service | 16-bit total length (in byte)

		16-bit identification | flags | 13-bit fragment offset 

		8-bit time to live | 8-bit protocol | 16-bit header check sum

		32-bit source IP address 

		32-bit destination IP address 

		{20 bytes}

		Options (if any)

		data 


	Arriba vemos las direcciones IP de los ordenadores emisor y receptor en la cabecera IP. 

	Abajo vemos el aspecto de un paquete después de pasar por la capa de aplicación, la capa TCP y la capa IP.

	Los datos de la capa de aplicación se segmentan en la capa TCP, se añade la cabecera TCP, el paquete continúa hasta la capa IP, se añade la cabecera IP y, a continuación, el paquete se transmite a través de Internet.


	Diagrama de un paquete completo:

		IP header {20 bytes} | TCP header {20 bytes} | data from aplication layer 



|| HTTP/1 y HTTP/2

	
	HTTP: 

		El Protocolo de Transferencia de Hipertexto, o HTTP, es un protocolo de aplicación que ha sido el estándar de facto para la comunicación en la World Wide Web desde su invención en 1989. 

		Desde el lanzamiento de HTTP/1.1 en 1997 hasta hace poco, ha habido pocas revisiones del protocolo.

		Pero en 2015, entró en uso una versión reimaginada llamada HTTP/2, que ofrecía varios métodos para disminuir la latencia, especialmente cuando se trataba de plataformas móviles y gráficos y vídeos de uso intensivo del servidor. 


		Comienzo: 	

			HTTP/1.1 fue desarrollado por Timothy Berners-Lee en 1989 como estándar de comunicación para la World Wide Web, HTTP es un protocolo de aplicación de alto nivel que intercambia información entre un ordenador cliente y un servidor web local o remoto. 

			En este proceso, un cliente envía una petición basada en texto a un servidor llamando a un método como GET o POST.

			Como respuesta, el servidor envía un recurso, como una página HTML, al cliente.

			Por ejemplo, supongamos que visita un sitio web en el dominio www.example.com.

			Cuando navegas a esta URL, el navegador de tu ordenador envía una petición HTTP en forma de mensaje de texto, similar al que se muestra aquí:

				```
					GET /index.html HTTP/1.1
					Host: www.example.com
				
				```

			Esta petición utiliza el método GET, que solicita datos del servidor host que aparece después de Host:. 

			En respuesta a esta petición, el servidor web de ejemplo.com devuelve una página HTML al cliente solicitante, además de las imágenes, hojas de estilo u otros recursos solicitados en el HTML. 

			Tenga en cuenta que no todos los recursos se devuelven al cliente en la primera petición de datos. 

			Las peticiones y respuestas irán y vendrán entre el servidor y el cliente hasta que el navegador web haya recibido todos los recursos necesarios para representar el contenido de la página HTML en su pantalla.

			Este intercambio de peticiones y respuestas puede considerarse como una capa de aplicación única de la pila de protocolos de Internet, que se asienta sobre la capa de transferencia (que suele utilizar el Protocolo de Control de Transmisión, o TCP) y las capas de red (que utilizan el Protocolo de Internet, o IP):

				Diagrama de pila de protocolos: 

					Host (Navegador/Browser)

						App Layer (HTTP)

						Transport Layer (TCP)

						Network Layer (IP)

						Data Link Layer

					
					Internet (Conecta Host a Target)


					Target (Webserver): 

						App Layer (HTTP)

						Transport Layer (TCP)

						Network Layer (IP)

						Data Link Layer


	HTTP/2: 

 		Cambios técnicos que HTTP/2 ha adoptado para lograr un protocolo Web más eficiente.	

 		HTTP/2 comenzó como el protocolo SPDY, desarrollado principalmente en Google con la intención de reducir la latencia de carga de las páginas web mediante técnicas como la compresión, la multiplexación y la priorización.

 		Este protocolo sirvió de plantilla para HTTP/2 cuando el grupo de trabajo httpbis del protocolo de transferencia de hipertexto del IETF (Internet Engineering Task Force) elaboró el estándar, que culminó con la publicación de HTTP/2 en mayo de 2015. 

 		Desde el principio, muchos navegadores apoyaron este esfuerzo de estandarización, incluidos Chrome, Opera, Internet Explorer y Safari. 

 		Debido en parte a este apoyo de los navegadores, ha habido una tasa de adopción significativa del protocolo desde 2015, con tasas especialmente altas entre los nuevos sitios.

		Desde un punto de vista técnico, una de las características más significativas que distingue HTTP/1.1 y HTTP/2 es la capa de framing binario, que puede considerarse parte de la capa de aplicación en la pila de protocolos de Internet. 

		A diferencia de HTTP/1.1, que mantiene todas las peticiones y respuestas en formato de texto plano, HTTP/2 utiliza la capa de enmarcado binario para encapsular todos los mensajes en formato binario, manteniendo la semántica HTTP, como verbos, métodos y cabeceras. 

		Una API a nivel de aplicación seguiría creando mensajes en los formatos HTTP convencionales, pero la capa subyacente los convertiría en binarios. 

		Esto garantiza que las aplicaciones web creadas antes de HTTP/2 puedan seguir funcionando con normalidad al interactuar con el nuevo protocolo.

		La conversión de mensajes a binario permite a HTTP/2 probar nuevos enfoques de entrega de datos no disponibles en HTTP/1.1, un contraste que está en la raíz de las diferencias prácticas entre los dos protocolos. 


		Modelos de entrega/Delivery Models:

			Como se mencionó en la sección anterior, HTTP/1.1 y HTTP/2 comparten semántica, asegurando que las peticiones y respuestas que viajan entre el servidor y el cliente en ambos protocolos lleguen a sus destinos como mensajes formateados tradicionalmente con cabeceras y cuerpos, utilizando métodos familiares como GET y POST. 

			Pero mientras HTTP/1.1 los transfiere en mensajes de texto plano, HTTP/2 los codifica en binario, permitiendo posibilidades de modelos de entrega significativamente diferentes.

			En esta sección, primero examinaremos brevemente cómo HTTP/1.1 intenta optimizar la eficiencia con su modelo de entrega y los problemas que se derivan de ello, seguido de las ventajas de la capa de enmarcado binario de HTTP/2 y una descripción de cómo prioriza las peticiones.


		HTTP/1.1 - Pipelining y bloqueo de cabecera de línea (Head-of-Line Blocking):

			La primera respuesta que recibe un cliente en una petición HTTP GET no suele ser la página completa. 
			
			En su lugar, contiene enlaces a recursos adicionales necesarios para la página solicitada. 

			El cliente descubre que la representación completa de la página requiere estos recursos adicionales del servidor sólo después de descargar la página. 

			Por ello, el cliente tendrá que realizar peticiones adicionales para recuperar estos recursos. 

			En HTTP/1.0, el cliente tenía que romper y rehacer la conexión TCP con cada nueva petición, un asunto costoso tanto en tiempo como en recursos.

			HTTP/1.1 resuelve este problema introduciendo conexiones persistentes (persistent connections) y pipelining. 

			Con las conexiones persistentes, HTTP/1.1 asume que una conexión TCP debe mantenerse abierta a menos que se le indique directamente que la cierre. 

			Esto permite al cliente enviar múltiples peticiones a lo largo de la misma conexión sin esperar una respuesta a cada una, mejorando enormemente el rendimiento de HTTP/1.1 sobre HTTP/1.0.	





|| HTTP/3

		


