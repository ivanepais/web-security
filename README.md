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

		Desgraciadamente, esta estrategia de optimización tiene un cuello de botella natural. 

		Dado que varios paquetes de datos no pueden cruzarse entre sí cuando viajan al mismo destino, hay situaciones en las que una solicitud en la cabeza de la cola que no puede recuperar su recurso requerido bloqueará todas las solicitudes detrás de ella.

		Esto se conoce como bloqueo de la cabecera de la cola (HOL, head-of-line blocking), y es un problema importante a la hora de optimizar la eficiencia de la conexión en HTTP/1.1. 

		Añadir conexiones TCP separadas y paralelas podría aliviar este problema, pero hay límites al número de conexiones TCP simultáneas posibles entre un cliente y un servidor, y cada nueva conexión requiere recursos significativos.

		Estos problemas estaban en el punto de mira de los desarrolladores de HTTP/2, que propusieron utilizar la mencionada capa de entramado binario para solucionar estos problemas, un tema sobre el que aprenderás más en la siguiente sección.


	HTTP/2 - Ventajas de la capa de marco binario (Advantages of the Binary Framing Layer):

		En HTTP/2, la capa de marco binario codifica las solicitudes/respuestas y las divide en paquetes de información más pequeños, lo que aumenta enormemente la flexibilidad de la transferencia de datos.

		Veamos cómo funciona: A diferencia de HTTP/1.1, que debe hacer uso de múltiples conexiones TCP para disminuir el efecto del bloqueo HOL, HTTP/2 establece un único objeto de conexión entre las dos máquinas. 

		Dentro de esta conexión hay múltiples flujos de datos.

		Cada flujo se compone de varios mensajes en el conocido formato solicitud/respuesta. 

		Finalmente, cada uno de estos mensajes se divide en unidades más pequeñas llamadas tramas (frames).


		Diagrama de funcionamiento de HTTP/2: 

			En la conexión cliente/servidor vemos dos flujos con multiples mensajes. 

			Cada uno dividido por multiples frames. 


		En el nivel más granular, el canal de comunicación consiste en un montón de tramas codificadas en binario (binary-encoded frames), cada una etiquetada (tagged) a un flujo (stream) concreto. 

		Las etiquetas de identificación (identifying tags) permiten a la conexión intercalar estas tramas durante la transferencia y volver a ensamblarlas en el otro extremo.

		Las peticiones y respuestas intercaladas pueden ejecutarse en paralelo sin bloquear los mensajes que vienen detrás, un proceso llamado multiplexación (multiplexing). 

		La multiplexación resuelve el problema del bloqueo de cabecera en HTTP/1.1 al garantizar que ningún mensaje tenga que esperar a que otro termine. 

		Esto también significa que servidores y clientes pueden enviar peticiones y respuestas simultáneas, lo que permite un mayor control y una gestión más eficiente de la conexión.

		Dado que la multiplexación permite al cliente construir múltiples flujos en paralelo, estos flujos sólo necesitan hacer uso de una única conexión TCP. 

		Disponer de una única conexión persistente por origen mejora HTTP/1.1 al reducir la huella de memoria y procesamiento en toda la red. 

		Esto se traduce en una mejor utilización de la red y del ancho de banda y, por tanto, reduce el coste operativo global.

		Una única conexión TCP también mejora el rendimiento del protocolo HTTPS, ya que el cliente y el servidor pueden reutilizar la misma sesión segura para múltiples peticiones/respuestas. 

		En HTTPS, durante el handshake TLS o SSL, ambas partes acuerdan el uso de una única clave durante toda la sesión. 

		Si la conexión se interrumpe, se inicia una nueva sesión, que requiere una nueva clave generada para continuar la comunicación.

		Así, mantener una única conexión puede reducir en gran medida los recursos necesarios para el rendimiento de HTTPS. 

		Tenga en cuenta que, aunque las especificaciones HTTP/2 no obligan a utilizar la capa TLS, muchos de los principales navegadores sólo admiten HTTP/2 con HTTPS.

		Aunque la multiplexación inherente a la capa de entramado binario resuelve ciertos problemas de HTTP/1.1, los flujos múltiples que esperan el mismo recurso pueden seguir causando problemas de rendimiento. 

		El diseño de HTTP/2 tiene esto en cuenta, sin embargo, mediante el uso de la priorización de flujos, un tema que discutiremos en la siguiente sección.


	HTTP/2 - Priorización de flujos (Stream priorization):

		La priorización de flujos no sólo resuelve el posible problema de las solicitudes que compiten por el mismo recurso, sino que también permite a los desarrolladores personalizar el peso relativo de las solicitudes para optimizar mejor el rendimiento de la aplicación. 

		Como ya sabe, la capa de estructura binaria organiza los mensajes en flujos paralelos de datos. 

		Cuando un cliente envía peticiones concurrentes a un servidor, puede priorizar las respuestas que solicita asignando un peso entre 1 y 256 a cada flujo. 

		Cuanto mayor sea el número, mayor será la prioridad. 

		Además, el cliente también indica la dependencia de cada flujo respecto a otro especificando el identificador del flujo del que depende. 

		Si se omite el identificador del padre, se considera que el flujo depende del flujo raíz. 


		Diagrama de prioridad de flujo: 

			Vemos que el canal contiene seis flujos (stream), cada uno con un ID único y asociado a un peso específico. 

			El flujo 1 no tiene un ID padre asociado y está por defecto asociado al nodo raíz. 

			Todos los demás flujos tienen marcado algún ID padre. 

			La asignación de recursos para cada flujo se basará en el peso (weight/wt) que tengan y las dependencias que requieran.

			Los flujos 5 y 6, por ejemplo, que en la figura tienen asignado el mismo peso y el mismo flujo padre, tendrán la misma priorización para la asignación de recursos.


		El servidor utiliza esta información para crear un árbol de dependencias, que le permite determinar el orden en que las peticiones recuperarán sus datos.

		Basándose en los flujos de la figura anterior, diagrama del árbol (Binary Tree/Heap) de dependencia será el siguiente:

			En este árbol de dependencia, el flujo 1 depende del flujo raíz y no hay ningún otro flujo derivado del raíz, por lo que todos los recursos disponibles se asignarán al flujo 1 antes que a los demás flujos. 

			Dado que el árbol indica que el flujo 2 depende de la finalización del flujo 1, el flujo 2 no procederá hasta que la tarea del flujo 1 se haya completado. 

			Ahora, echemos un vistazo a los flujos 3 y 4. 

			Ambos dependen del flujo 2.

			Como en el caso del flujo 1, el flujo 2 obtendrá todos los recursos disponibles antes que los flujos 3 y 4. 

			Después de que el flujo 2 complete su tarea, el flujo 2 no procederá hasta que el flujo 1 haya completado su tarea. 

			Después de que el flujo 2 complete su tarea, los flujos 3 y 4 obtendrán los recursos; estos se dividen en la proporción de 2:4 como indican sus pesos, lo que resulta en una mayor parte de los recursos para el flujo 4.

			Por último, cuando el flujo 3 termine, los flujos 5 y 6 obtendrán los recursos disponibles a partes iguales.

			Esto puede ocurrir antes de que el flujo 4 haya terminado su tarea, incluso aunque el flujo 4 reciba una porción mayor de recursos; a los flujos de un nivel inferior se les permite comenzar tan pronto como los flujos dependientes de un nivel superior hayan terminado.

		
		Como desarrollador de aplicaciones, puedes establecer los pesos en tus peticiones en función de tus necesidades. 

		Por ejemplo, puede asignar una prioridad más baja para cargar una imagen con alta resolución después de proporcionar una imagen en miniatura en la página web. 

		Al proporcionar esta facilidad de asignación de pesos, HTTP/2 permite a los desarrolladores obtener un mejor control sobre el renderizado de las páginas web.

		El protocolo también permite al cliente cambiar dependencias y reasignar pesos en tiempo de ejecución en respuesta a la interacción del usuario. 

		No obstante, es importante señalar que un servidor puede cambiar por sí mismo las prioridades asignadas si se bloquea el acceso de un determinado flujo a un recurso específico.


	Desbordamiento del búfer/Buffer Overflow:

		En cualquier conexión TCP entre dos máquinas, tanto el cliente como el servidor disponen de una cierta cantidad de espacio en búfer para albergar las peticiones entrantes que aún no han sido procesadas. 

		Estos búferes ofrecen flexibilidad para tener en cuenta peticiones numerosas o particularmente grandes, además de las velocidades desiguales de las conexiones descendentes y ascendentes.

		Sin embargo, hay situaciones en las que un búfer no es suficiente. 

		Por ejemplo, el servidor puede estar enviando una gran cantidad de datos a un ritmo que la aplicación cliente no es capaz de soportar debido a un tamaño limitado del búfer o a un ancho de banda menor. 

		Del mismo modo, cuando un cliente sube una imagen o un vídeo enorme a un servidor, el búfer del servidor puede desbordarse, provocando la pérdida de algunos paquetes adicionales.

		Para evitar el desbordamiento del búfer, un mecanismo de control de flujo debe impedir que el emisor sature de datos al receptor. 

		Esta sección proporcionará una visión general de cómo HTTP/1.1 y HTTP/2 utilizan diferentes versiones de este mecanismo para tratar el control de flujo de acuerdo con sus diferentes modelos de entrega.


	HTTP/1.1 - Flow control:

		En HTTP/1.1, el control de flujo (flow control) depende de la conexión TCP subyacente. 

		Cuando se inicia esta conexión, tanto el cliente como el servidor establecen el tamaño de sus búferes utilizando la configuración predeterminada del sistema. 

		Si el búfer del receptor está parcialmente lleno de datos, indicará al emisor su ventana de recepción, es decir, la cantidad de espacio disponible que queda en su búfer. 

		Esta ventana de recepción se anuncia en una señal conocida como paquete ACK, que es el paquete de datos que envía el receptor para confirmar que ha recibido la señal de apertura. 

		Si este tamaño de ventana de recepción anunciado es cero, el emisor no enviará más datos hasta que el cliente vacíe su búfer interno y solicite reanudar la transmisión de datos. 

		Es importante señalar aquí que el uso de ventanas de recepción basadas en la conexión TCP subyacente sólo puede implementar el control de flujo en cualquiera de los extremos de la conexión.

		Dado que HTTP/1.1 se basa en la capa de transporte para evitar el desbordamiento del búfer, cada nueva conexión TCP requiere un mecanismo de control de flujo independiente. 

		HTTP/2, sin embargo, multiplexa flujos dentro de una única conexión TCP, y tendrá que implementar el control de flujo de una manera diferente.


	HTTP/2 - Flow control: 

		HTTP/2 multiplexa flujos de datos dentro de una única conexión TCP.

		Como resultado, las ventanas de recepción a nivel de la conexión TCP no son suficientes para regular la entrega de flujos individuales. 

		HTTP/2 resuelve este problema permitiendo al cliente y al servidor implementar sus propios controles de flujo, en lugar de depender de la capa de transporte. 

		La capa de aplicación comunica el espacio de búfer disponible, lo que permite al cliente y al servidor establecer la ventana de recepción a nivel de los flujos multiplexados. 

		Este control de flujo a escala fina puede modificarse o mantenerse después de la conexión inicial mediante una trama (frame) WINDOW_UPDATE.

		Dado que este método controla el flujo de datos a nivel de la capa de aplicación, el mecanismo de control de flujo no tiene que esperar a que una señal llegue a su destino final antes de ajustar la ventana de recepción. 

		Los nodos intermediarios pueden utilizar la información de los ajustes de control de flujo para determinar sus propias asignaciones de recursos y modificarlas en consecuencia. 

		De este modo, cada servidor intermediario puede aplicar su propia estrategia de recursos personalizada, lo que permite una mayor eficiencia de la conexión.		
		Esta flexibilidad en el control de flujo puede ser ventajosa a la hora de crear estrategias de recursos adecuadas. 

		Por ejemplo, el cliente puede recuperar la primera parte de una imagen, mostrársela al usuario y permitirle previsualizarla mientras obtiene recursos más importantes. 

		Una vez que el cliente obtiene estos recursos críticos, el navegador reanuda la recuperación de la parte restante de la imagen. 

		Aplazar la implementación del control de flujo al cliente y al servidor puede mejorar el rendimiento percibido de las aplicaciones web.

		En cuanto al control de flujo y la priorización de flujos mencionada en una sección anterior, HTTP/2 proporciona un nivel de control más detallado que abre la posibilidad de una mayor optimización. 

		La siguiente sección explicará otro método exclusivo del protocolo que puede mejorar una conexión de forma similar: la predicción de solicitudes de recursos con push del servidor


	Predicción de solicitudes de recursos/Predicting Resource Requests:

		En una aplicación web típica, el cliente envía una petición GET y recibe una página en HTML, normalmente la página índice del sitio. 

		Mientras examina el contenido de la página índice, el cliente puede descubrir que necesita obtener recursos adicionales, como archivos CSS y JavaScript, para renderizar completamente la página. 

		El cliente determina que necesita estos recursos adicionales sólo después de recibir la respuesta de su petición GET inicial y, por tanto, debe realizar peticiones adicionales para obtener estos recursos y completar la composición de la página. 

		En última instancia, estas peticiones adicionales aumentan el tiempo de carga de la conexión.

		Sin embargo, este problema tiene solución: como el servidor sabe de antemano que el cliente necesitará archivos adicionales, puede ahorrarle tiempo enviándole estos recursos antes de que los solicite. 

		HTTP/1.1 y HTTP/2 tienen diferentes estrategias para lograr esto, cada una de las cuales se describirá en la siguiente sección.


	HTTP/1.1 - Inclusión de recursos (Resource Inlining):

		En HTTP/1.1, si el desarrollador sabe de antemano qué recursos adicionales necesitará la máquina cliente para renderizar la página, puede utilizar una técnica llamada inlining de recursos para incluir el recurso necesario directamente dentro del documento HTML que el servidor envía en respuesta a la petición GET inicial. 

		Por ejemplo, si un cliente necesita un archivo CSS específico para renderizar una página, la inclusión de ese archivo CSS proporcionará al cliente el recurso necesario antes de que lo solicite, reduciendo el número total de peticiones que el cliente debe enviar.

		Sin embargo, la incrustación de recursos plantea algunos problemas. 

		Incluir el recurso en el documento HTML es una solución viable para los recursos más pequeños, basados en texto, pero los archivos más grandes en formatos no textuales pueden aumentar enormemente el tamaño del documento HTML, lo que en última instancia puede disminuir la velocidad de conexión y anular la ventaja original obtenida con el uso de esta técnica.

		Además, como los recursos en línea ya no están separados del documento HTML, no existe ningún mecanismo para que el cliente rechace recursos que ya tiene, o para colocar un recurso en su caché. 

		Si varias páginas necesitan el recurso, cada nuevo documento HTML tendrá el mismo recurso incrustado en su código, lo que provocará documentos HTML más grandes y tiempos de carga más largos que si el recurso se hubiera guardado en caché al principio.

		Uno de los principales inconvenientes de la inserción de recursos es que el cliente no puede separar el recurso del documento. 

		Se necesita un nivel de control más fino para optimizar la conexión, una necesidad que HTTP/2 trata de satisfacer con server push.


	HTTP/2 - Server Push

		Dado que HTTP/2 permite múltiples respuestas concurrentes a la petición GET inicial de un cliente, un servidor puede enviar un recurso a un cliente junto con la página HTML solicitada, proporcionando el recurso antes de que el cliente lo pida. 

		Este proceso se denomina server push. 

		De este modo, una conexión HTTP/2 puede lograr el mismo objetivo de inlining de recursos manteniendo la separación entre el recurso empujado y el documento. 

		Esto significa que el cliente puede decidir almacenar en caché o rechazar el recurso empujado separado del documento HTML principal, solucionando el principal inconveniente del inlining de recursos.

		En HTTP/2, este proceso comienza cuando el servidor envía una trama (frame) PUSH_PROMISE para informar al cliente de que va a enviar un recurso. 

		Este frame sólo incluye la cabecera del mensaje y permite al cliente saber de antemano qué recurso va a enviar el servidor.

		Si ya tiene el recurso en caché, el cliente puede rechazar el envío enviando una trama RST_STREAM como respuesta. 

		La trama PUSH_PROMISE también evita que el cliente envíe una solicitud duplicada al servidor, ya que sabe qué recursos va a enviar el servidor.

		Es importante señalar aquí que el énfasis de server push es el control del cliente. 

		Si un cliente necesitara ajustar la prioridad de server push, o incluso desactivarla, podría en cualquier momento enviar una trama SETTINGS para modificar esta característica de HTTP/2.

		Aunque esta característica tiene mucho potencial, server push no es siempre la respuesta para optimizar tu aplicación web. 

		Por ejemplo, algunos navegadores web no siempre pueden cancelar las peticiones push, incluso si el cliente ya tiene el recurso en caché. 

		Si el cliente permite por error que el servidor envíe un recurso duplicado, el push de servidor puede consumir la conexión innecesariamente. 

		En definitiva, el push de servidor debe utilizarse a discreción del desarrollador.

		Para más información sobre cómo utilizar estratégicamente el push de servidor y optimizar las aplicaciones web, consulta el patrón PRPL desarrollado por Google. 

		Para obtener más información sobre los posibles problemas del push de servidor, consulte la entrada del blog de Jake Archibald HTTP/2 push es más difícil de lo que pensaba.		


	Compresión/Compression

		Un método habitual para optimizar las aplicaciones web es utilizar algoritmos de compresión para reducir el tamaño de los mensajes HTTP que viajan entre el cliente y el servidor. 

		Tanto HTTP/1.1 como HTTP/2 utilizan esta estrategia, pero existen problemas de implementación en el primero que impiden comprimir todo el mensaje.


		HTTP/1.1:

			Hace tiempo que se utilizan programas como gzip para comprimir los datos enviados en mensajes HTTP, especialmente para reducir el tamaño de los archivos CSS y JavaScript. 

			Sin embargo, el componente de cabecera de un mensaje siempre se envía como texto sin formato.

			Aunque cada cabecera es bastante pequeña, la carga de estos datos sin comprimir pesa cada vez más en la conexión a medida que se realizan más peticiones, lo que penaliza especialmente a las aplicaciones web complicadas y con muchas API que requieren muchos recursos diferentes y, por tanto, muchas peticiones de recursos diferentes. 

			Además, el uso de cookies a veces puede hacer que las cabeceras sean mucho más grandes, lo que aumenta la necesidad de algún tipo de compresión.

			Para resolver este cuello de botella, HTTP/2 utiliza la compresión HPACK para reducir el tamaño de las cabeceras, un tema que se trata con más detalle en la siguiente sección.


		HTTP/2:

			Uno de los temas que ha surgido una y otra vez en HTTP/2 es su capacidad de utilizar la capa de marco binario para exhibir un mayor control sobre los detalles más finos. 

			Lo mismo ocurre con la compresión de cabeceras.

			HTTP/2 puede separar las cabeceras de sus datos, dando lugar a un marco de cabecera y un marco de datos. 

			El programa de compresión HPACK, específico de HTTP/2, puede comprimir este marco de encabezado. 

			Este algoritmo puede codificar los metadatos de la cabecera utilizando la codificación Huffman, lo que reduce enormemente su tamaño.

			Además, HPACK puede realizar un seguimiento de los campos de metadatos transmitidos previamente y comprimirlos aún más según un índice modificado dinámicamente y compartido entre el cliente y el servidor. 

			Por ejemplo, tomemos las dos peticiones siguientes:		

			Request #1: 

				method:		GET
				scheme:		https
				host:		example.com
				path:		/academy
				accept:		/image/jpeg
				user-agent:	Mozilla/5.0 ...


			Request #2: 

				method:		GET
				scheme:		https
				host:		example.com
				path:		/academy/images
				accept:		/image/jpeg
				user-agent:	Mozilla/5.0 ...


			Los distintos campos de estas peticiones, como method, scheme, host, accept y user-agent, tienen los mismos valores; sólo el campo path utiliza un valor diferente.

			Como resultado, al enviar la petición #2, el cliente puede usar HPACK para enviar sólo los valores indexados necesarios para reconstruir estos campos comunes y codificar de nuevo el campo path. 

			Las tramas de cabecera resultantes serán las siguientes:

			Header Frame for Request #1: 

				method:		GET
				scheme:		https
				host:		example.com
				path:		/academy
				accept:		/image/jpeg
				user-agent:	Mozilla/5.0 ...


			Header Frame for Request #1:

				path:		/academy/images


			Mediante HPACK y otros métodos de compresión, HTTP/2 ofrece una función más que puede reducir la latencia cliente-servidor.




