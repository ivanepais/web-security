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

		