|| HTTP/3
	
	Como HTTP/2, HTTP/3 tiene algunos conceptos nuevos y prometedores, lamentablemente su impacto será relativamente limitado para la mayoría de páginas web y usuarios (aunque potencialmente crucial para un pequeño subconjunto). 

	El impacto de HTTP/2 no fue como lo esperaban, el server push no funciona realmente en la práctica, los flujos y la priorización suelen estar mal implementados y, en consecuencia, la agrupación (reducida) de recursos e incluso la fragmentación siguen siendo buenas prácticas en algunas situaciones.

	HTTP/3 también es bastante difícil de configurar y utilizar (correctamente), por lo que hay que tener cuidado al configurar el nuevo protocolo.


	La necesidad de HTTP/3: 

		En realidad no necesitábamos una nueva versión de HTTP en primer lugar, sino más bien una actualización del Protocolo de Control de Transmisión (TCP) subyacente.

		TCP es el protocolo principal que proporciona servicios cruciales como la fiabilidad y la entrega en orden a otros protocolos como HTTP. 

		También es una de las razones por las que podemos seguir utilizando Internet con muchos usuarios simultáneos, porque limita inteligentemente el uso del ancho de banda de cada usuario a su parte justa.


		Protocolos: 

			Cuando utilizas HTTP(S), en realidad estás utilizando varios protocolos además de HTTP al mismo tiempo. 

			Cada uno de los protocolos de esta "pila" tiene sus propias características y responsabilidades.

			Por ejemplo, mientras que HTTP se ocupa de las URL y de la interpretación de los datos.

			Transport Layer Security (TLS) garantiza la seguridad mediante el cifrado.

			TCP permite un transporte fiable de los datos mediante la retransmisión de los paquetes perdidos.

			El Protocolo de Internet (IP) encamina los paquetes de un extremo a otro a través de diferentes dispositivos intermedios (middleboxes).


		Esta "superposición" de protocolos se hace para facilitar la reutilización de sus funciones. 

		Los protocolos de capa superior (como HTTP) no tienen que volver a implementar funciones complejas (como el cifrado) porque los protocolos de capa inferior (como TLS) ya lo hacen por ellos. 

		Otro ejemplo: la mayoría de las aplicaciones de Internet utilizan TCP internamente para garantizar que todos sus datos se transmiten íntegramente. 

		Por este motivo, TCP es uno de los protocolos más utilizados y desplegados en Internet.


		Diagrama de pila de protocolos: 

			HTTP/2 y HTTP/3 comparten la semántica de HTTP y el protocolo IPv4/IPv6. 

			Se diferencian en las características que ofrece HTTP/3 con respecto a HTTP/2 y ofrece características adicionales en TLS/TCP.


		TCP ha sido la piedra angular de la Web durante décadas, pero empezó a mostrar su vejez a finales de la década de 2000. 

		Su sustituto previsto, un nuevo protocolo de transporte llamado QUIC, difiere lo suficiente de TCP en algunos aspectos clave como para que ejecutar HTTP/2 directamente sobre él sea muy difícil. 

		Por ello, HTTP/3 es una adaptación relativamente pequeña de HTTP/2 para hacerlo compatible con el nuevo protocolo QUIC, que incluye la mayoría de las nuevas características que entusiasman a la gente.

		QUIC es necesario porque TCP, que ha existido desde los primeros días de Internet, no se construyó realmente pensando en la máxima eficiencia. 

		Por ejemplo, TCP requiere un "apretón de manos" (Handshake) para establecer una nueva conexión.

		Esto se hace para garantizar que tanto el cliente como el servidor existen y que están dispuestos y son capaces de intercambiar datos. 

		Sin embargo, también requiere que se complete un viaje de ida y vuelta por toda la red antes de que se pueda hacer nada más en una conexión. 

		Si el cliente y el servidor están geográficamente distantes, cada tiempo de ida y vuelta (RTT) puede tardar más de 100 milisegundos, lo que provoca retrasos notables.

		Como segundo ejemplo, TCP ve todos los datos que transporta como un único "archivo" o flujo de bytes, aunque en realidad lo estemos utilizando para transferir varios archivos al mismo tiempo (por ejemplo, al descargar una página web compuesta por muchos recursos).

		En la práctica, esto significa que si se pierden paquetes TCP que contienen datos de un único archivo, todos los demás archivos también se retrasarán hasta que se recuperen esos paquetes.

		Es lo que se denomina bloqueo de cabecera de línea (HoL). 

		Aunque estas ineficiencias son bastante manejables en la práctica (de lo contrario, no habríamos estado utilizando TCP durante más de 30 años), afectan de forma notable a protocolos de nivel superior como HTTP.

		Con el tiempo, hemos intentado evolucionar y actualizar TCP para mejorar algunos de estos problemas e incluso introducir nuevas funciones de rendimiento.

		Por ejemplo, TCP Fast Open elimina la sobrecarga del "handshake" permitiendo a los protocolos de capa superior enviar datos desde el principio.

		Otra iniciativa se llama MultiPath TCP. 

		En este caso, la idea es que el teléfono móvil suele tener conexión Wi-Fi y móvil (4G), así que ¿por qué no utilizar ambas a la vez para aumentar el rendimiento y la robustez?

		No es terriblemente difícil implementar estas extensiones TCP. 

		Sin embargo, desplegarlas a escala de Internet es todo un reto. 

		Como TCP es tan popular, casi todos los dispositivos conectados tienen su propia implementación del protocolo a bordo. 

		Si estas implementaciones son demasiado antiguas, carecen de actualizaciones o presentan fallos, las extensiones no podrán utilizarse en la práctica. 

		Dicho de otro modo, todas las implementaciones deben conocer la extensión para que sea útil.

		Esto no supondría un gran problema si sólo habláramos de dispositivos de usuario final (como el ordenador o el servidor web), ya que pueden actualizarse manualmente con relativa facilidad. 

		Sin embargo, hay muchos otros dispositivos entre el cliente y el servidor que también tienen su propio código TCP (por ejemplo, cortafuegos (firewalls), balanceadores de carga (load balancers), enrutadores, servidores de caché, proxies, etc.).

		Estos middleboxes suelen ser más difíciles de actualizar y a veces más estrictos en lo que aceptan.

		Por ejemplo, si el dispositivo es un cortafuegos, puede estar configurado para bloquear todo el tráfico que contenga extensiones (desconocidas). 

		En la práctica, resulta que un enorme número de middleboxes activos hacen ciertas suposiciones sobre TCP que ya no se sostienen para las nuevas extensiones.

		En consecuencia, pueden pasar años o incluso más de una década antes de que se actualicen suficientes implementaciones (middlebox) de TCP para utilizar realmente las extensiones a gran escala. 

		Se podría decir que se ha vuelto prácticamente imposible evolucionar TCP.

		Como resultado, estaba claro que necesitaríamos un protocolo de sustitución de TCP, en lugar de una actualización directa, para resolver estos problemas. 

		Sin embargo, debido a la enorme complejidad de las características de TCP y sus diversas implementaciones, crear algo nuevo pero mejor desde cero sería una empresa monumental. 

		Por ello, a principios de 2010 se decidió posponer este trabajo.

		Al fin y al cabo, no sólo había problemas con TCP, sino también con HTTP/1.1. 

		Optamos por dividir el trabajo y "arreglar" primero HTTP/1.1, dando lugar a lo que ahora es HTTP/2. 

		Una vez hecho esto, el trabajo podría continuar. 

		Una vez hecho esto, se pudo empezar a trabajar en el sustituto de TCP, que ahora es QUIC. 

		Originalmente, esperábamos poder ejecutar HTTP/2 sobre QUIC directamente, pero en la práctica esto haría que las implementaciones fueran demasiado ineficientes (principalmente debido a la duplicación de funciones).

		En su lugar, HTTP/2 se ajustó en algunas áreas clave para hacerlo compatible con QUIC. 

		Esta versión modificada recibió finalmente el nombre de HTTP/3 (en lugar de HTTP/2-sobre-QUIC), principalmente por razones de marketing y claridad. 

		Por ello, las diferencias entre HTTP/1.1 y HTTP/2 son mucho más sustanciales que las que existen entre HTTP/2 y HTTP/3.


	Las claves: 

		La clave es que lo que necesitábamos no era HTTP/3, sino "TCP/2", y que hemos conseguido HTTP/3 "gratis" en el proceso.

		Las principales características que nos entusiasman de HTTP/3 (establecimiento más rápido de la conexión, menos bloqueo HoL, migración de la conexión, etc.) proceden en realidad de QUIC.


	¿Qué es QUIC?:

		Puede que te estés preguntando por qué importa esto. 

		¿A quién le importa si estas características están en HTTP/3 o en QUIC? Creo que esto es importante, porque QUIC es un protocolo de transporte genérico que, al igual que TCP, puede y será utilizado para muchos casos de uso además de HTTP y la carga de páginas web. 

		Por ejemplo, DNS, SSH, SMB, RTP, etc. pueden ejecutarse sobre QUIC. 

		Como tal, vamos a ver QUIC un poco más en profundidad, porque es aquí donde la mayoría de los conceptos erróneos acerca de HTTP/3 que he leído vienen.

		Una cosa que puede que hayas oído es que QUIC se ejecuta sobre otro protocolo, llamado Protocolo de Datagramas de Usuario (UDP). 

		Esto es cierto, pero no por las razones (de rendimiento) que muchos afirman. 

		Lo ideal habría sido que QUIC fuera un nuevo protocolo de transporte totalmente independiente, que se ejecutara directamente sobre IP en la pila de protocolos que se muestra en la imagen que he compartido más arriba.

		Sin embargo, esto habría provocado el mismo problema que nos encontramos al intentar evolucionar TCP: primero habría que actualizar todos los dispositivos de Internet para que reconocieran y permitieran QUIC.

		Por suerte, podemos construir QUIC sobre el otro protocolo de capa de transporte ampliamente soportado en Internet: UDP.


		UDP: 

			UDP es el protocolo de transporte más básico posible.

			En realidad, no ofrece ninguna característica, aparte de los llamados números de puerto (por ejemplo, HTTP utiliza el puerto 80, HTTPS está en el 443 y DNS emplea el puerto 53). 

			No establece una conexión con un apretón de manos, ni es fiable: Si se pierde un paquete UDP, no se retransmite automáticamente. 

			El enfoque de "mejor esfuerzo" de UDP significa que es lo más eficaz que se puede conseguir: No hay necesidad de esperar al apretón de manos y no hay bloqueo HoL. 

			En la práctica, UDP se utiliza sobre todo para tráfico en directo que se actualiza a gran velocidad y, por tanto, sufre poco la pérdida de paquetes, ya que los datos que faltan quedan rápidamente obsoletos (por ejemplo, videoconferencias y juegos en directo).

			También es útil para casos en los que se necesita un retardo inicial bajo; por ejemplo, las búsquedas de nombres de dominio DNS sólo deberían tardar un viaje de ida y vuelta en completarse.


		Muchas fuentes afirman que HTTP/3 se construye sobre UDP por motivos de rendimiento. 

		Dicen que HTTP/3 es más rápido porque, al igual que UDP, no establece una conexión y no espera retransmisiones de paquetes. 

		Estas afirmaciones son erróneas.

		Como hemos dicho antes, UDP es utilizado por QUIC y, por tanto, HTTP/3 principalmente porque se espera que facilite su despliegue, porque ya es conocido e implementado por (casi) todos los dispositivos de Internet.

		Además de UDP, QUIC esencialmente reimplementa casi todas las características que hacen de TCP un protocolo tan potente y popular (aunque algo más lento).

		QUIC es absolutamente fiable, utilizando acuses de recibo para los paquetes recibidos y retransmisiones para asegurarse de que los perdidos siguen llegando. 

		QUIC también sigue estableciendo una conexión y tiene un handshake muy complejo.

		Por último, QUIC también utiliza los llamados mecanismos de control de flujo y de congestión que evitan que un emisor sobrecargue la red o el receptor, pero que también hacen que TCP sea más lento que lo que se podría hacer con UDP sin procesar. 

		La clave está en que QUIC implementa estas funciones de una forma más inteligente y eficaz que TCP. 

		Combina décadas de experiencia en el despliegue y las mejores prácticas de TCP con algunas nuevas características fundamentales. 

		Discutiremos estas características en mayor profundidad más adelante en este artículo.


	Claves: 	

		La clave es que no hay nada gratis. 

		HTTP/3 no es mágicamente más rápido que HTTP/2 sólo porque hayamos cambiado TCP por UDP. 

		En su lugar, hemos reimaginado e implementado una versión mucho más avanzada de TCP y la hemos llamado QUIC. 

		Y como queremos que QUIC sea más fácil de desplegar, lo ejecutamos sobre UDP.


	Grandes cambios: 

		Entonces, ¿en qué mejora exactamente QUIC a TCP? 

		¿Qué es tan diferente? 

		Hay varias características y oportunidades nuevas y concretas en QUIC (datos 0-RTT, migración de conexiones, más resistencia a la pérdida de paquetes y a las redes lentas) que trataremos en detalle en la siguiente parte de la serie.

		Sin embargo, todas estas novedades se reducen básicamente a cuatro cambios principales:

		    QUIC se integra profundamente con TLS.

		    QUIC soporta múltiples flujos de bytes independientes.

		    QUIC utiliza IDs de conexión.

		    QUIC utiliza tramas.

		Echemos un vistazo más de cerca a cada uno de estos puntos.


	No Hay QUIC Sin TLS:

		Como ya hemos mencionado, TLS (el protocolo Transport Layer Security) se encarga de asegurar y encriptar los datos enviados a través de Internet. 

		Cuando usas HTTPS, tus datos HTTP en texto plano son primero encriptados por TLS, antes de ser transportados por TCP.


		TLS: 

			Los detalles técnicos de TLS, por suerte, no son realmente necesarios aquí; sólo necesitas saber que el cifrado se realiza utilizando algunas matemáticas bastante avanzadas y números (primos) muy grandes. 

			Estos parámetros matemáticos se negocian entre el cliente y el servidor durante un protocolo criptográfico específico de TLS. 

			Al igual que el protocolo TCP, esta negociación puede llevar algún tiempo. 

			En las versiones más antiguas de TLS (por ejemplo, la versión 1.2 e inferiores), esto suele llevar dos viajes de ida y vuelta por la red.

			Por suerte, las versiones más recientes de TLS (la 1.3 es la última) reducen este tiempo a un solo viaje de ida y vuelta. 

			Esto se debe principalmente a que TLS 1.3 limita severamente los diferentes algoritmos matemáticos que se pueden negociar a sólo un puñado (los más seguros).

			Esto significa que el cliente puede adivinar inmediatamente cuáles soportará el servidor, en lugar de tener que esperar a una lista explícita, lo que ahorra un viaje de ida y vuelta.


		Diagrama de duración TLS ,TCP y QUIC handshake: 	

			La interacción o intercambio de información entre el cliente/servidor se reducen significativamente en QUIC, TLS 1.3 y HTTP/3. 

			TCP, TLS 1.2 y HTTP/2 son los que más tardan. 

			En el medio se encuentra, TCP, TLS 1.3 y HTTP/2


		En los primeros tiempos de Internet, cifrar el tráfico era bastante costoso en términos de procesamiento.

		Además, no se consideraba necesario para todos los casos de uso.

		Históricamente, TLS ha sido un protocolo independiente que puede utilizarse opcionalmente sobre TCP.

		Por eso distinguimos entre HTTP (sin TLS) y HTTPS (con TLS).

		Con el tiempo, nuestra actitud hacia la seguridad en Internet ha cambiado, por supuesto, a "seguro por defecto".

		Por ello, aunque HTTP/2 puede, en teoría, ejecutarse directamente sobre TCP sin TLS (e incluso se define en la especificación RFC como HTTP/2 en texto claro (cleartext mode)), ningún navegador web (popular) soporta realmente este modo.

		En cierto modo, los fabricantes de navegadores han optado conscientemente por una mayor seguridad a costa del rendimiento.

		Dada esta clara evolución hacia TLS siempre activo (especialmente para el tráfico web), no es de extrañar que los diseñadores de QUIC decidieran llevar esta tendencia al siguiente nivel. 

		En lugar de simplemente no definir un modo de texto claro (cleartext mode) para HTTP/3, optaron por integrar el cifrado profundamente en el propio QUIC.

		Mientras que las primeras versiones específicas de Google de QUIC utilizaban una configuración personalizada para esto, QUIC estandarizado utiliza directamente el TLS 1.3 existente.

		Para ello, rompe en cierto modo la típica separación limpia entre protocolos en la pila de protocolos, como podemos ver en la imagen anterior. 

		Mientras que TLS 1.3 puede ejecutarse independientemente sobre TCP, QUIC encapsula TLS 1.3. 

		Dicho de otro modo, no hay forma de utilizar QUIC sin TLS. 

		Dicho de otro modo, no hay forma de utilizar QUIC sin TLS; QUIC (y, por extensión, HTTP/3) siempre está totalmente cifrado. 

		Además, QUIC encripta casi todos los campos de la cabecera del paquete también; la información de la capa de transporte (como los números de paquete, que nunca están encriptados para TCP) ya no es legible por intermediarios en QUIC (incluso algunas de las banderas de la cabecera del paquete están encriptadas).


		Diagrama interno de TCP: 

			A diferencia de TCP + TLS, QUIC también cifra los metadatos de la capa de transporte en la cabecera y la carga útil del paquete.	


		Para ello, QUIC utiliza primero el protocolo TLS 1.3 más o menos como lo haría con TCP para establecer los parámetros matemáticos de cifrado. 

		Después, sin embargo, QUIC toma el relevo y cifra los paquetes por sí mismo, mientras que con TLS-sobre-TCP, TLS realiza su propia encriptación. 

		Esta diferencia aparentemente pequeña representa un cambio conceptual fundamental hacia el cifrado permanente que se aplica en capas de protocolo cada vez más bajas.


		Este enfoque proporciona a QUIC varias ventajas:

		    QUIC es más seguro para sus usuarios.

		    No hay forma de ejecutar QUIC en texto claro, por lo que también hay menos opciones de escucha para atacantes y fisgones (attackers and eavesdroppers). 

		    (Investigaciones recientes han demostrado lo peligrosa que puede ser la opción de texto en claro de HTTP/2).

		    La conexión QUIC es más rápida.

		    Mientras que para TLS-sobre-TCP, ambos protocolos necesitan sus propios handshakes separados, QUIC combina el transporte y el handshake criptográfico en uno, ahorrando un viaje de ida y vuelta (ver imagen superior). 

		    Hablaremos de esto con más detalle en la segunda parte.

		    QUIC puede evolucionar más fácilmente.

		    Al estar totalmente encriptado, los intermediarios de la red ya no pueden observar e interpretar su funcionamiento interno, como ocurre con TCP.

		    Consecuentemente, ellos tampoco pueden romper (accidentalmente) en nuevas versiones de QUIC porque fallaron en la actualización.

		    Si queremos añadir nuevas características a QUIC en el futuro, "sólo" tenemos que actualizar los dispositivos finales, en lugar de todos los middleboxes también.


		Junto a estas ventajas, sin embargo, también hay algunas desventajas potenciales del cifrado extensivo:

		    Muchas redes dudarán en permitir QUIC.

		    Es posible que las empresas quieran bloquearlo en sus cortafuegos, porque se hace más difícil detectar el tráfico no deseado. 

		    Los ISP y las redes intermedias podrían bloquearlo porque métricas como los retrasos medios y los porcentajes de pérdida de paquetes ya no están fácilmente disponibles, lo que dificulta la detección y el diagnóstico de problemas.

		    Todo esto significa que QUIC probablemente nunca estará disponible de forma universal, algo de lo que hablaremos en la parte 3.

		    QUIC tiene una mayor sobrecarga de encriptación.

		    QUIC encripta cada paquete individual con TLS, mientras que TLS-sobre-TCP puede encriptar varios paquetes al mismo tiempo. 

		    Esto potencialmente hace QUIC más lento para escenarios de alto rendimiento (como veremos en la parte 2).

		    QUIC hace la web más centralizada.

		    Una queja que he encontrado a menudo es algo así como, "QUIC está siendo impulsado por Google, ya que les da acceso completo a los datos, mientras que no comparten nada de eso con los demás".

		    No estoy de acuerdo. En primer lugar, QUIC no oculta más (¡o menos!) información a nivel de usuario (por ejemplo, qué URLs estás visitando) a observadores externos que TLS-sobre-TCP (QUIC mantiene el status quo).


		En segundo lugar, aunque Google inició el proyecto QUIC, los protocolos finales de los que hablamos hoy fueron diseñados por un equipo mucho más amplio en el Grupo de Trabajo de Ingeniería de Internet (IETF). 

		El QUIC del IETF es técnicamente muy diferente del QUIC de Google.

		Aun así, es cierto que la gente del IETF procede en su mayoría de grandes empresas como Google y Facebook y de CDN como Cloudflare y Fastly. 

		Debido a la complejidad de QUIC, serán principalmente esas empresas las que tengan los conocimientos necesarios para desplegar correctamente y con rendimiento, por ejemplo, HTTP/3 en la práctica. 

		Esto conducirá probablemente a una mayor centralización en esas empresas, lo cual es realmente preocupante.


	Claves: 

		QUIC está profundamente encriptado por defecto. 

		Esto no sólo mejora sus características de seguridad y privacidad, sino que también ayuda a su capacidad de despliegue y evolución. 

		Hace que el protocolo sea un poco más pesado de ejecutar pero, a cambio, permite otras optimizaciones, como un establecimiento de conexión más rápido.


	QUIC entiende de múltiples flujos de bytes/QUIC Knows About Multiple Byte Streams: 

		La segunda gran diferencia entre TCP y QUIC es un poco más técnica, y exploraremos sus repercusiones con más detalle en la segunda parte. 

		Por ahora, sin embargo, podemos entender los aspectos principales a alto nivel.


    	Transmision de datos en la red: 

    		Considera en primer lugar que incluso una simple página web se compone de una serie de archivos y recursos independientes. 

    		Hay HTML, CSS, JavaScript, imágenes, etc. 

    		Cada uno de estos archivos puede verse como un simple "blob binario" (almacen de datos), una colección de ceros y unos que el navegador interpreta de una determinada manera. 

    		Al enviar estos archivos por la red, no los transferimos todos a la vez. 

    		En lugar de eso, se subdividen en trozos más pequeños (normalmente, de unos 1.400 bytes cada uno) y se envían en paquetes individuales. 

    		De este modo, podemos considerar cada recurso como un "flujo de bytes" independiente, ya que los datos se descargan o "transmiten" poco a poco a lo largo del tiempo.

		
		Para HTTP/1.1, el proceso de carga de recursos es bastante sencillo, ya que cada archivo recibe su propia conexión TCP y se descarga en su totalidad. 

		Por ejemplo, si tenemos los archivos A, B y C, tendríamos tres conexiones TCP. 

		La primera vería un flujo de bytes de AAAA, la segunda de BBBB, la tercera de CCCC (siendo cada repetición de letra un paquete TCP). 

		Esto funciona, pero también es muy ineficiente porque cada nueva conexión tiene cierta sobrecarga.

		En la práctica, los navegadores imponen límites al número de conexiones simultáneas que pueden utilizarse (y, por tanto, al número de archivos que pueden descargarse en paralelo): normalmente, entre 6 y 30 por carga de página. 

		Las conexiones se reutilizan para descargar un nuevo archivo una vez que el anterior se ha transferido por completo. 

		Estos límites empezaron a dificultar el rendimiento de las páginas modernas, que a menudo cargan muchos más de 30 recursos.

		Mejorar esta situación era uno de los principales objetivos de HTTP/2. 

		Para ello, el protocolo ya no abre una nueva conexión TCP para cada archivo, sino que descarga los distintos recursos a través de una única conexión TCP. 

		Esto se consigue "multiplexando" los distintos flujos de bytes. 

		Es una forma elegante de decir que mezclamos los datos de los distintos archivos al transportarlos. 

		Para nuestros tres archivos de ejemplo, tendríamos una única conexión TCP, y los datos entrantes podrían tener el aspecto AABBCCAABBCC (aunque son posibles muchos otros esquemas de ordenación). 

		Esto parece bastante sencillo y, de hecho, funciona bastante bien, haciendo que HTTP/2 sea normalmente tan rápido o un poco más que HTTP/1.1, pero con mucha menos sobrecarga.


		Diagrama de transferencia de archivos: 

			HTTP/1.1 no permite la multiplexación, a diferencia de HTTP/2 y HTTP/3.


		Sin embargo, hay un problema en el lado de TCP. 

		Verás, como TCP es un protocolo mucho más antiguo y no está hecho sólo para cargar páginas web, no sabe nada de A, B o C. 

		Internamente, TCP piensa que está transportando un único archivo, X, y no le importa que lo que ve como XXXXXXXXXXXXXX sea en realidad AABBCCAABBCC a nivel HTTP. 

		En la mayoría de las situaciones, esto no importa (¡y de hecho hace que TCP sea bastante flexible!), pero eso cambia cuando hay, por ejemplo, pérdida de paquetes en la red.

		Supongamos que se pierde el tercer paquete TCP (el que contiene los primeros datos del fichero B), pero se entregan todos los demás datos. 

		TCP soluciona esta pérdida retransmitiendo una nueva copia de los datos perdidos en un nuevo paquete. 

		Sin embargo, esta retransmisión puede tardar en llegar (al menos un RTT (un milisegundo en tiempo de ida y vuelta de respuesta en solicitud)).

		Podríamos pensar que no es un gran problema, ya que vemos que no hay pérdida para los recursos A y C. 

		Por tanto, podemos empezar a procesarlos mientras esperamos los datos perdidos de B, ¿verdad?.

		Desgraciadamente, no es así, porque la lógica de retransmisión ocurre en la capa TCP, ¡y TCP no sabe nada de A, B y C!. 

		En su lugar, TCP piensa que se ha perdido una parte del único archivo X, y por lo tanto siente que tiene que evitar que el resto de los datos de X se procesen hasta que se llene el agujero.

		Dicho de otro modo, mientras que a nivel de HTTP/2 sabemos que ya podríamos procesar A y C, TCP no lo sabe, lo que provoca que las cosas sean más lentas de lo que potencialmente podrían ser. 

		Esta ineficiencia es un ejemplo del problema de "bloqueo de cabecera de línea (HoL)" 

		Uno de los principales objetivos de QUIC era resolver el bloqueo HoL en la capa de transporte. 

		A diferencia de TCP, QUIC es plenamente consciente de que está multiplexando múltiples flujos de bytes independientes. 

		Por supuesto, no sabe que está transportando CSS, JavaScript e imágenes; sólo sabe que los flujos están separados. 

		Como tal, QUIC puede realizar la detección de pérdida de paquetes y la lógica de recuperación en una base por flujo.

		En el escenario anterior, sólo retendría los datos del flujo B y, a diferencia de TCP, entregaría cualquier dato de A y C a la capa HTTP/3 lo antes posible. 

		En teoría, esto podría mejorar el rendimiento. 

		En la práctica, sin embargo, la historia tiene muchos más matices, como veremos en la parte 2.


		Diagrama de perdida de paquetes: 	

			Cuando ocurre una perdida de un paquete en HTTP/1.1 y HTTP/2 con TCP, los demás tienen que esperar a que se complete para poder ser transmitidos (Problema HOL). 

			En HTTP/3 o QUIC solo el paquete perdido que está perdido espera a trasmitirse. 

			QUIC permite a HTTP/3 eludir (bypass) el problema del bloqueo de cabecera de línea


		Podemos ver que ahora tenemos una diferencia fundamental entre TCP y QUIC. 

		Esta es, por cierto, también una de las principales razones por las que no podemos ejecutar HTTP/2 tal cual sobre QUIC. 

		Como hemos dicho, HTTP/2 también incluye el concepto de ejecutar múltiples flujos sobre una única conexión (TCP). 

		Como tal, HTTP/2 sobre QUIC tendría dos abstracciones de flujo diferentes y competidoras una encima de la otra.

		Hacer que funcionen bien juntos sería muy complejo y propenso a errores; por lo tanto, una de las diferencias clave entre HTTP/2 y HTTP/3 es que este último elimina la lógica de flujo HTTP y reutiliza los flujos QUIC en su lugar. 

		Sin embargo, como veremos en la parte 2, esto tiene otras repercusiones en cómo se implementan características como el push del servidor, la compresión de cabeceras y la priorización.


	Claves: 


		La clave es que TCP nunca se diseñó para transportar varios archivos independientes a través de una única conexión. 

		Dado que eso es exactamente lo que requiere la navegación web, esto ha dado lugar a muchas ineficiencias a lo largo de los años. 

		QUIC lo soluciona haciendo de los flujos múltiples de bytes un concepto central en la capa de transporte y gestionando la pérdida de paquetes por flujo.



	QUIC admite la migración de conexiones:

		La tercera gran mejora de QUIC es el hecho de que las conexiones pueden permanecer vivas durante más tiempo.

		Conexión: 

		    A menudo utilizamos el concepto de "conexión" cuando hablamos de protocolos web. 

		    Sin embargo, ¿qué es exactamente una conexión? Normalmente, se habla de una conexión TCP una vez que se ha producido un apretón de manos entre dos puntos finales (por ejemplo, el navegador o el cliente y el servidor). 

		    Por eso a menudo se dice (erróneamente) que UDP es "sin conexión", porque no hace ese "apretón de manos". 

		    Sin embargo, el apretón de manos no tiene nada de especial: son sólo unos paquetes con una forma específica que se envían y reciben. 

		    Tiene unos cuantos objetivos, el principal de los cuales es asegurarse de que hay algo al otro lado y de que está dispuesto y es capaz de hablar con nosotros. 

		    Vale la pena repetir aquí que QUIC también realiza un apretón de manos, a pesar de que se ejecuta sobre UDP, que por sí mismo no lo hace.


		Entonces, la pregunta es: ¿cómo llegan esos paquetes al destino correcto?. 

		En Internet, las direcciones IP se utilizan para enrutar paquetes entre dos máquinas únicas. 

		Sin embargo, no basta con tener las IP del teléfono y del servidor, porque ambos quieren poder ejecutar simultáneamente varios programas en red en cada extremo.

		Por eso, a cada conexión individual se le asigna también un número de puerto en ambos extremos para diferenciar las conexiones y las aplicaciones a las que pertenecen. 

		Las aplicaciones servidoras suelen tener un número de puerto fijo según su función (por ejemplo, los puertos 80 y 443 para HTTP(S), y el puerto 53 para DNS), mientras que los clientes suelen elegir sus números de puerto (semi)aleatoriamente para cada conexión.

		Así, para definir una conexión única entre máquinas y aplicaciones, necesitamos estas cuatro cosas, la llamada 4-tupla: dirección IP del cliente + puerto del cliente + dirección IP del servidor + puerto del servidor.

		En TCP, las conexiones se identifican sólo por la 4-tupla.

		Por tanto, si uno solo de esos cuatro parámetros cambia, la conexión deja de ser válida y debe restablecerse (incluyendo un nuevo apretón de manos). 

		Para entenderlo, imagina el problema del aparcamiento: estás utilizando tu smartphone dentro de un edificio con Wi-Fi. Como tal, tiene una dirección IP en esta red Wi-Fi.

		Si ahora sale al exterior, es posible que su teléfono cambie a la red celular 4G. 

		Como se trata de una nueva red, obtendrá una dirección IP completamente nueva, ya que éstas son específicas de la red. 

		Ahora, el servidor verá paquetes TCP procedentes de una IP de cliente que no ha visto antes (aunque los dos puertos y la IP del servidor podrían, por supuesto, seguir siendo los mismos). 

		Esto se ilustra a continuación.


		Diagrama de cambio de conexión cliente-servidor: 	

			El problema de cambio de conexión de red con TCP: una vez que el cliente obtiene una nueva IP, el servidor ya no puede vincularla a la conexión.


		Pero, ¿cómo puede saber el servidor que estos paquetes de una nueva IP pertenecen a la "conexión"?. 

		¿Cómo sabe que estos paquetes no pertenecen a una nueva conexión de otro cliente en la red celular que eligió el mismo puerto de cliente (aleatorio) (lo que puede ocurrir fácilmente)?.

		Lamentablemente, no puede saberlo.

		Dado que TCP se inventó antes de que soñáramos siquiera con redes celulares y smartphones, no existe, por ejemplo, ningún mecanismo que permita al cliente informar al servidor de que ha cambiado de IP. 

		Ni siquiera hay forma de "cerrar" la conexión, porque un comando TCP reset o fin enviado a la antigua 4-tupla ya no llegaría al cliente. 

		Por lo tanto, en la práctica, cada cambio en la red significa que las conexiones TCP existentes ya no se pueden utilizar.

		Hay que ejecutar un nuevo protocolo TCP (y posiblemente TLS) para establecer una nueva conexión y, dependiendo del protocolo de la aplicación, habrá que reiniciar las acciones del proceso. 

		Por ejemplo, si se estuviera descargando un archivo de gran tamaño a través de HTTP, podría ser necesario volver a solicitar ese archivo desde el principio (por ejemplo, si el servidor no admite solicitudes de rango).

		Otro ejemplo son las videoconferencias en directo, en las que puede producirse un breve apagón al cambiar de red.

		Ten en cuenta que hay otras razones por las que la 4-tupla puede cambiar (por ejemplo, NAT rebinding), que discutiremos más en la parte 2.

		Reiniciar las conexiones TCP puede tener un impacto severo (esperando nuevos handshakes, reiniciando descargas, restableciendo el contexto). 

		Para resolver este problema, QUIC introduce un nuevo concepto llamado identificador de conexión (CID). 

		A cada conexión se le asigna otro número además de la 4-tupla que la identifica de forma única entre dos puntos finales.

		Crucialmente, porque este CID está definido en la capa de transporte en QUIC, ¡no cambia cuando se mueve entre redes! Esto se muestra en el diagrama de abajo.

		Para hacer esto posible, el CID se incluye en la parte delantera de todos y cada uno de los paquetes QUIC (al igual que las direcciones IP y los puertos también están presentes en cada paquete). 

		(De hecho, es una de las pocas cosas en la cabecera del paquete QUIC que no están encriptadas).


		Diagrama de conexión HTTP/3 a cliente-servidor: 

			QUIC utiliza identificadores de conexión (CID) para permitir que las conexiones sobrevivan a un cambio de red.


		Con esta configuración, incluso cuando una de las cosas en la 4-tupla cambia, el servidor QUIC y el cliente sólo tienen que mirar el CID para saber que es la misma vieja conexión, y entonces pueden seguir utilizándola. 

		No hay necesidad de un nuevo handshake, y el estado de descarga puede mantenerse intacto. 

		Esta función suele denominarse migración de conexión. 

		Esto es, en teoría, mejor para el rendimiento, pero como discutiremos en la parte 2, es, por supuesto, una historia matizada de nuevo.

		Hay otros retos que superar con el CID. 

		Por ejemplo, si utilizáramos un único CID, a los hackers y fisgones les resultaría extremadamente fácil seguir a un usuario a través de las redes y, por extensión, deducir su ubicación física (aproximada).

		Para evitar esta pesadilla, QUIC cambia el CID cada vez que se utiliza una nueva red.

		Pero esto puede confundirte: ¿No acabo de decir que el CID debe ser el mismo en todas las redes?.

		Bueno, eso fue una simplificación excesiva. 

		Lo que realmente ocurre internamente es que el cliente y el servidor acuerdan una lista común de CID (generados aleatoriamente) que corresponden a la misma "conexión" conceptual.

		Por ejemplo, ambos saben que los CID K, C y D corresponden en realidad a la conexión X. 

		Así, mientras que el cliente puede etiquetar paquetes con K en Wi-Fi, puede pasar a utilizar C en 4G. 

		Estas listas comunes se negocian totalmente cifradas en QUIC, por lo que los posibles atacantes no sabrán que K y C son en realidad X, pero el cliente y el servidor sí lo sabrán y podrán mantener viva la conexión.


		Diagrama de multiples identificadores CIDs ( Connections Identifiers): 

			QUIC utiliza múltiples identificadores de conexión negociados (CID) para evitar el seguimiento de usuarios


		Se vuelve aún más complejo, porque los clientes y los servidores tendrán diferentes listas de CIDs que ellos mismos eligen (igual que tienen diferentes números de puerto).

		Esto es principalmente para ayudar con el enrutamiento y el equilibrio de carga en configuraciones de servidores a gran escala, como veremos con más detalle en la parte 3.


	Claves: 

		La clave es que, en TCP, las conexiones están definidas por cuatro parámetros que pueden cambiar cuando los extremos cambian de red. 

		Como tal, estas conexiones a veces necesitan ser reiniciadas, lo que lleva a un cierto tiempo de inactividad. 

		QUIC añade otro parámetro a la mezcla, llamado ID de conexión.

		Tanto el cliente como el servidor QUIC saben qué ID de conexión corresponden a qué conexiones y, por tanto, son más robustos frente a los cambios de red.


	QUIC es flexible y evolutivo:

		Un último aspecto de QUIC es que está hecho específicamente para ser fácil de evolucionar. 

		Esto se logra de varias maneras diferentes. 

		En primer lugar, como se ha discutido, el hecho de que QUIC esté casi totalmente encriptado significa que sólo tenemos que actualizar los puntos finales (clientes y servidores), y no todos los middleboxes, si queremos desplegar una nueva versión de QUIC. 

		Eso sigue llevando tiempo, pero normalmente del orden de meses, no años.

		En segundo lugar, a diferencia de TCP, QUIC no utiliza una única cabecera de paquete fija para enviar todos los metadatos del protocolo. 

		En su lugar, QUIC tiene cabeceras de paquete cortas y utiliza una variedad de "tramas" (algo así como paquetes especializados en miniatura) dentro de la carga útil del paquete para comunicar información adicional. 

		Hay, por ejemplo, una trama (frame) ACK (para acuses de recibo), una trama NEW_CONNECTION_ID (para ayudar a establecer la migración de la conexión), y una trama STREAM (para transportar datos), como se muestra en la imagen de abajo.

		Esto se hace principalmente como una optimización, porque no todos los paquetes llevan todos los metadatos posibles (y así la cabecera del paquete TCP suele desperdiciar bastantes bytes - ver también la imagen de arriba).

		Un efecto secundario muy útil de usar tramas, sin embargo, es que definir nuevos tipos de tramas como extensiones de QUIC será muy fácil en el futuro. 

		Una muy importante, por ejemplo, es la trama DATAGRAM, que permite enviar datos no fiables sobre una conexión QUIC encriptada.

		Esto se hace principalmente como una optimización, porque no todos los paquetes llevan todos los metadatos posibles (y así la cabecera del paquete TCP normalmente desperdicia bastantes bytes -como en el diagrama de arriba-). 

		Un efecto secundario muy útil de usar tramas, sin embargo, es que definir nuevos tipos de tramas como extensiones de QUIC será muy fácil en el futuro. 

		Una muy importante, por ejemplo, es la trama DATAGRAM, que permite enviar datos no fiables a través de una conexión QUIC encriptada.


		Diagrama de los componentes de transmisión en QUIC: 	

			QUIC utiliza tramas individuales para enviar metadatos, en lugar de una gran cabecera de paquete fija


		En tercer lugar, QUIC utiliza una extensión TLS personalizada para transportar lo que se denominan parámetros de transporte (transport parameters). 

		Estos permiten al cliente y al servidor elegir una configuración para una conexión QUIC. 

		Esto significa que pueden negociar qué características están habilitadas (por ejemplo, si se permite la migración de conexión, qué extensiones están soportadas, etc.) y comunicar valores por defecto sensibles para algunos mecanismos (por ejemplo, tamaño máximo de paquete soportado, límites de control de flujo). 

		Aunque el estándar QUIC define una larga lista de estos, también permite extensiones para definir otros nuevos, haciendo de nuevo el protocolo más flexible.

		Por último, aunque no es un requisito real de QUIC en sí mismo, la mayoría de las implementaciones se realizan actualmente en el "espacio de usuario" (a diferencia de TCP, que normalmente se realiza en el "espacio del núcleo"). 

		Los detalles se discuten en la parte 2, pero esto significa principalmente que es mucho más fácil experimentar y desplegar variaciones y extensiones de implementación de QUIC que de TCP.


	Claves: 	

		Aunque QUIC ya se ha estandarizado, en realidad debería considerarse como la versión 1 de QUIC (lo que también se indica claramente en la Request For Comments (RFC)), y hay una clara intención de crear la versión 2 y más con bastante rapidez.

		Además, QUIC permite definir extensiones con facilidad, por lo que se pueden implementar aún más casos de uso.


	Conclusiones: 

		Hemos hablado principalmente del omnipresente protocolo TCP y de cómo se diseñó en una época en la que se desconocían muchos de los retos actuales. 

		Al intentar evolucionar TCP para mantener el ritmo, quedó claro que esto sería difícil en la práctica, porque casi todos los dispositivos llevan a bordo su propia implementación de TCP que habría que actualizar.

		Para evitar este problema sin dejar de mejorar TCP, creamos el nuevo protocolo QUIC (que en realidad es TCP 2.0). 

		Para facilitar su despliegue, QUIC se ejecuta sobre el protocolo UDP (compatible con la mayoría de dispositivos de red) y, para garantizar su evolución futura, está casi totalmente encriptado por defecto y utiliza un mecanismo de encuadre flexible.

		Aparte de esto, QUIC refleja en su mayor parte las características conocidas de TCP, como el handshake, la fiabilidad y el control de congestión. 

		Los dos cambios principales, además del cifrado y la estructuración, son el reconocimiento de múltiples flujos de bytes y la introducción del identificador de conexión.

		Sin embargo, estos cambios fueron suficientes para impedirnos ejecutar HTTP/2 sobre QUIC directamente, por lo que fue necesario crear HTTP/3 (que en realidad es HTTP/2 sobre QUIC).

		El nuevo enfoque de QUIC da lugar a una serie de mejoras en el rendimiento, pero sus beneficios potenciales tienen más matices de los que se suelen comunicar en los artículos sobre QUIC y HTTP/3. 



|| Seguridad en la Web
	
	



