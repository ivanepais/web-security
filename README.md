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



|| Introducción a HTTP

	HTTP: 	

		El Protocolo de Transferencia de Hipertexto (HTTP) es la base de la World Wide Web y se utiliza para cargar páginas web mediante enlaces de hipertexto. 

		HTTP es un protocolo de capa de aplicación diseñado para transferir información entre dispositivos en red y se ejecuta sobre otras capas de la pila de protocolos de red. 

		Un flujo típico sobre HTTP implica que una máquina cliente haga una petición (request) a un servidor, que a su vez envía un mensaje de respuesta (response).


	HTTP Request: 

		Una petición HTTP es la forma en que las plataformas de comunicación de Internet, como los navegadores web, solicitan la información que necesitan para cargar un sitio web.

		Cada petición HTTP realizada a través de Internet lleva consigo una serie de datos codificados que contienen distintos tipos de información. 

		Una petición HTTP típica contiene:

		    un tipo de versión HTTP.

		    una URL.

		    un método HTTP.

		    headers de petición HTTP.

		    cuerpo HTTP opcional.


	HTTP Method: 

		Un método HTTP, a veces denominado verbo HTTP, indica la acción que la petición HTTP espera del servidor consultado.

		Por ejemplo, dos de los métodos HTTP más comunes son 'GET' y 'POST'.

		Una petición 'GET' espera información a cambio (normalmente en forma de sitio web). 

		Una petición 'POST' indica normalmente que el cliente está enviando información al servidor web (como información de un formulario, por ejemplo, un nombre de usuario y una contraseña enviados).


	HTTP Request Headers: 

		Las cabeceras HTTP contienen información de texto almacenada en pares clave-valor, y se incluyen en todas las peticiones HTTP (y respuestas, más adelante). 

		Estas cabeceras comunican información básica, como qué navegador está utilizando el cliente y qué datos se están solicitando.

		Ejemplo de cabeceras de solicitud HTTP en información red del navegador: 

			:authority: www.google.com

			:method: GET

			:path: /

			:scheme: https

			accept: text/html

			accept-encoding: gzip, deflate, br 

			accept-lenguage: en-US,en;q=0.9

			upgrade-insecure-request: 1

			user-agent: Mozilla/5.0


	HTTP Request Body:

		El cuerpo de una solicitud es la parte que contiene el "cuerpo" de la información que la solicitud está transfiriendo. 

		El cuerpo de una petición HTTP contiene toda la información que se envía al servidor web, como un nombre de usuario y una contraseña, o cualquier otro dato introducido en un formulario.

	
	HTTP Response: 

		Una respuesta HTTP es lo que los clientes web (a menudo los navegadores) reciben de un servidor de Internet en respuesta a una solicitud HTTP. 

		Estas respuestas comunican información valiosa basada en lo que se pidió en la solicitud HTTP.

		Una respuesta HTTP típica contiene:

	    	un código de estado HTTP ( status code).

	    	cabeceras de respuesta HTTP (response headers).

	    	cuerpo HTTP opcional (optional body).

	    
	HTTP Status Code: 

		Los códigos de estado HTTP son códigos de 3 dígitos que se suelen utilizar para indicar si una solicitud HTTP se ha completado correctamente. 

		Los códigos de estado se dividen en los 5 bloques siguientes:

		    1xx Informativo
		    2xx Éxito
		    3xx Redirección
		    4xx Error del cliente
		    5xx Error del servidor

	    Las "xx" se refieren a diferentes números entre 00 y 99.

	    Los códigos de estado que empiezan por el número "2" indican éxito. 

	    Por ejemplo, después de que un cliente solicite una página web, las respuestas más comunes tienen un código de estado '200 OK', lo que indica que la solicitud se ha completado correctamente.

	    Si la respuesta comienza con un '4' o un '5' significa que hubo un error y la página web no se mostrará. 

	    Un código de estado que empiece por '4' indica un error del lado del cliente (es muy común encontrarse con un código de estado '404 NOT FOUND' al cometer un error tipográfico en una URL). 

	    Un código de estado que empieza por '5' significa que algo ha ido mal en el lado del servidor. 

	    Los códigos de estado también pueden empezar por '1' o '3', que indican una respuesta informativa y una redirección, respectivamente.


	HTTP Response Headers:

		Al igual que una solicitud HTTP, una respuesta HTTP viene con cabeceras que transmiten información importante como el idioma y el formato de los datos que se envían en el cuerpo de la respuesta.

		Ejemplo de cabecera de respuesta HTTP de la pestaña de información de red del navegador:

			cache-control: private, max-age=0

			content-encodign: br

			content-type: text/html; charset=UTF-8 

			date: thu, 21 dec 2017 18:25:08 GMT

			status: 200

			strict-transport-security: max-age-86400

			x-frame-options: SAMEORIGIN


	HTTP Response Body:

		Las respuestas HTTP satisfactorias a peticiones 'GET' suelen tener un cuerpo que contiene la información solicitada. 

		En la mayoría de las peticiones web, se trata de datos HTML que un navegador traducirá en una página web.


	Ataques DDoS a través de HTTP:

		Tenga en cuenta que HTTP es un protocolo "sin estado" (stateless), lo que significa que cada comando se ejecuta independientemente de cualquier otro comando. 

		En la especificación original, cada petición HTTP creaba y cerraba una conexión TCP. 

		En las versiones más recientes del protocolo HTTP (HTTP 1.1 y superiores), la conexión persistente permite que varias peticiones HTTP pasen por una conexión TCP persistente, lo que mejora el consumo de recursos. 

		En el contexto de los ataques DoS o DDoS, las peticiones HTTP en grandes cantidades pueden utilizarse para montar un ataque contra un dispositivo objetivo, y se consideran parte de los ataques de capa de aplicación o ataques de capa 7.



|| Caracteristicas HTTP/1 y HTTP/2

	HTTP es un protocolo de comunicación de capa de aplicación basado en TCP/IP que estandariza la forma en que clientes y servidores se comunican entre sí. 

	Define cómo se solicita y transmite el contenido a través de Internet.

	Por protocolo de capa de aplicación, es decir, que es simplemente una capa de abstracción (que oculta los detalles específicos para facilitar su uso y se comunica con otras capas) que estandariza cómo se comunican los hosts (clientes y servidores). 

	El propio HTTP depende de TCP/IP para transmitir peticiones y respuestas entre el cliente y el servidor. 

	Por defecto, se utiliza el puerto TCP 80, pero también se pueden utilizar otros puertos. 

	HTTPS, sin embargo, utiliza el puerto 443.


	HTTP/0.9 - La primera línea (1991):

		La primera versión documentada de HTTP fue HTTP/0.9, presentada en 1991. 

		Era el protocolo más simple que existía, con un único método llamado GET. 

		Si un cliente tenía que acceder a alguna página web en el servidor, habría hecho una simple petición como la siguiente: 

		```
			GET /index.html

		```

		Y la respuesta del servidor habría sido la siguiente:


		```
			(response body)
			(connection closed)

		```

		Es decir, el servidor recibiría la petición, respondería con el HTML en respuesta y tan pronto como el contenido haya sido transferido, la conexión se cerrará. 

		Composición:

			No había cabeceras

    		GET era el único método permitido

    		La respuesta tenía que ser HTML

		Como se puede ver, el protocolo realmente no tenía nada más que ser un peldaño para lo que estaba por venir.


	HTTP/1.0 - 1996:

		En 1996 se desarrolló la siguiente versión de HTTP, HTTP/1.0, que mejoró considerablemente la versión original.

		A diferencia de la versión HTTP/0.9, diseñada únicamente para respuestas HTML, la versión HTTP/1.0 permitía manejar otros formatos de respuesta, como imágenes, archivos de vídeo, texto sin formato o cualquier otro tipo de contenido. 

		Se añadieron más métodos (POST y HEAD), se cambiaron los formatos de solicitud y respuesta, se añadieron cabeceras HTTP tanto a la solicitud como a la respuesta, se añadieron códigos de estado para identificar la respuesta, se introdujo soporte para juegos de caracteres, tipos multiparte, autorización, almacenamiento en caché, codificación de contenidos y mucho más.

		A continuación se muestra un ejemplo de solicitud y respuesta HTTP/1.0:

		```	
			GET / HTTP/1.0
			Host: cs.fyi
			User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_5)
			Accept: */*

		```

		Como puede ver, junto con la solicitud, el cliente también ha enviado su información personal, el tipo de respuesta requerido, etc. 

		Mientras que en HTTP/0.9 el cliente nunca podía enviar esa información porque no había cabeceras.

		Un ejemplo de respuesta a la petición anterior podría tener el siguiente aspecto:

		```
			HTTP/1.0 200 OK 
			Content-Type: text/plain
			Content-Length: 137582
			Expires: Thu, 05 Dec 1997 16:00:00 GMT
			Last-Modified: Wed, 5 August 1996 15:55:28 GMT
			Server: Apache 0.84

			(response body)
			(connection closed)

		```

		Al principio de la respuesta aparece HTTP/1.0 (HTTP seguido del número de versión), luego aparece el código de estado 200 seguido de la frase de motivo (o descripción del código de estado, si se quiere).

		En esta nueva versión, las cabeceras de la petición y la respuesta seguían estando codificadas en ASCII, pero el cuerpo de la respuesta podía ser de cualquier tipo: imagen, vídeo, HTML, texto sin formato o cualquier otro tipo de contenido.

		Así pues, ahora el servidor podía enviar cualquier tipo de contenido al cliente; no mucho después de su introducción, el término "Hipertexto" en HTTP se convirtió en un término inapropiado. 

		HMTP o Hypermedia Transfer Protocol (protocolo de transferencia hipermedia) podría haber tenido más sentido, pero supongo que nos quedamos con ese nombre de por vida.

		Uno de los principales inconvenientes de HTTP/1.0 era que no se podían realizar varias peticiones por conexión. 

		Es decir, cada vez que un cliente necesitara algo del servidor, tendría que abrir una nueva conexión TCP y, una vez satisfecha esa única petición, la conexión se cerraría. 

		Y para cualquier siguiente requerimiento, tendrá que ser en una nueva conexión. 

		¿Por qué es malo? Bueno, supongamos que usted visita una página web que tiene 10 imágenes, 5 hojas de estilo y 5 archivos javascript, por un total de 20 elementos que necesita obtener cuando se solicita a esa página web. 

		Dado que el servidor cierra la conexión en cuanto se completa la petición, habrá una serie de 20 conexiones separadas en las que cada uno de los elementos se servirá uno a uno en sus conexiones separadas. 

		Este gran número de conexiones se traduce en un grave problema de rendimiento, ya que la necesidad de una nueva conexión TCP impone una importante penalización de rendimiento debido al handshake de tres vías (three-way handshake) seguido de un inicio lento.


	Acuerdo de tres vías:

		En su forma más simple, todas las conexiones TCP comienzan con un protocolo de tres vías en el que el cliente y el servidor comparten una serie de paquetes antes de empezar a compartir los datos de la aplicación.

	    SYN: 

	    	El cliente toma un número aleatorio, digamos x, y lo envía al servidor.


	    SYN ACK: 

	    	El servidor acusa recibo de la solicitud enviando un paquete ACK de vuelta al cliente que está formado por un número aleatorio, digamos y, recogido por el servidor y el número x+1, donde x es el número que envió el cliente.


	    ACK:

	    	El cliente incrementa el número y recibido del servidor y envía un paquete ACK de vuelta con el número y+1.


		Una vez completado el protocolo de tres vías, puede comenzar el intercambio de datos entre el cliente y el servidor. 

		Hay que tener en cuenta que el cliente puede empezar a enviar los datos de la aplicación en cuanto envíe el último paquete ACK, pero el servidor tendrá que esperar a recibir el paquete ACK para satisfacer la petición.

		Sin embargo, algunas implementaciones de HTTP/1.0 intentaron superar este problema introduciendo una nueva cabecera llamada Connection: keep-alive que pretendía decirle al servidor "Eh servidor, no cierres esta conexión, la necesito de nuevo".

		Pero aún así, no estaba muy extendido y el problema persistía.

		Además de no tener conexión, HTTP también es un protocolo sin estado, es decir, el servidor no mantiene la información sobre el cliente, por lo que cada una de las peticiones tiene que tener la información necesaria para que el servidor pueda satisfacer la petición por sí mismo, sin ninguna asociación con peticiones anteriores. 

		Además del gran número de conexiones que el cliente tiene que abrir, también tiene que enviar datos redundantes, lo que aumenta el uso del ancho de banda.


	HTTP/1.1 - 1997

		Tras sólo 3 años de HTTP/1.0, en 1999 se publicó la siguiente versión, HTTP/1.1, que introdujo numerosas mejoras con respecto a su predecesora. 

		Las principales mejoras con respecto a HTTP/1.0 fueron las siguientes

		    Se añadieron nuevos métodos HTTP: PUT, PATCH, OPTIONS y DELETE.

		    Identificación del nombre de host En HTTP/1.0 la cabecera Host no era obligatoria, pero HTTP/1.1 la hizo obligatoria.

		    Conexiones persistentes Como se ha comentado anteriormente, en HTTP/1.0 sólo había una petición por conexión y la conexión se cerraba tan pronto como se cumplía la petición, lo que provocaba un gran impacto en el rendimiento y problemas de latencia. 

		    HTTP/1.1 introdujo las conexiones persistentes, es decir, las conexiones no se cerraban por defecto y se mantenían abiertas, lo que permitía múltiples peticiones secuenciales. 

		    Para cerrar las conexiones, la cabecera Connection: close tenía que estar disponible en la petición. 

		    Los clientes suelen enviar esta cabecera en la última petición para cerrar la conexión de forma segura.

		    Pipelining También introdujo el soporte para pipelining, donde el cliente podía enviar múltiples peticiones al servidor sin esperar la respuesta del servidor en la misma conexión y el servidor tenía que enviar la respuesta en la misma secuencia en la que se recibían las peticiones. 

		    Pero, ¿cómo sabe el cliente que éste es el punto en el que finaliza la descarga de la primera respuesta y comienza el contenido de la siguiente?. 

		    Bien, para resolver esto, debe haber una cabecera Content-Length presente que los clientes puedan usar para identificar dónde termina la respuesta y puede empezar a esperar la siguiente respuesta.


		Debe tenerse en cuenta que para beneficiarse de las conexiones persistentes o del pipelining, la cabecera Content-Length debe estar disponible en la respuesta, porque esto permitiría al cliente saber cuándo se completa la transmisión y puede enviar la siguiente petición (en la forma secuencial normal de enviar peticiones) o empezar a esperar la siguiente respuesta (cuando el pipelining está activado).

    	Pero este enfoque seguía planteando un problema. 

    	Y es, ¿qué pasa si los datos son dinámicos y el servidor no puede encontrar la longitud del contenido de antemano?. 

    	Bueno, en ese caso, realmente no puedes beneficiarte de las conexiones persistentes, ¿verdad?. 

    	Para solucionarlo, HTTP/1.1 introdujo la codificación por trozos (chunked encoding). 

    	En tales casos, el servidor puede omitir content-Length en favor de la codificación en trozos (más sobre esto en un momento). 

    	Sin embargo, si ninguno de ellos está disponible, entonces la conexión debe cerrarse al final de la petición.


	    	Transferencias por trozos en el caso de contenidos dinámicos, cuando el servidor no puede averiguar realmente la longitud del contenido al iniciar la transmisión, puede empezar a enviar el contenido por trozos (trozo a trozo) y añadir la longitud del contenido de cada trozo al enviarlo. 

	    	Y cuando se envían todos los trozos, es decir, cuando se ha completado toda la transmisión, envía un trozo vacío, es decir, con la longitud del contenido a cero, para indicar al cliente que la transmisión se ha completado. 

	    	Para notificar al cliente la transferencia en trozos, el servidor incluye la cabecera Transfer-Encoding: chunked.

		    A diferencia de HTTP/1.0, que sólo tenía autenticación básica, HTTP/1.1 incluye autenticación digest y proxy.

		    Almacenamiento en caché

		    Rangos de bytes

		    Juegos de caracteres

		    Negociación de idioma

		    Cookies de cliente

		    Compresión mejorada

		    Nuevos códigos de estado

	    	y más.


	    En el documento "Key differences between HTTP/1.0 and HTTP/1.1" (Diferencias clave entre HTTP/1.0 y HTTP/1.1) que RFC original muestra más características para los más avanzados.

		HTTP/1.1 se introdujo en 1999 y ha sido un estándar durante muchos años. 

		Aunque mejoró mucho respecto a su predecesor, con la web cambiando cada día, empezó a mostrar su edad. 

		Hoy en día, cargar una página web consume más recursos que antes.

		Una simple página web hoy en día tiene que abrir más de 30 conexiones. 

		Bueno, HTTP/1.1 tiene conexiones persistentes, entonces ¿por qué tantas conexiones? dirás. 

		La razón es que en HTTP/1.1 sólo puede haber una conexión pendiente en cualquier momento.

		HTTP/1.1 intentó arreglar esto introduciendo el pipelining, pero no solucionó completamente el problema debido al bloqueo de cabecera de línea (HOL), donde una petición lenta o pesada puede bloquear las peticiones que vienen detrás y una vez que una petición se queda atascada en un pipeline, tendrá que esperar a que se cumplan las siguientes peticiones. 

		Para superar estas deficiencias de HTTP/1.1, los desarrolladores empezaron a aplicar soluciones alternativas, como el uso de hojas de sprites, imágenes codificadas en CSS, archivos CSS/Javascript únicos y enormes, fragmentación de dominios, etc.


	SPDY - 2009:

		Google siguió adelante y empezó a experimentar con protocolos alternativos para hacer la web más rápida y mejorar la seguridad web, reduciendo al mismo tiempo la latencia de las páginas web.

		 En 2009, anunciaron SPDY.

		    SPDY es una marca registrada de Google y no es un acrónimo.

		Se vio que si seguimos aumentando el ancho de banda, el rendimiento de la red aumenta al principio pero llega un punto en el que no hay mucha ganancia de rendimiento. 

		Pero si hacemos lo mismo con la latencia, es decir, si seguimos reduciendo la latencia, hay un aumento constante del rendimiento. 

		Esta era la idea central de la ganancia de rendimiento detrás de SPDY, disminuir la latencia para aumentar el rendimiento de la red.

		    Para quienes no conozcan la diferencia, la latencia es el retardo, es decir, el tiempo que tardan los datos en viajar entre el origen y el destino (medido en milisegundos) y el ancho de banda es la cantidad de datos transferidos por segundo (bits por segundo).

		Las características de SPDY incluyen multiplexación, compresión, priorización, seguridad, etc. 
		
		HTTP/2 en la siguiente sección, como he dicho HTTP/2 se inspira principalmente en SPDY.

		SPDY no trataba realmente de sustituir a HTTP; era una capa de traducción sobre HTTP que existía en la capa de aplicación y modificaba la petición antes de enviarla a la red. 

		Empezó a convertirse en un estándar de facto y la mayoría de los navegadores empezaron a implementarlo.

		En 2015, en Google no querían tener dos estándares en competencia y decidieron fusionarlo con HTTP, dando lugar a HTTP/2 y eliminando SPDY.


	HTTP/2 - 2015:

		HTTP/2 se diseñó para el transporte de contenidos de baja latencia. 

		Las principales características o diferencias con respecto a la antigua versión HTTP/1.1 incluyen

		    Binario en lugar de Textual.

		    Multiplexación: 

		    	Múltiples peticiones HTTP asíncronas a través de una única conexión.

		    Compresión de cabeceras mediante HPACK.

		    Empuje del servidor:

		     	Múltiples respuestas para una única solicitud.

		    Priorización de peticiones.

		    Seguridad.


			Diagrama de HTTP/2 en App Layer: 

				Divide la solicitud en Headers Frame (solicitud) y Data Frame (cliente). 

		
		Protocolo binario:

			HTTP/2 trata de resolver el problema del aumento de latencia que existía en HTTP/1.x convirtiéndolo en un protocolo binario. 

			Al ser un protocolo binario, es más fácil de analizar, pero a diferencia de HTTP/1.x ya no es legible por el ojo humano. Los principales componentes de HTTP/2 son Frames y Streams
			

		Frames y Streams:

			Los mensajes HTTP se componen ahora de una o más tramas.

			Hay una trama HEADERS para los metadatos y una trama DATA para la carga útil, y existen otros tipos de tramas (HEADERS, DATA, RST_STREAM, SETTINGS, PRIORITY, etc.) que puedes consultar en las especificaciones de HTTP/2.

			Cada solicitud y respuesta HTTP/2 recibe un ID de flujo único y se divide en tramas.

			Las tramas (frames) no son más que piezas binarias de datos. 

			Una colección de tramas se denomina flujo (stream). 

			Cada frame tiene un stream id que identifica el stream al que pertenece y cada frame tiene una cabecera común.

			Además, aparte de que el ID de flujo es único, cabe mencionar que cualquier solicitud iniciada por el cliente utiliza números impares y la respuesta del servidor tiene números pares de ID de flujo.

			Aparte de los HEADERS y DATA, otro tipo de trama que creo que vale la pena mencionar aquí es RST_STREAM que es un tipo de trama especial que se utiliza para abortar algún flujo, es decir, el cliente puede enviar esta trama para hacer saber al servidor que ya no necesito este flujo. 

			En HTTP/1.1 la única forma de hacer que el servidor dejara de enviar la respuesta al cliente era cerrando la conexión, lo que provocaba un aumento de la latencia porque había que abrir una nueva conexión para cualquier petición consecutiva.

			Mientras que en HTTP/2, el cliente puede usar RST_STREAM y dejar de recibir un flujo específico mientras que la conexión seguirá abierta y los otros flujos seguirán en juego.


		Multiplexing:

			Dado que HTTP/2 es ahora un protocolo binario y como he dicho anteriormente que utiliza tramas (frames) y flujos (streams) para las peticiones y respuestas, una vez que se abre una conexión TCP, todos los flujos se envían de forma asíncrona a través de la misma conexión sin abrir ninguna conexión adicional. 

			Y a su vez, el servidor responde de la misma forma asíncrona, es decir, la respuesta no tiene orden y el cliente utiliza el identificador de flujo asignado para identificar el flujo al que pertenece un paquete concreto. 

			Esto también resuelve el problema de bloqueo de cabecera que existía en HTTP/1.x, es decir, el cliente no tendrá que esperar a la solicitud que está tardando y otras solicitudes seguirán siendo procesadas.			

		Compresión de Headers:

			Formaba parte de una RFC independiente cuyo objetivo específico era optimizar las cabeceras enviadas. 

			La esencia de esto es que cuando estamos constantemente accediendo al servidor desde un mismo cliente hay muchos datos redundantes que estamos enviando en las cabeceras una y otra vez, y a veces puede haber cookies aumentando el tamaño de las cabeceras lo que resulta en un uso de ancho de banda y un aumento de la latencia. 

			Para solucionar este problema, HTTP/2 introdujo la compresión de cabeceras.

			A diferencia de la solicitud y la respuesta, las cabeceras no se comprimen en formatos gzip o compress, etc., sino que existe un mecanismo diferente para la compresión de cabeceras: 

				los valores literales se codifican utilizando código Huffman y el cliente y el servidor mantienen una tabla de cabeceras, y tanto el cliente como el servidor omiten cualquier cabecera repetitiva (por ejemplo, agente de usuario, etc.) en las solicitudes posteriores y las referencian utilizando la tabla de cabeceras mantenida por ambos.

			Ya que estamos hablando de cabeceras, permítanme añadir que las cabeceras siguen siendo las mismas que en HTTP/1.1, excepto por la adición de algunas pseudocabeceras: :method, :scheme, :host y :path.


		Push de servidor

			El push de servidor es otra de las grandes características de HTTP/2: 

				el servidor, sabiendo que el cliente va a pedir un determinado recurso, puede enviárselo al cliente sin que éste se lo pida. 

			Por ejemplo, digamos que un navegador carga una página web, analiza toda la página para averiguar el contenido remoto que tiene que cargar desde el servidor y luego envía las consiguientes peticiones al servidor para obtener ese contenido.

			Server push permite al servidor reducir los viajes de ida y vuelta enviando los datos que sabe que el cliente va a solicitar. 

			El servidor envía una trama especial llamada PUSH_PROMISE para notificar al cliente: "¡Oye, estoy a punto de enviarte este recurso! No me lo pidas". 

			La trama PUSH_PROMISE está asociada al flujo que ha provocado el push y contiene el ID del flujo prometido, es decir, el flujo en el que el servidor enviará el recurso que se va a empujar.


		Priorización de solicitudes (Request Priorization)

			Un cliente puede asignar una prioridad a un flujo incluyendo la información de priorización en la trama HEADERS con la que se abre un flujo. 

			En cualquier otro momento, el cliente puede enviar una trama PRIORITY para cambiar la prioridad de un flujo.

			Sin ninguna información de prioridad, el servidor procesa las peticiones de forma asíncrona, es decir, sin ningún orden. 

			Si hay una prioridad asignada a un flujo, entonces basado en esta información de prioridad, el servidor decide cuántos de los recursos necesitan ser dados para procesar qué petición.


		Seguridad:

			Hubo un amplio debate sobre si la seguridad (a través de TLS) debería ser obligatoria para HTTP/2 o no. 

			Al final, se decidió no hacerla obligatoria. 

			Sin embargo, la mayoría de los proveedores declararon que sólo soportarán HTTP/2 cuando se utilice sobre TLS.

			Así que, aunque HTTP/2 no requiere cifrado por especificaciones, se ha convertido en obligatorio por defecto. 

			Una vez aclarado esto, HTTP/2, cuando se implementa sobre TLS, impone algunos requisitos, por ejemplo, debe utilizarse TLS versión 1.2 o superior, debe haber un cierto nivel de claves mínimas, se requieren claves efímeras, etc.



|| DNS

	El Sistema de Nombres de Dominio (DNS) es la guía telefónica de Internet. 

	Los seres humanos acceden a la información en línea a través de nombres de dominio, como nytimes.com o espn.com. 

	Los navegadores web interactúan a través de direcciones de Protocolo de Internet (IP). 

	El DNS traduce los nombres de dominio a direcciones IP para que los navegadores puedan cargar los recursos de Internet.

	Cada dispositivo conectado a Internet tiene una dirección IP única que otras máquinas utilizan para encontrarlo. 

	Los servidores DNS eliminan la necesidad de que los humanos memoricen direcciones IP como 192.168.1.1 (en IPv4), o nuevas direcciones IP alfanuméricas más complejas como 2400:cb00:2048:1::c629:d7a2 (en IPv6).


	Funcionamiento del Sistema de Nombres de Dominio: 

		El proceso de resolución DNS consiste en convertir un nombre de host (como www.example.com) en una dirección IP fácil de usar (como 192.168.1.1). 

		A cada dispositivo de Internet se le asigna una dirección IP, y esa dirección es necesaria para encontrar el dispositivo de Internet adecuado, al igual que se utiliza la dirección de una calle para encontrar una casa concreta. 

		Cuando un usuario quiere cargar una página web, debe producirse una traducción entre lo que el usuario teclea en su navegador web (ejemplo.com) y la dirección amigable para la máquina necesaria para localizar la página web ejemplo.com.

		Para entender el proceso que hay detrás de la resolución DNS, es importante conocer los diferentes componentes de hardware por los que debe pasar una consulta DNS.

		Para el navegador web, la búsqueda DNS se produce "entre bastidores" y no requiere ninguna interacción.


	Hay 4 servidores DNS implicados en la carga de una página web:

	    Recursor DNS (DNS recursor):  

	    	Se puede pensar en el recursor como en un bibliotecario al que se le pide que vaya a buscar un libro concreto a algún lugar de una biblioteca. 

	    	El recursor DNS es un servidor diseñado para recibir consultas de máquinas cliente a través de aplicaciones como los navegadores web. 

	    	Normalmente, el recursor se encarga de realizar peticiones adicionales para satisfacer la consulta DNS del cliente.


	    Servidor de nombres raíz (Root nameserver):

	    	El servidor raíz es el primer paso en la traducción (resolución) de nombres de host legibles por humanos en direcciones IP. 

	    	Se puede considerar como un índice en una biblioteca que apunta a diferentes estantes de libros - normalmente sirve como referencia a otras ubicaciones más específicas.


	    Servidor de nombres TLD (TLD nameserver):

	    	El servidor de dominios de nivel superior (TLD) puede considerarse como un estante específico de libros en una biblioteca. 

	    	Este servidor de nombres es el siguiente paso en la búsqueda de una dirección IP específica, y aloja la última parte de un nombre de host (en ejemplo.com, el servidor TLD es "com").


	    Servidor de nombres autoritativo (Authoritative nameserver): 

	    	Este servidor de nombres final puede considerarse como un diccionario en un estante de libros, en el que un nombre específico puede traducirse a su definición.

	    	El servidor de nombres autoritativo es la última parada en la consulta del servidor de nombres. 

	    	Si el servidor de nombres autoritativo tiene acceso al registro solicitado, devolverá la dirección IP del nombre de host solicitado al Recursor DNS (el bibliotecario) que realizó la solicitud inicial.


	Diferencia entre un servidor DNS autoritativo y resolver un DNS recursivo:

		Ambos conceptos se refieren a servidores (grupos de servidores) que forman parte integral de la infraestructura DNS, pero cada uno desempeña una función diferente y vive en lugares distintos dentro del proceso de una consulta DNS. 

		Una forma de ver la diferencia es que el resolver recursivo está al principio de la consulta DNS y el servidor de nombres autoritativo está al final.


		Resolución DNS recursiva:

			El resolutor recursivo es el ordenador que responde a una petición recursiva de un cliente y se toma el tiempo necesario para localizar el registro DNS. 

			Para ello, realiza una serie de peticiones hasta que llega al servidor de nombres DNS autoritativo para el registro solicitado (o agota el tiempo de espera o devuelve un error si no se encuentra ningún registro). 

			Por suerte, los resolutores DNS recursivos no siempre tienen que hacer varias peticiones para localizar los registros necesarios para responder a un cliente; el almacenamiento en caché es un proceso de persistencia de datos que ayuda a reducir las peticiones necesarias sirviendo el registro de recurso solicitado antes en la búsqueda DNS.


		Servidor DNS autorizado:

			En pocas palabras, un servidor DNS autoritativo es un servidor que realmente mantiene y es responsable de los registros de recursos DNS. 

			Se trata del servidor situado en la parte inferior de la cadena de búsqueda DNS que responderá con el registro de recursos consultado, permitiendo en última instancia que el navegador web que realiza la solicitud alcance la dirección IP necesaria para acceder a un sitio web u otros recursos web. 

			Un servidor de nombres autoritativo puede satisfacer consultas a partir de sus propios datos sin necesidad de consultar a otra fuente, ya que es la fuente final de verdad para determinados registros DNS.



		Diagrama DNS Recursivo y DNS Autoritativo: 

			Cliente/Navegador -> DNS Recursive Resolver -> DNS Root Nameserver -> Authoritative Nameserver/Website.com


		Vale la pena mencionar que en los casos en que la consulta es para un subdominio como foo.example.com o blog.cloudflare.com, se añadirá un servidor de nombres adicional a la secuencia después del servidor de nombres autoritativo, que es responsable de almacenar el registro CNAME del subdominio.

			Cliente/Navegador -> DNS Recursive Resolver -> DNS Root Nameserver -> Authoritative Nameserver/blog.Website.com


		Hay una diferencia clave entre muchos servicios DNS y el que proporciona Cloudflare. 

		Diferentes resolutores recursivos DNS como Google DNS, OpenDNS, y proveedores como Comcast mantienen instalaciones de centros de datos de resolutores recursivos DNS. 

		Estos resolvedores permiten consultas rápidas y fáciles a través de grupos optimizados de sistemas informáticos optimizados para DNS, pero son fundamentalmente diferentes de los servidores de nombres alojados por Cloudflare.

		Cloudflare mantiene servidores de nombres a nivel de infraestructura que son parte integral del funcionamiento de Internet. 

		Un ejemplo clave es la red de servidores f-root que Cloudflare es parcialmente responsable de alojar. 

		El F-root es uno de los componentes de la infraestructura de servidores de nombres DNS de nivel raíz responsable de los miles de millones de solicitudes de Internet al día. 

		Nuestra red Anycast nos sitúa en una posición única para gestionar grandes volúmenes de tráfico DNS sin interrumpir el servicio.


	La búsqueda en DNS:

		En la mayoría de las situaciones, el DNS se ocupa de traducir un nombre de dominio en la dirección IP adecuada. 

		Para aprender cómo funciona este proceso, es útil seguir el camino de una búsqueda DNS a medida que viaja desde un navegador web, a través del proceso de búsqueda DNS, y de vuelta otra vez. Veamos los pasos.

		Nota: A menudo, la información de la búsqueda DNS se almacena en caché localmente en el ordenador que realiza la consulta o remotamente en la infraestructura DNS. 

		Normalmente hay 8 pasos en una búsqueda DNS. 

		Cuando la información DNS se almacena en caché, se omiten pasos del proceso de búsqueda DNS, lo que lo hace más rápido.

		El siguiente ejemplo muestra los 8 pasos cuando no se almacena nada en caché


		Los 8 pasos de una búsqueda DNS:

		    Un usuario teclea "ejemplo.com" en un navegador web, la consulta viaja por Internet y es recibida por un resolver DNS recursivo.

		    A continuación, el resolver consulta un servidor de nombres DNS raíz (.).

		    El servidor raíz responde entonces al resolvedor con la dirección de un servidor DNS de dominio de nivel superior (TLD) (como .com o .net), que almacena la información de sus dominios. 

		    Al buscar ejemplo.com, nuestra petición se dirige al TLD .com.

		    A continuación, el resolver realiza una solicitud al TLD .com.

		    A continuación, el servidor del TLD responde con la dirección IP del servidor de nombres del dominio, ejemplo.com.

		    Por último, el resolver recursivo envía una consulta al servidor de nombres del dominio.

		    El servidor de nombres devuelve al resolver la dirección IP de ejemplo.com.

		    A continuación, el resolver DNS responde al navegador web con la dirección IP del dominio solicitado inicialmente.

		    Una vez que los 8 pasos de la búsqueda DNS han devuelto la dirección IP de ejemplo.com, el navegador puede solicitar la página web:
		    	
		    	El navegador realiza una petición HTTP a la dirección IP.

		    El servidor en esa IP devuelve la página web para que se muestre en el navegador (paso 10).


	DNS Resolver: 

		El resolver DNS es la primera parada en la búsqueda DNS, y es responsable de tratar con el cliente que hizo la petición inicial. 

		El resolver inicia la secuencia de consultas que, en última instancia, lleva a traducir una URL en la dirección IP necesaria.

		Nota: Una búsqueda DNS sin caché típica implicará tanto consultas recursivas como iterativas.

		Es importante diferenciar entre una consulta DNS recursiva y un resolver DNS recursivo. 

		La consulta se refiere a la petición realizada a un resolver DNS que requiere la resolución de la consulta. 

		Un resolver DNS recursivo es el ordenador que acepta una consulta recursiva y procesa la respuesta realizando las peticiones necesarias.


		Diagrama de DNS Resolver: 

			DNS Client -> DNS Recursive Query -> DNS Recursive Resolver


	Tipos de DNS Queries: 

		En una búsqueda DNS típica se producen tres tipos de consultas.

		Mediante el uso de una combinación de estas consultas, un proceso optimizado para la resolución DNS puede resultar en una reducción de la distancia recorrida. 

		En una situación ideal, los datos de registro almacenados en caché estarán disponibles, lo que permitirá a un servidor de nombres DNS devolver una consulta no recursiva.

		3 tipos de consultas DNS:

		    Consulta recursiva:

		    	En una consulta recursiva, un cliente DNS requiere que un servidor DNS (normalmente un resolver recursivo DNS) responda al cliente con el registro de recurso solicitado o con un mensaje de error si el resolver no puede encontrar el registro.


		    Consulta iterativa:

		    	En esta situación el cliente DNS permitirá que un servidor DNS devuelva la mejor respuesta que pueda. 

		    	Si el servidor DNS consultado no tiene una coincidencia para el nombre de la consulta, devolverá una remisión a un servidor DNS autoritativo para un nivel inferior del espacio de nombres del dominio. 

		    	El cliente DNS realizará entonces una consulta a la dirección de referencia. 

		    	Este proceso continúa con servidores DNS adicionales en la cadena de consulta hasta que se produce un error o se agota el tiempo de espera.


		    Consulta no recursiva: 

		    	Suele producirse cuando un cliente de resolución DNS consulta a un servidor DNS un registro al que tiene acceso, ya sea porque es autoritativo para el registro o porque el registro existe en su caché. 

		    	Normalmente, un servidor DNS almacenará en caché los registros DNS para evitar el consumo adicional de ancho de banda y la carga en los servidores ascendentes.


	Caché de DNS:

		El objetivo del almacenamiento en caché es almacenar temporalmente los datos en una ubicación que permita mejorar el rendimiento y la fiabilidad de las solicitudes de datos. 

		El almacenamiento en caché de DNS implica almacenar datos más cerca del cliente solicitante para que la consulta DNS se pueda resolver antes y se puedan evitar consultas adicionales más adelante en la cadena de búsqueda DNS, mejorando así los tiempos de carga y reduciendo el consumo de ancho de banda/CPU. 

		Los datos DNS pueden almacenarse en caché en varias ubicaciones, cada una de las cuales almacenará registros DNS durante un periodo de tiempo determinado por un tiempo de vida (TTL).

		
		Caché DNS del navegador:

			Los navegadores web modernos están diseñados por defecto para almacenar en caché los registros DNS durante un tiempo determinado. 

			El objetivo es obvio: cuanto más cerca esté la caché DNS del navegador web, menos pasos de procesamiento habrá que dar para comprobar la caché y hacer las peticiones correctas a una dirección IP.

			Cuando se realiza una solicitud para un registro DNS, la caché del navegador es la primera ubicación que se comprueba para el registro solicitado.

		En Chrome, puedes ver el estado de tu caché DNS yendo a chrome://net-internals/#dns.


	Caché DNS a nivel de sistema operativo (SO):

		El resolver DNS a nivel de sistema operativo es la segunda y última parada local antes de que una consulta DNS salga de su máquina. 

		El proceso dentro de su sistema operativo que está diseñado para gestionar esta consulta se denomina comúnmente "stub resolver" o cliente DNS. 

		Cuando un stub resolver recibe una solicitud de una aplicación, primero comprueba su propia caché para ver si tiene el registro. 

		Si no lo tiene, envía una consulta DNS (con una bandera recursiva activada), fuera de la red local a un resolver DNS recursivo dentro del proveedor de servicios de Internet (ISP).

		Cuando el resolver recursivo dentro del ISP recibe una consulta DNS, como en todos los pasos anteriores, también comprobará si la traducción de host a dirección IP solicitada ya está almacenada dentro de su capa de persistencia local.

		El resolver recursivo también tiene funcionalidades adicionales dependiendo de los tipos de registros que tenga en su caché:

		    Si el resolver no tiene los registros A, pero tiene los registros NS para los servidores de nombres autoritativos, consultará directamente a esos servidores de nombres, saltándose varios pasos en la consulta DNS. 

		    Este atajo evita las búsquedas desde los servidores de nombres raíz y .com (en nuestra búsqueda de ejemplo.com) y ayuda a que la resolución de la consulta DNS se produzca más rápidamente.

		    Si el resolver no tiene los registros NS, enviará una consulta a los servidores TLD (.com en nuestro caso), saltándose el servidor raíz.
    		
    		En el improbable caso de que el resolver no tenga registros que apunten a los servidores TLD, entonces consultará a los servidores raíz. 

    		Esto suele ocurrir después de que se haya purgado la caché DNS.



|| Hosting/Alojamiento: 
	
	Hay muchos terminos y tecnologías relacionadas con la web: 	

		Página web/Web page: 

			Documento que puede visualizarse en un navegador. 

			Se escribe en lenguaje de marcado HTML y contiene distintos recursos escritos en otros lenguajes como hojas de estilo (se escribe en CSS), scripts (JS), media (img, vid, etc.)

			Todas las páginas web disponibles en la red son accesibles a través de una dirección única a las que accedemos a través de links o escribiendo en el sitio del buscador o en la barra de busqueda del navegador.  


		Sitio web/Website: 

			Conjunto de páginas web agrupadas y conectadas entre si. 

			Cada sitio web tiene un único nombre de dominio. 

			Sus páginas web tienen enlaces explicitos en forma de texto (links).

			La página principal de un sitio es su main page o homepage. 


		Servidor web/Web server: 

			Ordenador que aloja un sitio web. 

			Todas las páginas web y  archivos de un sitio están disponibles en ese ordenador.

			Si el servidor no responde, el sitio no estará disponible y los otros sitios que aloje. 

			El servidor web enviará cualquier página web del sitio web que aloja al navegador de cualquier usuario, a petición de éste.


		Motor de busqueda/Search engine: 

			Servicio web que ayuda a encontrar otros sitios web. 

			Puede haber motores de busqueda especializados en determinados temas. 

			Un navegador es un programa informático que recupera y muestra páginas web y un motor de búsqueda es un servicio que ayuda a encontrar distintos sitios. 


	Server: 

		El término servidor web puede referirse al hardware o al software, o a ambos trabajando juntos.

    	En cuanto al hardware, un servidor web es un ordenador que almacena software de servidor web y los archivos que componen un sitio web (por ejemplo, documentos HTML, imágenes, hojas de estilo CSS y archivos JavaScript). 

    	Un servidor web se conecta a Internet y soporta el intercambio físico de datos con otros dispositivos conectados a la red.

    	En cuanto al software, un servidor web incluye varias partes que controlan la forma en que los usuarios acceden a los archivos alojados. 

    	Como mínimo, se trata de un servidor HTTP. 

    	Un servidor HTTP es un software que entiende las URL (direcciones web) y HTTP (el protocolo que utiliza el navegador para ver las páginas web). 

    	Se puede acceder a un servidor HTTP a través de los nombres de dominio de los sitios web que almacena, y entrega el contenido de estos sitios web alojados al dispositivo del usuario final.

		En el nivel más básico, cuando un navegador necesita un archivo alojado en un servidor web, lo solicita a través de HTTP. 

		Cuando la petición llega al servidor web (hardware) correcto, el servidor HTTP (software) acepta la petición, encuentra el documento solicitado y lo devuelve al navegador, también a través de HTTP. 

		(Si el servidor no encuentra el documento solicitado, devuelve en su lugar una respuesta 404).
	

		Diagrama Cliente-Servidor: 

			El navegador manda una solicitud o petición HTTP para obtener los recursos del servidor (hardware) que tiene los archivos solicitados y un servidor HTTP (software). 


		Para publicar un sitio web se necesita un servidor web estático o dinámico.

		Un servidor web estático, o stack, consiste en un ordenador (hardware) con un servidor HTTP (software). 

		Lo llamamos "estático" porque el servidor envía los archivos alojados tal cual al navegador.

		Un servidor web dinámico consiste en un servidor web estático más software adicional, normalmente un servidor de aplicaciones y una base de datos. 

		Lo llamamos "dinámico" porque el servidor de aplicaciones actualiza los archivos alojados antes de enviar el contenido a su navegador a través del servidor HTTP.

		Por ejemplo, para producir las páginas web finales que ves en el navegador, el servidor de aplicaciones puede rellenar una plantilla HTML con contenido de una base de datos. 

		Sitios como MDN o Wikipedia tienen miles de páginas web.

		Normalmente, este tipo de sitios se componen de unas pocas plantillas HTML y una gigantesca base de datos, en lugar de miles de documentos HTML estáticos.

		Esta configuración facilita el mantenimiento y la distribución de los contenidos.


	Obtención de una página web: 

		Para obtener una página web, el navegador envía una petición al servidor web, que busca el archivo solicitado en su propio espacio de almacenamiento. 

		Cuando encuentra el archivo, el servidor lo lee, lo procesa según sea necesario y lo envía al navegador.


	Alojamiento de archivos:

		En primer lugar, un servidor web tiene que almacenar los archivos del sitio web, es decir, todos los documentos HTML y sus activos relacionados, incluidas imágenes, hojas de estilo CSS, archivos JavaScript, fuentes y vídeo.

		Técnicamente, podrías alojar todos esos archivos en tu propio ordenador, pero es mucho más cómodo almacenarlos todos en un servidor web dedicado porque:

	   		Un servidor web dedicado suele estar más disponible (en funcionamiento).

	   		Excluyendo el tiempo de inactividad y los problemas del sistema, un servidor web dedicado siempre está conectado a Internet.

	    	Un servidor web dedicado puede tener la misma dirección IP todo el tiempo. 

	    	Esto se conoce como dirección IP dedicada. (No todos los ISP proporcionan una dirección IP fija para las líneas domésticas).

	    	Un servidor web dedicado suele ser mantenido por un tercero.

		Por todas estas razones, encontrar un buen proveedor de alojamiento es una parte clave de la creación de su sitio web. 

		Examine los distintos servicios que ofrecen las empresas. 

		Elija uno que se ajuste a sus necesidades y presupuesto. (Los servicios van de gratuitos a miles de dólares al mes.) Puede encontrar más detalles en este artículo.

		Una vez que disponga del servicio de alojamiento web, deberá cargar sus archivos en el servidor web.


	Comunicación a través de HTTP

		En segundo lugar, un servidor web proporciona soporte para HTTP (Protocolo de Transferencia de Hipertexto). 

		Como su nombre indica, HTTP especifica cómo transferir hipertexto (documentos web enlazados) entre dos ordenadores.

		Un protocolo es un conjunto de reglas para la comunicación entre dos ordenadores. 

		HTTP es un protocolo textual y sin estado.


		Textual

		    Todos los comandos son de texto plano y legibles.


		Sin estado (stateless)

		    Ni el servidor ni el cliente recuerdan comunicaciones anteriores.

		    Por ejemplo, basándose sólo en HTTP, un servidor no puede recordar una contraseña que usted escribió o recordar su progreso en una transacción incompleta. 

		    Para este tipo de tareas se necesita un servidor de aplicaciones.


		HTTP proporciona reglas claras sobre cómo se comunican un cliente y un servidor. 

		Algunas características:

	    	Normalmente sólo los clientes hacen peticiones HTTP, y sólo a los servidores. 

	    	Los servidores responden a las peticiones HTTP de los clientes. 

	    	Un servidor también puede introducir datos en la caché de un cliente, antes de que éste los solicite, a través de un mecanismo llamado server push.

	    	Al solicitar un archivo a través de HTTP, los clientes deben proporcionar la URL del archivo.

	    	El servidor web debe responder a cada solicitud HTTP, al menos con un mensaje de error.


		En un servidor web, el servidor HTTP es responsable de procesar y responder a las peticiones entrantes.

			Al recibir una solicitud, un servidor HTTP comprueba si la URL solicitada coincide con un archivo existente.

			Si es así, el servidor web devuelve el contenido del archivo al navegador. 

			En caso contrario, el servidor comprobará si debe generar un archivo dinámicamente para la solicitud (véase Contenido estático frente a contenido dinámico).

			Si ninguna de estas opciones es posible, el servidor web devuelve un mensaje de error al navegador, normalmente 404 Not Found. 

			El error 404 es tan común que algunos diseñadores web dedican mucho tiempo y esfuerzo a diseñar páginas de error 404.


	Contenido estático frente a contenido dinámico

		A grandes rasgos, un servidor puede servir contenidos estáticos o dinámicos. Recuerde que el término estático significa "servido tal cual". 

		Los sitios estáticos son los más fáciles de configurar, por lo que le sugerimos que su primer sitio sea estático.

		El término dinámico significa que el servidor procesa el contenido o incluso lo genera sobre la marcha a partir de una base de datos. 

		Este enfoque proporciona más flexibilidad, pero la pila técnica es más compleja, por lo que es mucho más difícil construir un sitio web.

		Es imposible sugerir un único servidor de aplicaciones listo para usar que sea la solución adecuada para todos los casos de uso posibles. 

		Algunos servidores de aplicaciones están diseñados para alojar y gestionar blogs, wikis o soluciones de comercio electrónico, mientras que otros son más genéricos. 

		Si va a crear un sitio web dinámico, tómese su tiempo para investigar sus requisitos y encontrar la tecnología que mejor se adapte a sus necesidades.

		La mayoría de los desarrolladores de sitios web no necesitarán crear un servidor de aplicaciones desde cero, porque hay muchas soluciones listas para usar, muchas de las cuales son muy configurables. 

		Pero si necesita crear su propio servidor, probablemente querrá utilizar un framework de servidor, aprovechando el código y las bibliotecas existentes, y ampliando sólo las partes que necesite para satisfacer su caso de uso. 

		Sólo un número relativamente pequeño de desarrolladores necesitará desarrollar un servidor completamente desde cero: por ejemplo, para cumplir con las estrictas limitaciones de recursos de un sistema embebido. 

		De esto se encarga la programación de sitios web del lado del servidor. 


	Publicar Sitio Web/Cargar archivos/Upload files: 

		Se necesita un servicio de alojamiento y un nombre de dominio. 

		    El alojamiento web es un espacio de archivos alquilado en el servidor web de una empresa de alojamiento. 

		    Usted coloca los archivos del sitio web en el servidor web.

		    El servidor web proporciona el contenido del sitio web a los visitantes.

		    Un nombre de dominio es la dirección única donde la gente encuentra su sitio web, como https://www.mozilla.org o https://www.bbc.co.uk. 

		    Puede alquilar su nombre de dominio durante tantos años como desee a un registrador de dominios.

		Muchos sitios web profesionales se ponen en línea de esta manera.

		Además, necesitará un programa de Protocolo de Transferencia de Archivos (FTP) para transferir los archivos del sitio web al servidor. 

		Los programas FTP son muy variados, pero en general hay que conectarse al servidor web con los datos facilitados por la empresa de alojamiento (nombre de usuario, contraseña y nombre de host). 

		A continuación, el programa te muestra tus archivos locales y los del servidor web en dos ventanas, y te permite transferir archivos de un lado a otro.

		Tambien, para poner un sitio online hay varios clientes disponibles como SFTP, RSync y GitHub. 


		Clientes SFTP: 

			Entre los disponibles está Filezilla que es gratuito y de código abierto. 

			Loggearse: 

				Necesitamos contratar un servicio de hosting que nos va a dar las credenciales de nuestra cuenta. 

				```			
				    SFTP server: sftp://demozilla.examplehostingprovider.net
				    Username: demozilla
				    Password: quickbrownfox
				    Port: 5548
				    To publish on the web, put your files into the Public/htdocs directory.

				```

				La dirección pricipal estará vacía.

				Para conectar su cliente SFTP al servidor distante, siga estos pasos:

				    Seleccione Archivos > Administrador de Sitios... en el menú principal.

				    En la ventana del Administrador de Sitios, pulse el botón Nuevo Sitio, luego rellene el nombre del sitio como demozilla en el espacio proporcionado.

				    Introduzca el servidor SFTP proporcionado por su host en el campo Host:.

				    En el menú desplegable Tipo de inicio de sesión:, seleccione Normal y, a continuación, introduzca el nombre de usuario y la contraseña proporcionados en los campos correspondientes.

				    Rellena el puerto correcto y otra información.

				    Ahora pulse Conectar para conectarse al servidor SFTP.


				Asegúrese de que su proveedor de alojamiento ofrece conexión SFTP (FTP seguro) a su espacio de alojamiento. FTP es intrínsecamente inseguro, y no deberías usarlo.


			Vista de archivos remota y local: 

				Una vez conectado, debemos ver: 

				    En el panel central izquierdo, verás tus archivos locales. 

				    Navegue hasta el directorio donde almacena su sitio web (por ejemplo, mdn).

				    En el panel central derecho, verá los archivos remotos.

				    Estamos logueados en nuestra raíz FTP remota (en este caso, usuarios/demozilla)
				    Puede ignorar los paneles inferior y superior por ahora.

				    Respectivamente, son un registro de mensajes que muestran el estado de la conexión entre tu ordenador y el servidor SFTP, y un registro en vivo de cada interacción entre tu cliente SFTP y el servidor.


			Cargar, publicar o actualizar archivos al servidor:

				Las instrucciones de nuestro host de ejemplo nos decían "Para publicar en la web, ponga sus archivos en el directorio Public/htdocs". 

				Debe navegar hasta el directorio especificado en el panel derecho. 

				Este directorio es efectivamente la raíz de su sitio web: 

					donde su archivo index.html y otros recursos irán.

				Una vez que haya encontrado el directorio remoto correcto en el que colocar sus archivos, para subirlos al servidor deberá arrastrarlos y soltarlos desde el panel izquierdo al panel derecho.


			Verificar estado online: 

				Para verificar si los archivos realmente están en línea, podemos comprobarlo volviendo a tu sitio web principal o al que deseamos verficar: 

					Por ejemplo, http://demozilla.examplehostingprovider.net/ en el navegador.


		Rsync: 

			Rsync es una herramienta de sincronización de archivos de local a remoto, que suele estar disponible en la mayoría de sistemas basados en Unix (como macOS y Linux), aunque también existen versiones para Windows.

			Se considera una herramienta más avanzada que SFTP, porque por defecto se utiliza en la línea de comandos. 

			Un comando básico tiene el siguiente aspecto:

			
			```
				rsync [-opciones] SOURCE user@x.x.x.x:DESTINATION

			```

		    -options es un guión seguido de una o más letras, por ejemplo -v para mensajes de error verbose, y -b para hacer copias de seguridad.

		    Puedes ver la lista completa en la página de manual de rsync (busca "Options Summary").

		    SOURCE es la ruta al archivo o directorio local desde el que desea copiar los archivos.

		    user@ son las credenciales del usuario del servidor remoto al que desea copiar los archivos.

		    x.x.x.x es la dirección IP del servidor remoto.

		    DESTINATION es la ruta a la ubicación en la que quieres copiar el directorio o los archivos en el servidor remoto.

			Tendrás que solicitar estos datos a tu proveedor de alojamiento.

		
			Conexión Segura: 

				Por supuesto, es una buena idea utilizar una conexión segura, como con FTP a SFTP

				En el caso de Rsync, se especifican los detalles SSH para realizar la conexión a través de SSH, utilizando la opción -e. Por ejemplo:

				```
					rsync [-options] -e "ssh [SSH DETAILS GO HERE]" SOURCE user@x.x.x.x:DESTINATION

				```


		GUI para Rsync

			Existen herramientas GUI para Rsync (para aquellos que no se sientan tan cómodos utilizando la línea de comandos). 

			Acrosync es una de estas herramientas, y está disponible para Windows y macOS.

			Una vez más, tendrías que obtener las credenciales de conexión de tu proveedor de alojamiento, pero de esta manera tendrías una GUI para introducirlas.


		GitHub:

			GitHub te permite publicar sitios web a través de páginas GitHub (gh-pages).

			Sin embargo, vale la pena saber que también puedes alojar un sitio web en GitHub, pero utilizando un dominio personalizado con él.


		Web Interface: 

			Provista por el hosting server. 


		Web DAV: 

			Extensión del protocolo HTTP, permite una gestión de archivos


	Tipos de Servidores: 

		El alojamiento web es un servicio en línea que hace que el contenido de su sitio web sea accesible en Internet. 

		Cuando se contrata un plan de alojamiento, se alquila espacio en un servidor físico para almacenar todos los archivos y datos del sitio web.

		Los proveedores de alojamiento web proporcionan diferentes tecnologías y los recursos necesarios para que su sitio web funcione de forma eficaz y segura. 

		Se encargan de mantener el servidor en funcionamiento, aplicar las medidas de seguridad del alojamiento y garantizar que datos como textos, fotos y otros archivos se transfieran correctamente a los navegadores de los visitantes.


		Autoalojamiento:

			Puede alojar un sitio web usted mismo, pero requiere amplios conocimientos técnicos. 

			El autoalojamiento implica instalar y configurar un servidor web desde cero, incluyendo el equipo, la infraestructura, el hardware y el software. 

			Además, tendrá que ocuparse de todo el mantenimiento.


		Proveedor de alojamiento: 

			Un proveedor de servicios de alojamiento web garantiza que su sitio web funcione de forma óptima y con mejores protocolos de seguridad.

			El servidor que aloja su sitio web es un ordenador físico que funciona continuamente para que el sitio esté disponible para los visitantes en todo momento.

			Además, simplifica los numerosos y complejos aspectos de alojar un sitio web, desde la instalación del software hasta la asistencia técnica.

			La mayoría de los proveedores de alojamiento web ofrecen diferentes paquetes de alojamiento para diferentes tipos de clientes, desde propietarios de sitios web empresariales hasta creadores de blogs personales.

			Lo ideal es empezar con la solución de alojamiento más sencilla. 

			Una vez que su sitio tenga más tráfico, puede cambiar a un plan más avanzado. 

			No dude en consultar los precios de alojamiento de Hostinger para hacerse una idea general de los distintos tipos de alojamiento y sus costes.

		
		Shared Hosting: 

			Con el alojamiento compartido, varios usuarios comparten los mismos recursos del servidor, incluida la memoria, la capacidad de procesamiento y el espacio de almacenamiento.

			Debido a su sencillez y asequibilidad, el alojamiento web compartido es una solución excelente para pequeñas empresas y sitios web personales que no requieren una configuración avanzada o un mayor ancho de banda. 

			Por lo tanto, el alojamiento compartido es una excelente opción para los principiantes que necesitan alojamiento barato para empezar.


			Ventajas

			    Rentable, ideal para sitios web de pequeña escala.

			    No requiere conocimientos técnicos.

			    Opciones de servidor preconfiguradas.

			    No es necesario ocuparse del mantenimiento ni de la administración del servidor.


			Contras

			    Acceso mínimo a la configuración del servidor.

			    El aumento de tráfico en otros sitios web puede afectar a la velocidad de su sitio web.


		Virtual Private Server (VPS) Hosting:

			Con este tipo de alojamiento web, su sitio web también comparte un servidor físico con otros usuarios, pero el proveedor de alojamiento web crea una partición virtual para cada usuario. 

			Así, un sitio alojado en un servidor privado virtual obtiene una cantidad asignada de recursos.

			El alojamiento web VPS es una gran opción para sitios de tamaño medio, tiendas de comercio electrónico y grandes blogs con un número de visitantes en rápido crecimiento.


			Ventajas

			    Espacio de servidor dedicado.

			    El aumento de tráfico en otros sitios web no tiene impacto en el rendimiento de su sitio.

			    Acceso raíz al servidor
			    Gran capacidad de personalización.


			Contras

			    Los usuarios necesitan conocimientos técnicos para gestionarlo.

			    Aunque es relativamente asequible, algunos usuarios pueden tener que contratar a un desarrollador para gestionar el servidor virtual, lo que incrementa los costes totales.


		Cloud Hosting: 

			Esta solución de alojamiento web utiliza varios servidores virtuales para alojar sitios.

			Así, si un servidor experimenta un tráfico elevado o un problema, los restantes tomarán el relevo y mantendrán el sitio web operativo.

			Puesto que se basa en un clúster de servidores (conjunto de servidores bajo la misma IP) para funcionar, los negocios con web site múltiples y los sitios grandes como tiendas del eCommerce pueden beneficiar de él, proporciona poco a ningún tiempo muerto.


			Ventajas

			    Menor probabilidad de tiempo de inactividad y fallos de hardware.

			    Utiliza el equilibrio de carga para gestionar el tráfico elevado y evitar ataques DDoS.

			    Escalabilidad: 

			    	su sitio web no está limitado a los recursos de un único servidor.


			Contras

			    No siempre se proporciona acceso raíz.

			    Es más caro que el VPS y el alojamiento compartido.


		WordPress Hosting:

			Este tipo de servicio de alojamiento web CMS proporciona un entorno de servidor optimizado para WordPress para ayudar a que su sitio cargue más rápido y minimizar los posibles problemas. 

			Sin embargo, otros tipos de alojamiento web siguen funcionando para sitios web basados en este popular sistema de gestión de contenidos (CMS).

			Normalmente, los planes de alojamiento optimizados para WordPress vienen con características tales como temas preinstalados, plugins para funciones básicas como el almacenamiento en caché y la seguridad, y otras herramientas.


			Ventajas

			    Bajo coste y fácil de usar para principiantes
			    Rendimiento optimizado para sitios WordPress.

			    Equipo de atención al cliente formado en problemas de WordPress.

			    Plugins y temas de WordPress preinstalados


			Contras

			    No es un tipo de alojamiento web ideal para sitios web que no sean de WordPress.


		Dedicated Hosting:

			El alojamiento dedicado designa un servidor físico para cada sitio web. 

			Al optar por el alojamiento dedicado, puede configurar el servidor, elegir el sistema operativo y el software que desee y personalizar todo el entorno de alojamiento según sus especificaciones.

			Alquilar un servidor dedicado es tan potente como tener su propio servidor in situ, pero con la ventaja añadida de obtener asistencia profesional de su proveedor de alojamiento Web. 

			Por lo tanto, el alojamiento dedicado es ideal para las grandes empresas en línea que se ocupan de tráfico pesado.


			Ventajas

			    Control total sobre la configuración del servidor.

			    Alta fiabilidad.

			    Acceso root al servidor.


			Contras

			    Coste elevado, más orientado a grandes empresas.

			    Se requieren conocimientos técnicos y de gestión de servidores.


	Características de 
	los servicios de alojamiento web:

		A medida que su sitio web crece, es posible que necesite más espacio de almacenamiento, ancho de banda y otros tipos de recursos. 

		En ese caso, puede considerar migrar a una solución de alojamiento más avanzada, como alojamiento en la nube o VPS.

		Por lo tanto, asegúrese de encontrar el mejor proveedor de alojamiento web que ofrezca una variedad de servicios para que pueda actualizar en cualquier momento. 

		Además, hay varios factores a analizar cuando se trata de decidir entre proveedores de alojamiento web.


		Panel de control:

			Con un panel de control de alojamiento, podrá gestionar la cuenta de alojamiento sin tener que iniciar sesión en el servidor Web. 
			
			Por lo tanto, es mejor optar por proveedores de alojamiento web que ofrezcan una interfaz de usuario fácil de manejar para usuarios de todos los niveles.

			Gestionar sus archivos, crear una copia de seguridad completa e instalar aplicaciones asociadas a su sitio web, de forma rápida y eficaz.


		Tiempo de actividad del alojamiento web:

			Debido a servidores web mal mantenidos o inestables, las caídas frecuentes e inesperadas pueden afectar gravemente a su negocio y a la confianza de sus clientes.

			Por lo tanto, asegúrese de que el host que elija cumple la garantía de tiempo de actividad que anuncia.

			Una garantía de tiempo de actividad y unas condiciones de servicio justas reflejan el compromiso de las empresas de alojamiento de mantener sus sistemas en funcionamiento.


		Especificaciones técnicas:

			Además de elegir servicios de alojamiento con suficiente espacio en disco, potencia de procesamiento y ancho de banda, debe buscar otras características que ayuden a que su sitio web funcione sin problemas.


		Reseñas en línea:

			Busque reseñas de alojamiento de sitios web que ofrezcan información detallada sobre los distintos proveedores de servicios de alojamiento web.

			La mayoría de las reseñas en línea incluyen información sobre el tiempo de actividad y la velocidad, por lo que podrá ver cómo funcionan realmente los servidores del proveedor.

		
		Seguridad:

			Asegúrese de que el proveedor de alojamiento esté bien equipado con medidas de seguridad avanzadas que le ayuden a proteger su sitio de malware o ataques DDoS.

			Pueden incluir gestión de accesos, detección de malware, copias de seguridad automáticas y actualizaciones.
		

		Atención al cliente 24/7:

			La asistencia técnica o al cliente las 24 horas del día es muy útil si su sitio web sufre retrasos inesperados, caídas o incluso fallos de seguridad. 

			Compruebe si el host también proporciona recursos de soporte como tutoriales y bases de conocimiento.

		
		Servicios adicionales:

			Un gran plan de alojamiento ofrece una excelente relación calidad-precio si contiene complementos y funciones gratuitos, como un certificado SSL, una cuenta de correo electrónico empresarial o una red de distribución de contenidos (CDN).


	Servidor y nombre de dominio: 

		Después de elegir dónde almacenar los archivos de su sitio web, el siguiente paso para configurar su sitio web es realizar una búsqueda de nombres de dominio y luego comprar un nombre de dominio. 

		Dominio y alojamiento son dos cosas diferentes pero igualmente importantes necesarias para publicar su sitio web en línea.

		Mientras que el alojamiento se utiliza para almacenar su sitio, un nombre de dominio actúa como identidad digital del sitio web, permitiendo a la gente acceder fácilmente a él.

		Un nombre de dominio suele consistir en el nombre de un sitio web y una extensión de dominio como .com, .org o .net. Además, hay muchas otras opciones y nuevos nombres de dominio como .xyz, que se encuentran entre las alternativas más populares hoy en día.

		Un dominio y una cuenta de alojamiento pueden comprarse al mismo proveedor o a proveedores diferentes. 

		Muchas empresas de alojamiento, ofrecen también el registro de dominios.

		Para empezar, decídase por un nombre de dominio y compruebe su disponibilidad.

		Una vez que encuentres un nombre de dominio único, regístralo en un registrador de dominios. 

		Si no es la misma empresa que eligió para alojar el sitio, compre un plan de alojamiento y apunte el nombre de dominio en consecuencia.

		Otra opción es adquirir un plan de alojamiento que incluya el registro gratuito del nombre de dominio, una solución mucho más sencilla y asequible.

		Sin embargo, si no está satisfecho con el servicio prestado, puede migrar el sitio a un nuevo proveedor. 

		Sólo tienes que asegurarte de que la empresa es compatible con el framework de tu sitio web.



|| Nombre de Dominio
	
	Un nombre de dominio es una dirección web única que puede adquirirse mediante el registro de un dominio.

	Normalmente, los nombres de dominio constan de un nombre de sitio web y una extensión de nombre de dominio.

	Un buen dominio refuerza su imagen de marca y ayuda a su público a encontrar su sitio web.

	Un nombre de dominio es el equivalente de un sitio web a una dirección física. 

	Consta de un nombre y una extensión.

	Ayuda a los usuarios a encontrar fácilmente su sitio web y elimina la necesidad de memorizar la dirección del protocolo de Internet (IP) del sitio. 

	Además, los nombres de dominio son fundamentales para la infraestructura de Internet.


	Funcionamiento de los nombre de dominio: 

		Se refiere a la interacción que hace el usuario/navegador con la red del DNS y servidores: 

			Browser <-> DNS server - DNS server <-> Hosting server


		Un nombre de dominio y un servidor de alojamiento web son los dos elementos principales de un sitio web. 

		Todos los nombres de dominio se conectan a sus correspondientes direcciones IP y apuntan a los servidores específicos que alojan el sitio.

		Cuando un usuario introduce un nombre de dominio en un navegador, una red mundial de servidores del Sistema de Nombres de Dominio (DNS) buscará su dirección IP y servidor web asociados. 

		Este servidor web almacena los datos del sitio web, incluidos sus archivos, base de datos y código HTML.

		A continuación, el servidor web correspondiente recogerá los datos solicitados del servicio de alojamiento del dominio y devolverá la solicitud al navegador.

		Una vez que el navegador recibe los datos lo convertirá en una página web para el usuario.


	Características que aportan los nombres de dominio: 

	    Memorabilidad del sitio web: 

	    	Técnicamente, su público puede visitar su sitio web introduciendo su dirección IP. 

	    	Sin embargo, es difícil de recordar, ya que consiste en una cadena de números aleatorios. 

	    	Los nombres de dominio hacen que un sitio sea más accesible para los usuarios.


	    Marca eficaz: 

	    	Un nombre de dominio bien pensado ayuda a transmitir los valores y la misión de su proyecto o negocio.


	    Credibilidad: 

	    	Los sitios web con nombres de dominio personalizados tienen un aspecto más profesional que los que tienen un subdominio gratuito, web.constructorweb.com.


	    Direcciones de correo electrónico personalizadas: 

	    	Un nombre de dominio te permite crear cuentas de correo electrónico profesionales, como name@yourdomain.com. 

	    	También hace que tu presentación sea coherente en los distintos canales online.


	    SEO: 

	    	Un nombre de dominio memorable con palabras clave relevantes tendrá un impacto positivo en la optimización del motor de búsqueda de su sitio web, mejorando su clasificación en Google.


	Tipos de nombres de dominio: 

		TLD (Top Level Domain): 

			Dominio de primer nivel

			El Dominio de nivel superior es el término general para una extensión de dominio. 

			Es la parte que aparece junto al nombre. 

			Por ejemplo, en el nombre de dominio basicweb.com, ".com" es el dominio de nivel superior.

			Hay varios TLD (dominios de nivel superior) disponibles en Internet, pero los dominios .com siguen siendo los más populares, ya que más del 47% de todos los sitios los utilizan. 

			Aunque se suele utilizar para empresas comerciales, otros proyectos pueden utilizar el dominio de primer nivel .com para mejorar la credibilidad del sitio web.

			Otra ventaja de las extensiones populares es que pueden impulsar un alto tráfico orgánico, ya que los usuarios suelen escribirlas por defecto. He aquí otras opciones de TLD populares:

			   
		    Dominio .net: 

		    	las empresas que trabajan en el ámbito de las redes pueden elegir este TLD.

		    	Dicho esto, .net es una gran alternativa a .com, independientemente de su nicho.


		    Dominio .biz:

		    	Otra alternativa a .com.

		    	Es una buena opción para un nombre de dominio empresarial.


		    Dominio .org: 

		    	Es el TLD preferido por las organizaciones sin ánimo de lucro.


		    Dominio .xyz:

		    	En referencia a las generaciones X, Y y Z, esta extensión de dominio es una alternativa más asequible para cualquiera que desee construir su presencia en línea. 

		    	Este TLD también es popular para sitios de pruebas.


		    Dominio .icu:

		    	Significa "I see you", esta extensión es adecuada para cualquier proyecto.


			En el lado negativo, los nombres de dominio populares pueden ser muy caros.

			Las extensiones menos comunes, como .online, .io, .shop y .tech, suelen ser más asequibles y exclusivas.

			Sin embargo, con el creciente número de sitios nuevos que se crean a diario, la popularidad y el coste de un dominio de primer nivel específico pueden cambiar.

			La Corporación de Asignación de Nombres y Números de Internet (ICANN) gestiona la distribución de los dominios de primer nivel. 

			Entre las responsabilidades de la ICANN figuran:

		    	Evaluar y aprobar las solicitudes de nuevos TLD.

		    	Gestionar y supervisar los registros de dominios.

		   		Desarrollar y coordinar la política del sistema de nombres de dominio.

		    	Garantizar que la introducción de nuevos TLD se ajusta a la misión de la organización de potenciar la innovación, la competencia y las opciones del consumidor en línea.


		ccTLD: Dominio de primer nivel en código de país:

			Los ccTLD (country-code top-level domains) son extensiones específicas de un país concreto. 

			Suelen constar de dos letras basadas en los códigos internacionales de los países.

			A modo de ejemplo, los sitios de la India pueden utilizar .in como extensión de dominio, mientras que .us suele registrarse para sitios web con sede en Estados Unidos.

			He aquí otros ejemplos de ccTLDs:

			    .se - Suecia
			    .lt - Lituania
			    .de - Alemania
			    .it - Italia

			Un ccTLD es adecuado para empresas, organizaciones o entidades que operan en un país concreto. 

			Las empresas internacionales también pueden utilizar ccTLD para diferenciar contenidos localizados en distintas regiones.

			Por ejemplo, la BBC utiliza bbc.co.uk como dominio para el Reino Unido y bbc.com para la audiencia internacional.

			Si no está seguro del código de país de un país, la base de datos de la Organización Mundial de la Propiedad Intelectual (WIPO) puede ayudarle a encontrar el correcto.


		gTLD: Dominio genérico de primer nivel

			Los gTLD (generic top-level domains) son extensiones de dominio que no dependen de un código de país. 

			Los dominios .com y .net son excelentes ejemplos de gTLD.

			Sin embargo, algunos de ellos están asociados a una comunidad específica, por lo que debe tener cuidado de no confundir a sus visitantes.

			A menudo denominados TLD patrocinados, estas extensiones de dominio están representadas por una organización patrocinadora que establece y hace cumplir las normas del TLD. 

			Ejemplos de TLD patrocinados:

		    Dominio .edu:

		    	Gestionado por EDUCAUSE, es elegible para instituciones de educación superior de EE.UU..


		    Dominio .asia:

		    	Las empresas, organizaciones o entidades que operan en la región Asia-Pacífico pueden utilizar este TLD.

		    	Este TLD está patrocinado por DotAsia Organisation Ltd.


		    Dominio .travel:

		    	Propiedad de Donuts Inc., este TLD es una gran opción para agencias de viajes, líneas aéreas, hoteleros y oficinas de turismo.


		    Dominio .gov:

		    	patrocinado por Cybersecurity and Infrastructure Security Agency y reservado para organizaciones gubernamentales.


			Si su empresa o proyecto no pertenece a una categoría concreta, no podrá utilizar un dominio de primer nivel genérico asociado a ella.


		Dominio de segundo nivel/Second-Level-Domain:

			Un dominio de segundo nivel (SLD) está por debajo de los TLD en la jerarquía de nombres de dominio. 

			Un SLD es la sección de un nombre de dominio situada a la izquierda del último punto. Por ejemplo, en www.google.com, "google" es el SLD.

			Algunos registros de nombres de dominio utilizan un dominio de segundo nivel para indicar la entidad específica que está registrada. 

			Por ejemplo, las instituciones académicas del Reino Unido suelen registrar sitios web bajo .ac.uk, y las empresas comerciales de Australia utilizan nombres de dominio .com.au.


			Los propietarios de sitios web suelen utilizar sus nombres comerciales registrados como nombres de dominio de segundo nivel.

				Google/Alphabet en Google.com

			Aunque suele ser una buena idea, no tiene por qué hacer que su nombre de dominio sea exactamente igual que el nombre de su empresa.

			A continuación, le indicamos algunas razones por las que puede considerar la posibilidad de utilizar un nombre de dominio diferente:

				Si el nombre de su empresa ya está ocupado, tendrá que elegir un nombre de dominio diferente.

				Si el nombre de su empresa es demasiado largo, elija un nombre de dominio más corto.

				Elija un nombre de dominio que sea más relevante para el contenido de su sitio web.


		Subdominio

			Un subdominio especifica una división separada de un dominio principal dentro de los mismos servidores. 

			Por lo tanto, no necesita registrar un subdominio si ya posee el dominio.

			Un subdominio también puede denominarse nombre de host.

			La parte www en la mayoría de las URL es técnicamente un subdominio, lo que sugiere que un sitio web forma parte de la World Wide Web. 

			Sin embargo, algunos sitios web tienen un subdominio adicional además del nombre de host.

			Una razón común para crear subdominios es organizar el contenido web en secciones separadas. 

			Por ejemplo, Google utiliza developers.google.com para proporcionar información específica para desarrolladores.

			Un subdominio también es útil para la localización. 

			Por ejemplo, Wikipedia. Tiene un subdominio para cada idioma: en.wikipedia.org para la versión inglesa y de.wikipedia.org para la alemana.

			Para un sitio web empresarial, he aquí ejemplos de subdominios populares:

		    blog.yourwebsite.com:

		    	Para el blog de su empresa, que puede cubrir actualizaciones de la empresa e historias de clientes.


		    news.yourwebsite.com:

		    	Para las últimas noticias de la empresa.


		    resources.yourwebsite.com:

		    	para estudios de casos, libros blancos o libros electrónicos.


		    support.yourwebsite.com:

		    	Documentación, preguntas frecuentes e información de contacto.


		Dominio gratuito:

			Los creadores de sitios web suelen ofrecer nombres de dominio gratuitos a los nuevos usuarios. 

			Normalmente, los principiantes aprovechan esta oportunidad para crear sitios web antes de invertir dinero en ellos. 

			Una dirección de sitio web gratuita suele seguir la misma estructura que los subdominios.

			Un subdominio gratuito a menudo viene con características y herramientas mínimas. 

			Puede limitar las oportunidades de marca de tu sitio web, ya que sólo es un subdominio de tu plataforma de creación de sitios web.

			Recomendamos invertir en un nombre de dominio personalizado de pago para mejorar la identidad de marca y la credibilidad.


	Nombre de dominio vs URL: 
		
		Aunque un nombre de dominio y una de recursos URL (Universal Resource Locator) comparten algunas similitudes, son diferentes.

		Una URL se refiere a una dirección web completa que dirige a los visitantes a una página específica, y un nombre de dominio es sólo una parte de una URL. 

		Normalmente, las URL o direcciones web constan de estos elementos

		    Un protocolo: 

		    	Puede ser HTTP (Hypertext Transfer Protocol) o HTTPS (Hypertext Transfer Protocol Secure). 

		    	Permite a los visitantes saber si un sitio está protegido con un certificado SSL.


		    Un dominio: 

		    	suele constar de un dominio de segundo nivel y un dominio de primer nivel.


		    Ruta/path:

		    	aparece sólo cuando se dirige a los visitantes a una página específica dentro de un sitio web.


		También existe el nombre de dominio completo/ fully qualified domain name (FQDN). 

		Es la versión completa de un nombre de dominio que también incluye el nombre de host, como www.		

		No confunda una URL con un FQDN.

		Una URL especifica la ubicación de un recurso en Internet. 

		En cambio, un FQDN especifica la ubicación de un ordenador o servidor en Internet.

		Una URL siempre incluye un FQDN, pero un FQDN no siempre incluye una URL. 

		Por ejemplo, la dirección web del sitio web de Google es https://www.google.com/. 

		En este ejemplo, el FQDN es www.google.com, pero la URL también incluye el protocolo https:// y la ruta /.


		Exploremos cada elemento de una jerarquía FQDN:

		    Nombre de host/Hostname:

		    	Es una etiqueta asignada a un servicio de servidor (server service) disponible en una red. 

		    	Un servidor DNS utiliza un nombre de host para que una dirección IP sea 
		    	fácil de recordar.

		    	Ejemplos de un nombre de host son "www" en www.google.com y "en" en.wikipedia.org.


		    Subdominio/Subdomain:

		    	Esta parte se encuentra a la izquierda de un dominio de segundo nivel y a veces indica una sección de un dominio mayor. 

		    	Por ejemplo, support.google.com es una parte de google.com, y la palabra "support" es el subdominio. 

		    	Tenga en cuenta que no todos los dominios tienen este elemento.


		    Nombre de dominio/Domain name: 

		    	Consta de un segundo nivel y un dominio de nivel superior (TLD). 

		    	Por ejemplo, en google.com, "google" es el dominio de segundo nivel, y ".com" es el TLD.


			La longitud máxima del nombre de host y del nombre de dominio completo es de 63 bytes por etiqueta y 255 bytes por FQDN.
 

 	Obtener un nombre de dominio:

		El registro de un nombre de dominio implica la compra de un nombre de dominio a un registrador de dominios por un periodo determinado.

		Por su parte, la transferencia de un nombre de dominio consiste en trasladar un dominio de un registrador a otro.


		Registrar un nombre de dominio:

			Si necesita ayuda para encontrar el nombre de dominio perfecto, un generador de nombres de dominio (domain name generators) es un buen punto de partida.

			Para encontrar el dominio adecuado, tenga en cuenta la marca y el coste. 

			Asegúrese de que sea memorable y se ajuste a su presupuesto.

			Tenga en cuenta que los nombres de dominio populares suelen ser más caros y pueden estar ya ocupados. 

			Algunos generadores ofrecen opciones alternativas si el dominio que quieres no está disponible. 

			Puedes elegir otro dominio de nivel superior (TLD) con el mismo nombre o uno alternativo.

			También puede utilizar una herramienta de comprobación de dominios, como la siguiente, para comprobar si el nombre que desea sigue disponible.


		Una vez que haya encontrado un nombre de dominio válido, utilice un registrador de confianza para comprar el dominio. 

		La base de datos de ICANN contiene una lista de registradores de dominios legítimos.


		Comprar nombre de dominio en un registrador legitimo:

		    Elija el nombre de dominio que desee y pase por caja.

		    Seleccione el periodo de registro de su nombre de dominio.

		    Acceda a su nueva cuenta tras el pago.

		    Complete el proceso de registro introduciendo los campos requeridos, incluyendo su nombre y dirección postal.

		
		Una vez completado el registro del dominio, podrá acceder a un panel de control con todas las herramientas de gestión esenciales.

		Puede incluir la protección de la privacidad del dominio.

		Oculta su información sensible en la base de datos WHOIS, evitando la suplantación de identidad a través de la herramienta de búsqueda WHOIS.


	Transferir un nombre de dominio:

		La transferencia de nombres de dominio es el proceso de cambiar a otro registrador de dominios.

		Un registrador de dominios diferente puede ofrecer un servicio de mejor calidad, lo que puede incitar al cambio.

		Todo lo que tiene que hacer es enviar el código de autorización de dominio (EPP) de su proveedor actual y confirmar la transferencia. 

		Este proceso puede tardar entre cuatro y siete días en completarse.

		Lamentablemente, algunas extensiones no son transferibles.

		Si un registrador de dominios no acepta determinados TLD, puede dirigir los servidores de nombres (nameservers) a una determinada empresa de alojamiento de sitios web. 

		Para ello, tendrá que cambiar los nameservers.

		Sólo puede cambiar la información del servidor web (web server information) del registrador de dominios original. 

		Si el registrador no permite cambiar nameservers, puede intentar apuntar el dominio (pointing the domain) a otro registrador utilizando el registro A (A record).



|| Application Server

	Por definición estricta, un servidor web es un subconjunto común de un servidor de aplicaciones.

	Un servidor web entrega contenido web estático -por ejemplo, páginas HTML, archivos, imágenes, vídeo- principalmente en respuesta a peticiones de protocolo de transferencia de hipertexto (HTTP) de un navegador web.

	Un servidor de aplicaciones también puede ofrecer contenidos web, pero su función principal es permitir la interacción entre los clientes finales y el código de la aplicación del lado del servidor -el código que representa lo que suele denominarse lógica empresarial (business logic)- para generar y ofrecer contenidos dinámicos, como resultados de transacciones, apoyo a la toma de decisiones o análisis en tiempo real.

	El cliente de un servidor de aplicaciones puede ser la propia interfaz de usuario final de la aplicación, un navegador web o una aplicación móvil, y la interacción cliente-servidor puede producirse a través de cualquier número de protocolos de comunicación.

	En la práctica, sin embargo, la línea que separa los servidores web de los servidores de aplicaciones es cada vez más difusa, sobre todo a medida que el navegador web se ha ido convirtiendo en el cliente de aplicaciones preferido y que han aumentado las expectativas de los usuarios sobre las aplicaciones web y su rendimiento.

	La mayoría de los servidores web admiten plug-ins para lenguajes de programación (ASP, JSP, PHP, Perl, etc.) que permiten generar contenidos dinámicos basados en la lógica del servidor. 

	Y cada vez son más los servidores de aplicaciones que no sólo incorporan funciones de servidor web, sino que utilizan HTTP como protocolo principal y admiten otros protocolos (por ejemplo, CGI y variantes de CGI) para interactuar con los servidores web. 

	También permiten a las aplicaciones web aprovechar servicios como el proxy inverso, la agrupación en clústeres, la redundancia y el equilibrio de carga, servicios que mejoran el rendimiento y la fiabilidad y permiten a los desarrolladores centrarse menos en la infraestructura y más en la codificación.

	Para mayor confusión, muchos servidores web y algunos servidores de aplicaciones se denominan, o se denominan a sí mismos, servidores de aplicaciones web.

	En resumidas cuentas, los servidores web y de aplicaciones más populares hoy en día son híbridos de ambos.

	La mayoría de las aplicaciones cada vez más ricas que utilizas hoy en día presentan una combinación de contenido web estático y contenido de aplicaciones dinámicas, entregado a través de una combinación de tecnologías de servidor web y servidor de aplicaciones.


	Servidores web y servidores de aplicaciones de código abierto: 

		El mercado está inundado de servidores web y de aplicaciones, demasiados para enumerarlos aquí. En su lugar, hemos pensado que sería más útil enumerar las opciones gratuitas de código abierto más populares:
		

		Nginx:	 

			Nginx es un servidor web de código abierto que incluye proxy inverso, equilibrio de carga, proxy de correo y caché HTTP (reverse proxy, load balancing, mail proxy). 

			Proxy: 

				Es un sistema o router que proporciona una pasarela entre los usuarios e Internet. 

				Por tanto, ayuda a impedir que los ciberatacantes entren en una red privada. 

				Es un servidor, denominado "intermediario" porque se interpone entre los usuarios finales y las páginas web que visitan en línea.

				Los servidores proxy proporcionan una valiosa capa de seguridad para su ordenador. 

				Pueden configurarse como filtros web o cortafuegos (firewalls), protegiendo tu ordenador de amenazas de Internet como el malware.

				Un servidor proxy tiene su propia dirección IP, actúa como intermediario entre un ordenador e Internet. 

				Su ordenador conoce esta dirección, y cuando usted envía una solicitud a Internet, ésta se dirige al proxy, que obtiene la respuesta del servidor web y reenvía los datos de la página al navegador de su ordenador

				Existen versiones de hardware y de software.

				Las conexiones de hardware se sitúan entre tu red e Internet, donde obtienen, envían y reenvían los datos de la web. 

				Los proxies de software suelen estar alojados por un proveedor o residir en la nube. 

				Usted descarga e instala una aplicación en su ordenador que facilita la interacción con el proxy.


			También hay disponibles versiones comerciales compatibles de Nginx, en Nginx, Inc.

			Según la empresa de investigación de Internet y prevención de la ciberdelincuencia Netcraft Nginx sirvió o proxyó casi el 38% de todos los sitios web del mundo y más del 25% del millón de sitios más concurridos en diciembre de 2019. 

			Entre los usuarios de Nginx de empresas mundialmente conocidas se incluyen Dropbox, Netflix y Zynga.
		

		Servidor HTTP Apache
		 
			Lanzado por primera vez en 1995, Apache HTTP Server (también conocido simplemente como 'Apache') es otro servidor web gratuito y de código abierto muy popular que, hasta hace muy poco, alimentaba más sitios web que cualquier otro servidor web-71% en su pico-antes de ser superado por Nginx en abril de 2019. 

			En diciembre de 2019, Apache servía a más del 24% de todos los sitios en todo el mundo y al 31% del millón de sitios más activos.


		Apache Tomcat:

			Apache Tomcat es un servidor de aplicaciones de código abierto que ejecuta Java Servlets, renderiza y entrega páginas web que incluyen código JavaServer Page y sirve aplicaciones Java Enterprise Edition (Java EE).

			Lanzado en 1998, Tomcat es el servidor de aplicaciones Java de código abierto más utilizado.
		

		Glassfish:
			 
			Glassfish es un servidor de aplicaciones Java EE de código abierto lanzado por Sun Microsystems en 2006, y actualmente está alojado en la Fundación Eclipse. 

			Como la mayoría de servidores de aplicaciones Java, Glassfish soporta Java Servlets, Enterprise JavaBeans (EJB), etc., pero también puede funcionar como servidor web, sirviendo contenidos web en respuesta a peticiones HTTP.


	Claves: 

		Los servidores web y los servidores de aplicaciones tienen procesos independientes distintos. 

		Sin embargo, son invisibles para el usuario final.

		A pesar del contraste que implica "servidor de aplicaciones frente a servidor web", en Internet ambos tipos de servidores suelen desplegarse juntos con un objetivo común: satisfacer las peticiones de contenidos de un sitio web por parte de los usuarios. 

		No existen documentos normativos que definan las propiedades de los servidores web y los servidores de aplicaciones, pero veamos cómo se entienden comúnmente estos términos.

		El trabajo fundamental de un servidor web es aceptar y satisfacer las peticiones de los clientes de contenido estático de un sitio web (páginas HTML, archivos, imágenes, vídeo, etc.).

		El cliente es casi siempre un navegador o una aplicación móvil y la petición adopta la forma de un mensaje HTTP (Hypertext Transfer Protocol), al igual que la respuesta del servidor web.	

		El trabajo fundamental de un servidor de aplicaciones es proporcionar a sus clientes acceso a lo que comúnmente se denomina lógica de negocio, que genera contenido dinámico; es decir, es código que transforma datos para proporcionar la funcionalidad especializada que ofrece un negocio, servicio o aplicación. 

		Los clientes de un servidor de aplicaciones suelen ser las propias aplicaciones, y pueden incluir servidores web y otros servidores de aplicaciones. 

		La comunicación entre el servidor de aplicaciones y sus clientes puede adoptar la forma de mensajes HTTP, pero no es tan necesaria como para la comunicación entre los servidores web y sus clientes. 

		Muchos otros protocolos son populares, incluyendo las variantes de CGI.

		En un despliegue típico, un sitio web que proporciona contenidos tanto estáticos como generados dinámicamente ejecuta servidores web para los contenidos estáticos y servidores de aplicaciones para generar contenidos dinámicamente.

		Un reverse proxy y un load balancer se sitúan frente a uno o varios servidores web y uno o varios servidores de aplicaciones web para dirigir el tráfico al servidor adecuado, primero en función del tipo de contenido solicitado y después en función del algoritmo de equilibrio de carga configurado.

		La mayoría de los programas equilibradores de carga son también servidores proxy inversos, lo que simplifica la arquitectura de los servidores de aplicaciones web.


	Diferencias entre un servidor web y un servidor de aplicaciones: 	

		Un servidor web es una tecnología que aloja el código y los datos de un sitio web. Al ingresar una URL en el navegador, la URL es en realidad el identificador de dirección del servidor web.

		Su navegador y servidor web se comunican de la siguiente manera:

		    El navegador usa la URL para encontrar la dirección IP del servidor.

		    El navegador envía una solicitud HTTP de información.

		    El servidor web se comunica con un servidor de base de datos para encontrar los datos relevantes.

		    El servidor web devuelve contenido estático, como páginas HTML, imágenes, videos o archivos, en una respuesta HTTP al navegador.

		    A continuación, el navegador le mostrará la información.


		Un sitio web que aloja contenido estático, como blogs, imágenes de encabezado o artículos, puede ejecutarse en un servidor web.

		Sin embargo, la mayoría de los sitios web y aplicaciones web son mucho más interactivos y requieren un servidor de aplicaciones.


		Un servidor de aplicaciones amplía las capacidades de un servidor web, pues admite la generación de contenido dinámico, la lógica de la aplicación y la integración con varios recursos.

		Proporciona un entorno de tiempo de ejecución en el que puede ejecutar el código de la aplicación e interactuar con otros componentes de software, como los sistemas de mensajería y las bases de datos. 

		Utiliza la lógica empresarial para transformar los datos de manera más significativa que un servidor web.
		
		Cuando intenta acceder al contenido interactivo de un sitio web, el proceso funciona de la siguiente manera:

		    El navegador usa la URL para encontrar la dirección IP del servidor.

		    El navegador envía una solicitud HTTP de información.

		    El servidor web transfiere la solicitud al servidor de aplicaciones.

		    El servidor de aplicaciones aplica la lógica empresarial y se comunica con otros servidores y sistemas de terceros para cumplir con la solicitud.

		    El servidor de aplicaciones representa una nueva página HTML y la devuelve como respuesta al servidor web.

		    El servidor web devuelve la respuesta al navegador.

		    El navegador le muestra la información.

		Para usar el ejemplo de un sitio web de comercio electrónico, cuando agrega artículos a su carrito o retira artículos, interactúa con el servidor de aplicaciones.


		Tareas realizadas:

			Un servidor web aloja sitios web y entrega respuestas a solicitudes sencillas. 

			Los servidores web también registran la actividad del servidor y permiten la creación de secuencias de comandos en el servidor.

			Por otro lado, los servidores de aplicaciones tienen un conjunto de tareas más complejo. 

			Los servidores de aplicaciones gestionan la lógica empresarial para generar contenido dinámico mediante la conexión con sistemas, servicios y bases de datos empresariales.


		Protocolos utilizados:

			El protocolo principal que utilizan los servidores web es el protocolo HTTP. 

			Sin embargo, diferentes servidores web también admiten FTP y Simple Mail Transfer Protocol (SMTP). 

			Estos dos protocolos facilitan el almacenamiento y la transferencia de archivos, así como el funcionamiento del correo electrónico.

			Además de los protocolos que utilizan los servidores web, los servidores de aplicaciones utilizan protocolos de comunicación adicionales para comunicarse con otros componentes de software. 

			Por ejemplo, pueden usar la invocación de métodos remotos (RMI) y la llamada a procedimiento remoto (RPC).
		

		Tipos de contenidos:

			Los servidores web ofrecen en su mayoría contenido estático. 

			El contenido estático es el contenido que un servidor no necesita modificar o procesar antes de entregarlo. 

			Por ejemplo, los archivos de imagen (como PNG, GIF y JPEG), los documentos descargables (PDF), los videos y los archivos HTML son todos contenidos estáticos. 

			Los servidores de aplicaciones ofrecen en su mayoría contenido dinámico.

			El contenido dinámico es el contenido que cambia en función de la forma en que el usuario interactúa con él.

			Por ejemplo, los informes generados dinámicamente, las representaciones de datos personalizadas, las interfaces de usuario personalizadas, los resultados de las bases de datos y el HTML procesado son todos contenidos dinámicos.


		Subprocesamiento múltiple:

			Los subprocesos de un servidor son vías de operación independientes que permiten el procesamiento simultáneo de tareas. 

			En el subprocesamiento múltiple, el servidor crea y ejecuta varios subprocesos simultáneamente y cada uno gestiona una tarea independiente o parte de una tarea. 

			La compatibilidad con subprocesos múltiples ayuda a entregar contenido web más rápido y, al mismo tiempo, a administrar más tráfico web.

			La mayoría de los servidores web no admiten subprocesos múltiples. 

			Los servidores web colocan cada nueva solicitud de conexión en una cola y utilizan un bucle de eventos para supervisar las nuevas entradas y salidas de la cola. 

			Para mejorar la eficiencia, el servidor procesa las solicitudes mediante E/S sin bloqueo y devoluciones de llamadas. 

			Las operaciones sin bloqueo y la arquitectura basada en eventos permiten a los servidores web gestionar conexiones simultáneas.

			Los servidores de aplicaciones utilizan subprocesos múltiples para proporcionar una alta escalabilidad y eficiencia.

			Si una solicitud requiere recursos externos, el servidor de aplicaciones usa subprocesos independientes para hacer frente a esas interacciones. 

			Puede procesar varios subprocesos a la vez, lo que permite muchas interacciones con los clientes en paralelo. 



|| CMS/CRM

	Hay casos de en los que no se necesita una lógica de negocio o de aplicación como la que puede proveer los servidores de aplicaciones con una compleja base de datos que pueda generar contenido dinámico y personalizado para el usuario. 

	Solo se necesita una plataforma para publicar contenido que se pueda comunicar, ver, leer, vender o una plataforma para administrar un negocio. 


	Content Management System (CMS): 

		Un sistema de gestión de contenidos (CMS) es una aplicación de software que se ejecuta en un navegador.

		Proporciona a los usuarios una interfaz gráfica de usuario que les permite crear y gestionar un sitio web sin necesidad de programarlo desde cero. 

		Con un CMS, se puede personalizar el diseño de un sitio web descargando y modificando plantillas y extensiones prediseñadas. 

		Algunas de sus funciones también incluyen la gestión y modificación de contenidos, el almacenamiento de imágenes y la creación de páginas web. 

		Hay muchos sistemas de gestión de contenidos disponibles en la red, cada uno con sus puntos fuertes y débiles. 


	Existen varios tipos de sistemas de gestión de contenidos:

		Un sistema de gestión de contenidos (CMS) es una aplicación de software que se encarga de la infraestructura básica de creación de sitios web.

		Con un CMS, los usuarios pueden centrarse en las áreas front-end de la creación de sitios web, como la personalización del diseño del sitio web y la gestión de contenidos. 


	    CMS de código abierto: 

	    	Una comunidad de desarrolladores mantiene el software en lugar de que sea propiedad de una sola empresa. 

	    	Los desarrolladores externos tienen acceso al código fuente y pueden desarrollar y mejorar las funcionalidades del software.  


	    CMS en la nube:

	    	Un sistema preconstruido accesible sin necesidad de descargar hardware o software. 

	    	Los usuarios pueden gestionar contenidos web de forma segura a través de la nube y acceder a ellos fácilmente desde múltiples dispositivos.


	    CMS propietario: 

	    	Tiene un coste de licencia, ya que es propiedad legal de la empresa, organización o persona que lo ha creado. 

	    	El coste puede ser un pago inicial único, una cuota mensual o un cargo anual.


	Funcionamiento de un sitio web y de los CMS: 

		Para entender cómo funciona un sistema de gestión de contenidos, primero hay que saber qué es un sitio web y cómo se construye uno desde cero.

		Un sitio web consta de dos partes principales: 

			El front-end es la parte que el usuario final ve en su navegador, como entradas de blog, galerías y vídeos.

			Comprende lenguajes de marcado estándar llamados HTML, lenguaje de hojas de estilo CSS y JavaScript.

		Por su parte, el back-end consiste en la base de datos y la funcionalidad de un sitio web.

		Los distintos lenguajes de programación que se utilizan en su construcción son PHP, Python, Ruby y Java. 

		Para que su sitio web sea visible en la web, también tiene que cargar manualmente todo el contenido de su sitio web en un servidor web. 

		La base de datos del servidor web almacenará el contenido y lo enviará del back-end al front-end cada vez que un usuario acceda al sitio. 

		Un sistema de gestión de contenidos permite agilizar estos procesos. 

		Además de eliminar la necesidad de codificar, un sistema de gestión de contenidos también facilita la carga de contenidos. 

		El editor de contenidos, muy fácil de usar, permite crear sin problemas entradas y páginas.

		Además de archivos basados en texto, como documentos .PDF, el software editor de contenidos también permite organizar páginas web, imágenes, vídeos, texto y archivos de audio, entre otros tipos de archivos.

		La mayoría de los software CMS también le proporcionan una interfaz a través de la cual puede tener el control de las revisiones. 

		También puede utilizarlo para configurar los ajustes de su sitio web y establecer sistemas de permisos. 

		Todo el proceso es sencillo y no requiere conocimientos técnicos.

		Ten en cuenta que un sistema de gestión de contenidos es diferente de un sistema de gestión de contenidos empresariales (ECM). 

		El ECM se centra más en la gestión de documentos y procesos relacionados con la empresa, como la digitalización de documentos en papel para una mejor organización, seguridad y trazabilidad.


	Características de un CMS: 

		Un sistema de gestión de contenidos consta de dos elementos básicos: la aplicación de gestión de contenidos (CMA) y la aplicación de entrega de contenidos (CDA).

		La CMA gestiona la entrada de contenidos del sitio, permitiendo a los usuarios añadir, gestionar y modificar el contenido con facilidad. 

		El front-end del software CMS suele incluir un editor de tipo "lo que ves es lo que obtienes" (WYSIWYG: what you see is what you get) que puede utilizarse para crear y publicar el contenido del sitio.

		Mientras tanto, el CDA sirve como back-end del software CMS. 

		El CDA almacena y gestiona el contenido que los propietarios del sitio introducen a través del CMA y lo publica para que sea visible para los visitantes del sitio. 

		Todos los cambios realizados en las páginas web pasan por esta parte del CMS.


	Plugins, extensiones y temas para un CRM: 

		Por defecto, los sistemas de gestión de contenidos permiten crear entradas y páginas y modificar el diseño general del sitio web. 

		Otras funciones, como la optimización para motores de búsqueda (SEO), las funciones de búsqueda, la seguridad y otras personalizaciones, están disponibles a través de extensiones como plugins y temas.

		Una extensión o un plugin es un componente de software que conlleva una funcionalidad específica. 

		Al añadirlo a un sitio web se amplían sus capacidades o se integra el sistema del sitio web con un servicio de terceros.

		La mayoría de las plataformas CMS tienen sus propios directorios de extensiones o plugins. 

		Por ejemplo, WordPress tiene miles de plugins gratuitos en su directorio oficial de plugins.

		Algunos CMS también permiten adquirirlos en mercados de plugins de terceros como CodeCanyon y Mojo Marketplace.

		En cuanto a cambiar la apariencia de tu sitio web, puedes hacerlo instalando un tema. 

		Se trata de un conjunto de archivos de plantilla que proporcionan a un sitio una interfaz visual coherente sin afectar a su funcionalidad básica. 

		Ten en cuenta que un tema suele estar orientado a un nicho específico en cuanto a diseño y funciones. 

		Sin embargo, puedes editar los archivos para añadir o eliminar algunos elementos visuales y gráficos y modificar la combinación de colores. 

		Al igual que los plugins, los temas se pueden descargar a través del directorio de temas del CMS o de mercados de terceros. 

		El proceso de instalación de ambos componentes es relativamente sencillo.

		Configurarlos y modificarlos puede requerir algunos conocimientos técnicos básicos, pero son más fáciles de aprender en comparación con aprender a programar desde cero.


	CMS populares: 

		Dado que cada plataforma CMS se dirige a necesidades de usuario diferentes, es esencial que determine sus objetivos para el resultado final. 

		A continuación se enumeran algunas de las plataformas de sistemas de gestión de contenidos web (WCMS) más populares.


		WordPress: 

			WordPress, que ocupa el 42,9% de Internet, es el sistema de gestión de contenidos web más popular del mercado actual.

			Este CMS gratuito y autoalojado comenzó como una plataforma de publicación de blogs, lo que le permitió contar con sólidas herramientas de gestión de contenidos. 

			WordPress puede alojar todo tipo de sitios web, desde tiendas de comercio electrónico hasta sitios de aprendizaje y portafolios sencillas. 

			Viene con una enorme colección de plugins y temas relativamente fáciles de configurar. 

			Por este motivo, WordPress es muy versátil y escalable.

			Al ser una plataforma de código abierto, WordPress cuenta con una gran comunidad y multitud de foros. 

			Los propietarios de sitios web pueden ponerse en contacto con otros usuarios de WordPress o consultar sitios web de tutoriales de WordPress para obtener ayuda. 

			Esto es especialmente beneficioso para los principiantes, ya que WordPress tiene una pronunciada curva de aprendizaje.


		Drupal: 	

			Drupal es uno de los sistemas de gestión de contenidos web más potentes del mercado.

			Grandes empresas y entidades gubernamentales como la NASA, Tesla, Sony Music y Nokia lo utilizan para gestionar sus contenidos web en línea. 

			Drupal ofrece un tiempo de carga de página excelente y herramientas de seguridad avanzadas. 

			También viene con módulos incorporados, lo que le permite integrar su sitio web con herramientas de análisis populares, así como funciones de marketing y comercio electrónico.

			Dicho esto, para crear un sitio web con Drupal sólo necesita servicios de alojamiento y conocimientos básicos de programación. 

			Esta plataforma CMS está diseñada para profesionales, por lo que los principiantes pueden encontrar su interfaz mucho más complicada que la de WordPress.


		PrestaShop: 

			PrestaShop es un sistema de gestión de contenidos cada vez más popular entre las pequeñas y medianas empresas de comercio electrónico. 

			Una de las ventajas de utilizar este software CMS es su sencillo proceso de integración y el acceso a herramientas de comercio electrónico fáciles de usar, que permiten a usuarios de todos los niveles crear una tienda online profesional.

			Además de ser fácil de usar, PrestaShop también es compatible con varias divisas e idiomas. 

			También dispone de herramientas SEO para mejorar el posicionamiento de su tienda en las SERPs.

			Sin embargo, la escalabilidad limitada de Prestashop hace que no sea adecuado para las empresas a gran escala.

			Tendrá que comprar módulos y plantillas premium para ampliar su tienda. 

			Además, se necesitará un alojamiento fiable para Prestashop para poner en marcha su sitio web.


		Magento: 

			Magento es una popular plataforma de comercio electrónico para tiendas en línea de mediana y gran escala. 

			Samsung, Nike y Ford son algunas de las muchas grandes empresas que utilizan Magento por su escalabilidad y sus avanzadas opciones de personalización. 

			Magento está disponible en dos versiones: código abierto y Commerce. 

			La versión gratuita de código abierto viene con un montón de características, como la venta global, la búsqueda en el sitio y la gestión de catálogos. 

			Para acceder a funciones premium y soporte, tiene que comprar la versión Commerce de Magento, cuyo coste depende de sus necesidades individuales.


		Joomla!: 

			Joomla! es otro excelente sistema de gestión de contenidos de código abierto.

			Al igual que WordPress, Joomla admite todo tipo de sitios web, ya sean para uso personal o empresarial.

			Una de sus ventajas más significativas es que puedes gestionar el contenido en partes segregadas, lo que resulta ideal para sitios web con múltiples tipos de contenido. 

			Las funciones de revisión de Joomla también le permiten modificar archivos de forma segura. 

			Dado que Joomla requiere ciertos conocimientos técnicos, es más adecuado para desarrolladores y usuarios con experiencia en desarrollo web. 

			Para los principiantes, optar por Joomla alojamiento web, ya que es una solución optimizada para Joomla que viene con herramientas de gestión de alojamiento fácil de usar para hacer su trabajo más fácil.


		Otras opciones: 

		    Squarespace:

		    	Un CMS centrado en el comercio electrónico con aplicaciones móviles para ayudarle a gestionar el contenido sobre la marcha.


		    Ghost:

		    	Un CMS sin cabeza donde su repositorio de contenido está separado de la capa de presentación.


		    Webflow:

		    	Un WCMS con toneladas de opciones de personalización y excelentes funciones de gestión de formatos, ideal para diseñadores y agencias.


	Ventajas y desventajas de un CRM: 	

		A pesar de su facilidad de uso y abundantes funciones, utilizar un sistema de gestión de contenidos también tiene algunos inconvenientes. 

		A continuación se exponen los pros y los contras de utilizar un sistema de gestión de contenidos web (WCMS) para construir y gestionar su sitio.


		Ventajas:

		    Facilidad de uso: 

		    	No hace falta saber programar para utilizar un CMS. 

		    	También puedes obtener soporte para las extensiones y plantillas si eliges las opciones premium.


		    Rentable: 

		    	La mayoría de las plataformas CMS son de uso gratuito y ofrecen extensiones y plantillas gratuitas.


		    Altamente escalable:

		    	la instalación de extensiones y plugins añadirá nuevas características a su sitio web, por lo que es más fácil de modificar según sea necesario. 

		    	Hay multitud de opciones disponibles en directorios oficiales y sitios web de terceros.


		    Funcionalidad de gestión de usuarios:

		    	Todo sistema de gestión de contenidos, como WordPress, permite configurar diferentes roles y privilegios de usuario dentro del sitio.


		    Bien documentado:

		    	Documentación en línea, páginas de preguntas frecuentes, descripciones de extensiones y plantillas, tutoriales y vídeos están disponibles para ayudar a los principiantes a empezar.


		Desventajas: 

			Riesgos de seguridad: 

				No actualizar las extensiones y plantillas con regularidad puede crear vulnerabilidades que los hackers pueden explotar. 

				Por eso los piratas informáticos tienden a atacar sobre todo los sitios web con CMS.


		    SEO mínimo:

		    	Algunas plataformas CMS pueden proporcionar algunas herramientas SEO, pero su sitio web seguirá necesitando optimización manual para motores de búsqueda y extensiones adicionales para subir en las SERPs.


		    Flexibilidad limitada:

		    	Implementar funciones específicas en algunos CMS será un reto sin tener conocimientos técnicos o contratar a un desarrollador.		    


	Consideraciones para elegir un CMS: 

		Dado que cada sistema de gestión de contenidos presenta diferentes puntos fuertes y débiles, es fundamental elegir el más adecuado para su proyecto.


	    Tipo de sitio web: 

	    	Asegúrese de que el CMS elegido dispone de todas las herramientas necesarias para su tipo de sitio web. 

	    	Por ejemplo, WordPress es el mejor para crear blogs, mientras que Magento es ideal para desarrollar sitios de comercio electrónico. 


	    Coste: 

	    	Aunque la mayoría de los sistemas de gestión de contenidos son gratuitos, suelen vender funciones adicionales como productos individuales.

	    	Compruebe si el coste total se ajusta a su presupuesto.


	    Escalabilidad:

	    	Elegir un CMS con un amplio directorio de extensiones y plantillas le ofrece más opciones a la hora de crear su sitio web. 

	    	Asegúrese también de comprobar los requisitos de servidor de las extensiones que desee utilizar.


	    SEO:

	    	El CMS que elija debe ser capaz de optimizar sus páginas web para los rastreadores de los motores de búsqueda.


	    Marketing: 

	    	La capacidad de realizar marketing por correo electrónico y redes sociales también ayuda a impulsar sus esfuerzos de SEO.


	    Seguridad: 

	    	Asegúrese de que las funciones de seguridad integradas en el CMS están actualizadas y son capaces de anticiparse a todos los tipos de malware.


	CMS vs Website builders: 

		Es fácil confundir un sistema de gestión de contenidos (CMS) con un creador de sitios web, otro tipo de software popular para crear sitios web sin tener que codificar.


	    Alojamiento: 

	    	Mientras que los creadores de sitios web suelen proporcionar servicios de alojamiento junto con su producto, el software CMS suele ser autoalojado, por lo que los usuarios pueden elegir los servicios de alojamiento web por separado.

	    	Optar por el alojamiento CMS será lo más ideal, ya que el servicio está optimizado específicamente para este tipo de sitios web.


    	Facilidad de uso: 

    		Los creadores de sitios web suelen ofrecer editores fáciles de usar para crear contenidos y personalizar un sitio. 

    		Mientras tanto, algunas plataformas CMS pueden tener una curva de aprendizaje más pronunciada para los usuarios no técnicos debido a la naturaleza de sus interfaces. 


	    Escalabilidad: 

	    	La mayoría de los CMS, especialmente los de código abierto, ofrecen una gran variedad de extensiones y plugins para ampliar un sitio. 

	    	Los creadores de sitios web, sin embargo, suelen estar más limitados en cuanto al crecimiento del sitio.


	Requisitos para hacer funcionar un CMS: 	

		Antes de utilizar un CMS, hay que contratar un servicio de alojamiento web que permita almacenar todos los contenidos, archivos y bases de datos necesarios para el sitio web. 

		Asegúrese de que el proveedor de alojamiento es compatible con el CMS elegido. 

		Por ejemplo, los planes de alojamiento WordPress están diseñados específicamente para sitios web WordPress. 

		No dude en consultar varias soluciones de alojamiento CMS de Hostinger y elija la más adecuada para su plataforma CMS.

		El siguiente paso es registrar un dominio. 

		Algunos proveedores de alojamiento incluyen nombres de dominio gratuitos con la mayoría de los planes de alojamiento. 

		Alternativamente, puede registrar uno a través de un registrador de dominios. 

		Una vez asegurados el alojamiento y el dominio, es hora de configurar el CMS desde la cuenta de alojamiento. 

		La mayoría de los proveedores de alojamiento web ofrecen a los usuarios la posibilidad de configurar el CMS con un solo clic para agilizar este proceso.

		Cuando el CMS esté en funcionamiento, podrás acceder al panel de control con el nombre de dominio registrado para empezar a personalizar tu sitio web y añadir contenido.

		Asegúrese de que el proveedor de alojamiento es compatible con el CMS que ha elegido. 


	Claves de los CRM: 

		Un sistema de gestión de contenidos (CMS) permite crear y gestionar un sitio web profesional sin conocimientos de programación y a un coste mínimo. 

		Además de su precio rentable, el principal atractivo de un CMS es su capacidad de personalización.

		Gracias a las plantillas y extensiones prediseñadas, podrá elegir el diseño y las funciones que mejor se adapten a sus necesidades. 

	
	What you see is what you get (WYSIWYG):	

		Un editor "lo que ves es lo que obtienes" (WYSIWYG) es una aplicación de software que contiene una interfaz que permite a los usuarios ver el resultado final del contenido mientras lo editan. 

		Se suele utilizar en procesadores de texto, creadores de sitios web, sistemas de gestión de contenidos (CMS) y software de gestión de relaciones con los clientes (CRM).

		En comparación con otros editores, las aplicaciones WYSIWYG permiten editar contenidos visualmente sin codificar. 

		Ofrecen a los usuarios opciones de diseño y formato preestablecidas para añadir elementos, como imágenes, texto y vídeos, arrastrando y soltando el elemento en cualquier lugar de la página.


		Funcionamiento de los editores WYSIWYG: 

			Existen muchos editores WYSIWYG, pero su funcionamiento varía en función de sus características y capacidades. 

			En general, estas plataformas incluyen lo siguiente.


		    Interfaz gráfica de usuario:

		    	Ofrece un editor visual con opciones de formato, botones y menús para crear o manipular elementos como tablas, listas, imágenes, contenido escrito y enlaces.


		    Creación de contenidos en directo:

		    	A medida que trabajas en el contenido, como añadir imágenes o modificar el formato, puedes verlos renderizados en la pantalla del editor en tiempo real.
		    

		    Código autogenerado: 

		    	El editor WYSIWYG genera código o lenguajes de marcado como CSS y Lenguaje de Marcado de Hipertexto (HTML) según las modificaciones del usuario.


		    Vista previa de la página y publicación:

		    	Muchos editores WYSIWYG disponen de una función de vista previa que permite ver el aspecto final del contenido antes de ponerlo en línea. 

		    	Una vez que esté satisfecho con los resultados, puede publicar con un solo clic.


		Ventajas y desventajas de los WYSIWYG website builders: 

			Ventajas: 

				Edición sin código:

					Un editor WYSIWYG ofrece una interfaz sin código que permite crear, formatear y modificar elementos visualmente. 

					Con una curva de aprendizaje poco pronunciada, es perfecto para usuarios sin conocimientos técnicos ni habilidades de codificación.


				Fácil de usar y centrado en el diseño:

					Un editor WYSIWYG permite a los usuarios centrarse en la creación de una apariencia elegante del sitio web fácilmente sin prestar atención al código HTML específico. 

					Suele venir con diseños o plantillas prefabricadas que puedes modificar para que tu sitio web destaque entre la competencia.


				Flujo de trabajo eficaz:

					Con un editor WYSIWYG, puedes crear y editar elementos web en línea, lo que lo hace excelente para la colaboración.

					Además, los errores pueden resolverse fácilmente modificando elementos sin necesidad de despublicar y volver a publicar, lo que agiliza los flujos de trabajo.


				Publicación rápida:

					La publicación es más rápida utilizando un editor WYSIWYG, ya que no es necesario formatear el contenido del sitio manualmente desde cero. 

					Incluye una función de publicación rápida que publica automáticamente el producto final en línea.


			Desventajas: 	

				Genera una cantidad excesiva de código:

					Muchos editores WYSIWYG tienden a generar código excesivo o no conforme. 

					En el primer caso, suele contener código hinchado y de mala calidad que puede hacer que su página se cargue lentamente.

					Por su parte, el código no conforme puede romper las convenciones del sitio web y afectar a la usabilidad.


				Funcionalidad de diseño limitada:

					Algunos constructores web WYSIWYG ofrecen funciones de diseño limitadas, que sólo permiten crear un sitio web estándar.

					Como tal, aquellos que construyen sitios complejos pueden necesitar utilizar CSS o código personalizado para ampliar la funcionalidad, ya que puede no ser posible utilizando las herramientas proporcionadas.


				Oportunidades limitadas de optimización para motores de búsqueda:

					Con algunos constructores web WYSIWYG, no puedes incluir explícitamente etiquetas de encabezado o atributos alt. 

					Esto puede dificultar que su sitio web sea reconocido por los motores de búsqueda.

					Sin embargo, los editores WYSIWYG más modernos incorporan funciones de optimización para motores de búsqueda (SEO).



	CRM: 

		Customer relationship management (CRM) es una tecnología para gestionar todas las relaciones e interacciones de su empresa con clientes y clientes potenciales. 

		El objetivo es sencillo: Mejorar las relaciones comerciales para hacer crecer su negocio. 

		Un sistema CRM ayuda a las empresas a mantenerse conectadas con los clientes, agilizar los procesos y mejorar la rentabilidad.

		Cuando la gente habla de CRM, suele referirse a un sistema CRM, una herramienta que ayuda en la gestión de contactos, la gestión de ventas, la productividad de los agentes y mucho más. 

		En la actualidad, las herramientas CRM pueden utilizarse para gestionar las relaciones con los clientes a lo largo de todo su ciclo de vida, abarcando el marketing, las ventas, el comercio digital y las interacciones con el servicio de atención al cliente.

		Una solución CRM le ayuda a centrarse en las relaciones de su organización con personas individuales -incluidos clientes, usuarios de servicios, colegas o proveedores- a lo largo de su ciclo de vida con ellos, incluida la búsqueda de nuevos clientes, la captación de sus negocios y la prestación de asistencia y servicios adicionales a lo largo de la relación.


	Propósito de un CRM: 

		Un sistema CRM ofrece a todo el mundo -desde ventas, atención al cliente, desarrollo empresarial, contratación, marketing o cualquier otra línea de negocio- una forma mejor de gestionar las interacciones y relaciones externas que impulsan el éxito.

		Una herramienta CRM le permite almacenar información de contacto de clientes y clientes potenciales, identificar oportunidades de venta, registrar problemas de servicio y gestionar campañas de marketing, todo ello en una ubicación central, y poner la información sobre cada interacción con el cliente a disposición de cualquier persona de su empresa que pueda necesitarla.

		Con visibilidad y fácil acceso a los datos, es más fácil colaborar y aumentar la productividad.

		Todos los miembros de su empresa pueden ver cómo se han comunicado con los clientes, qué han comprado, cuándo lo hicieron por última vez, cuánto han pagado y mucho más. 

		CRM puede ayudar a empresas de todos los tamaños a impulsar el crecimiento del negocio, y puede ser especialmente beneficioso para una pequeña empresa, donde los equipos a menudo necesitan encontrar formas de hacer más con menos.


	Ventajas de un CRM: 

		Para que su empresa perdure, necesita una estrategia de futuro centrada en sus clientes y dotada de la tecnología adecuada. 

		Usted tiene metas de ventas, objetivos empresariales y rentabilidad. 

		Pero obtener información actualizada y fiable sobre su progreso puede ser complicado.

		¿Cómo traduce los numerosos flujos de datos procedentes de las ventas, el servicio de atención al cliente, el marketing y el seguimiento de las redes sociales en información empresarial útil?

		Un sistema CRM puede ofrecerle una visión clara de sus clientes.

		Puede verlo todo en un único lugar: un panel de control sencillo y personalizable que le informa del historial de un cliente con usted, el estado de sus pedidos, cualquier problema pendiente con el servicio de atención al cliente y mucho más.

		Incluso puede incluir información de su actividad pública en las redes sociales: lo que les gusta y lo que no, lo que dicen y comparten sobre usted o sus competidores. 

		Los profesionales del marketing pueden utilizar una solución de CRM para gestionar y optimizar las campañas y los recorridos de los clientes potenciales con un enfoque basado en datos, y comprender mejor la cartera de ventas o los clientes potenciales que llegan, lo que simplifica las previsiones y las hace más precisas. 

		Tendrá una visibilidad clara de cada oportunidad o cliente potencial, lo que le mostrará una ruta clara desde las consultas hasta las ventas.

		Algunas de las mayores ganancias en productividad y en el cambio de toda la empresa hacia un enfoque centrado en el cliente pueden venir de ir más allá del CRM como mera herramienta de ventas y marketing, e integrarlo en su negocio, desde las finanzas a los servicios al cliente y la gestión de la cadena de suministro. 

		Esto ayuda a garantizar que las necesidades del cliente estén en primera línea de los procesos empresariales y los ciclos de innovación.

		Aunque los sistemas CRM se han utilizado tradicionalmente como herramientas de ventas y marketing, el servicio y la atención al cliente son un segmento en alza del CRM y una pieza fundamental en la gestión de una relación holística con el cliente. 

		El cliente de hoy puede plantear un problema en un canal -por ejemplo, Twitter- y luego pasar al correo electrónico o al teléfono para resolverlo en privado. 

		Una plataforma de CRM permite gestionar la consulta a través de los distintos canales sin perder el hilo, y ofrece a los departamentos de ventas, servicios y marketing una visión única del cliente que sirve de base para sus actividades. 

		La capacidad de conectar estas tres funciones, y los equipos que las llevan a cabo, en una sola plataforma y con una sola visión del cliente, tiene un valor incalculable para ofrecer experiencias relevantes y conectadas.


	Desventajas de un CRM: 

		Más administración significa menos tiempo para todo lo demás.

		Un equipo de ventas activo puede generar una avalancha de datos.

		Los representantes se desplazan para hablar con los clientes, reunirse con posibles clientes y obtener información valiosa, pero con demasiada frecuencia esta información se almacena en notas manuscritas, ordenadores portátiles o dentro de las cabezas de los vendedores.

		Los detalles pueden perderse, no se hace un seguimiento puntual de las reuniones y priorizar a los clientes puede ser una cuestión de conjeturas en lugar de un ejercicio riguroso basado en datos. 

		Y todo esto puede agravarse si un vendedor clave se marcha. 

		Pero no sólo las ventas sufren sin CRM.

		Sus clientes pueden ponerse en contacto con usted a través de distintas plataformas (teléfono, correo electrónico o redes sociales) para hacerle preguntas, realizar el seguimiento de un pedido o plantearle un problema.

		Sin una plataforma común para las interacciones con los clientes, las comunicaciones pueden perderse o perderse en la avalancha de información, lo que provoca una respuesta lenta o insatisfactoria.

		Incluso si consigue recopilar todos estos datos, se enfrenta al reto de darles sentido, puede ser difícil extraer información. 

		Los informes pueden ser difíciles de crear y pueden hacer perder un valioso tiempo de venta. 

		Los directivos pueden perder de vista lo que hacen sus equipos, lo que significa que no pueden ofrecer el apoyo adecuado en el momento oportuno, mientras que la falta de supervisión también puede dar lugar a una falta de responsabilidad por parte del equipo.


	Características de un CRM: 

		Una solución de gestión de las relaciones con los clientes (CRM) le ayuda a encontrar nuevos clientes, captarlos y mantenerlos satisfechos organizando la información sobre clientes actuales y potenciales de forma que pueda establecer relaciones más sólidas con ellos y acelerar el crecimiento de su negocio. 

		Los sistemas de CRM empiezan recopilando los datos del sitio web, el correo electrónico, el teléfono y las redes sociales de un cliente, entre otros, a través de múltiples fuentes y canales.

		También puede extraer automáticamente otra información, como noticias recientes sobre la actividad de la empresa, y puede almacenar datos personales, como las preferencias personales de un cliente en las comunicaciones. 

		La herramienta CRM organiza esta información para ofrecerle un registro completo de individuos y empresas en general, de modo que pueda comprender mejor su relación a lo largo del tiempo.

		Con una visión consolidada de cada cliente potencial y cliente, un sistema CRM se utiliza para gestionar las actividades e interacciones diarias con los clientes. 

		Desde el punto de vista del marketing, esto significa atraer a sus clientes potenciales con el mensaje adecuado, en el momento oportuno, a través de campañas y recorridos de marketing digital específicos. 

		En cuanto a las ventas, los representantes pueden trabajar de forma más rápida e inteligente con una visión clara de su cartera y realizar previsiones más precisas. 

		Los equipos de comercio pueden lanzar y ampliar rápidamente el comercio electrónico -desde los pedidos en línea hasta la recogida en la acera- para sus compradores particulares (comercio B2C) y empresariales (comercio B2B). 

		Y los agentes de atención al cliente pueden responder a las necesidades de los clientes en cualquier canal: desde casa, sobre el terreno o en la oficina.

		Una plataforma CRM también puede conectarse a otras aplicaciones empresariales que le ayuden a desarrollar relaciones con los clientes. 

		Las soluciones CRM actuales son más abiertas y pueden integrarse con sus herramientas empresariales favoritas, como la firma de documentos, la contabilidad y la facturación, y las encuestas, de modo que la información fluye en ambos sentidos para ofrecerle una verdadera visión de 360 grados de su cliente.
		
		Y una nueva generación de CRM va un paso más allá: La inteligencia y la IA integradas automatizan las tareas administrativas, como la introducción de datos y el enrutamiento de clientes potenciales o casos de servicio, para que pueda dedicar tiempo a actividades más valiosas. 

		La información generada automáticamente le ayuda a comprender mejor a sus clientes, incluso a predecir cómo se sentirán y cómo actuarán, para que pueda preparar el acercamiento adecuado. 

		La IA también le ayuda a encontrar oportunidades que pueden estar ocultas en los datos de su empresa.


	Herramientas de los CRM: 

		Silos: 

			El 56% de los directivos admite que los silos organizativos repercuten negativamente en la calidad de la experiencia de sus clientes actuales y potenciales. 

			Los silos de información son un gran problema, pero una plataforma y un proceso compartidos para gestionar las relaciones con los clientes en todas las funciones pueden ser de gran ayuda. De hecho, el 80% de los líderes empresariales del mismo estudio afirman que utilizan cada vez más el CRM de su empresa como única fuente de información sobre sus clientes en todos los departamentos.

			Con un CRM compartido, los empleados disponen de las herramientas y los datos adecuados para gestionar las relaciones con los clientes de forma más eficaz en todas las líneas de negocio, y tienen visibilidad de las interacciones con los clientes de otros departamentos. 

			Pueden trabajar juntos de forma más eficaz y eficiente para ofrecer experiencias de cliente conectadas.


		Cuenta de resultados: 

			Se ha demostrado que la introducción de una plataforma CRM produce resultados reales, incluidas mejoras directas en los resultados finales. 

			Los clientes globales de todos los tamaños de empresa tienen un historial probado de producir lo siguiente

			Se ha demostrado que la introducción de una plataforma CRM produce resultados reales, incluidas mejoras directas en los resultados finales.


		Clasificación de clientes: 

			Un sistema CRM puede ayudarle a identificar y añadir nuevos clientes potenciales de forma fácil y rápida, y a clasificarlos con precisión.

			Al centrarse en los clientes potenciales adecuados, el departamento de ventas puede dar prioridad a las oportunidades que permitirán cerrar acuerdos, y el de marketing puede identificar los clientes potenciales que necesitan más atención y prepararlos para que se conviertan en clientes potenciales de calidad.

			Al disponer de información completa, precisa y centralizada sobre clientes y clientes potenciales, los departamentos de ventas y marketing pueden centrar su atención y energía en los clientes adecuados.


		Relación cliente-empresa: 

			Al conocer mejor a sus clientes, se hacen más evidentes las oportunidades de venta cruzada y upselling, lo que le da la oportunidad de conseguir nuevos negocios de sus clientes actuales.

			Esto le ayuda a establecer relaciones más duraderas y rentables con sus clientes.

			Con una mejor visibilidad, también podrá mantener a sus clientes satisfechos con un mejor servicio. 

			Los clientes satisfechos suelen repetir, y los que repiten gastan más: hasta un 33% más, según algunos estudios.


		Soporte/Atención al cliente: 

			Los clientes de hoy en día esperan una asistencia rápida y personalizada, a cualquier hora del día o de la noche.

			Un sistema CRM puede ayudarle a ofrecer el servicio de alta calidad que buscan los clientes. 

			Sus agentes pueden ver rápidamente qué productos han pedido los clientes, y pueden obtener un registro de cada interacción para poder dar a los clientes las respuestas que necesitan, rápidamente.


		Mejora de productos y servicios: 

			Un buen sistema CRM recopilará información de una gran variedad de fuentes de su empresa y más allá. 

			De este modo, puede servir como un motor de escucha de los clientes, proporcionándole una visión sin precedentes de cómo se sienten sus clientes y de lo que dicen de su organización, para que pueda mejorar lo que ofrece, detectar problemas a tiempo e identificar carencias.


		Conexión remota: 

			En un mundo en el que se trabaja desde cualquier lugar, nunca ha sido tan importante que sus equipos estén conectados en una plataforma compartida que les permita colaborar y trabajar desde cualquier sitio. 

			Y dejando a un lado las fuerzas externas, las expectativas de los clientes seguirán empujando a su empresa a evolucionar con el tiempo, y un CRM flexible, escalable y basado en la nube puede ayudarle a mantenerse ágil y a hacer crecer su negocio sin importar las circunstancias. 


	Cloud CRM: 

		Quizá el avance reciente más significativo en los sistemas CRM haya sido el paso del software CRM local a la nube. 

		Liberadas de la necesidad de instalar software en decenas, cientos o miles de ordenadores de sobremesa y dispositivos móviles, organizaciones de todo el mundo están descubriendo las ventajas de trasladar datos, software y servicios a un entorno en línea seguro.

		Permiten que todos los usuarios dispongan de la misma información en todo momento. 

		Sus equipos de ventas que están de viaje pueden consultar los datos, actualizarlos al instante después de una reunión o trabajar desde cualquier lugar. 

		La misma información está disponible para cualquiera que la necesite, desde el equipo de ventas hasta los representantes del servicio de atención al cliente.


		Reducir costes:

			El CRM puede ser rápido y fácil de implantar. 

			Un sistema basado en la nube no requiere ninguna instalación especial ni hardware que configurar, lo que mantiene bajos los costes de TI y elimina los quebraderos de cabeza del control de versiones y los calendarios de actualización.

			Normalmente, los sistemas CRM basados en la nube tienen un precio basado en el número de usuarios que acceden al sistema y el tipo de funciones necesarias. 

			Esto puede ser muy rentable en términos de desembolso de capital, y también es extremadamente flexible, lo que le permite escalar y añadir más personas a medida que crece su negocio.

			Salesforce también es flexible en términos de funcionalidad: no pagará por ninguna función que no le resulte útil.


		Una plataforma CRM basada en la nube le ofrece:

		    Implementación más rápida.

		    Actualizaciones automáticas de software.

		    Rentabilidad y escalabilidad.

		    La posibilidad de trabajar desde cualquier lugar, en cualquier dispositivo.

		    Mayor colaboración.


	Claves de un CRM: 

		El uso de un sistema CRM ayuda a las empresas a ser más eficientes, mejorar las relaciones con sus clientes y aumentar su CLV (Customer Lifetime Value).

    	Un sistema CRM almacena datos importantes sobre clientes y clientes potenciales, lo que permite a las empresas gestionar mejor sus relaciones clave.

   		Entre las funciones importantes de un sistema CRM se incluyen la gestión de contactos y clientes potenciales, la previsión de ventas y los análisis basados en cuadros de mando.

    	Al evaluar y comparar sistemas CRM, es importante que una organización decida primero qué se ajusta mejor a sus necesidades: un CRM basado en la nube o un CRM cliente/servidor.

    	Los sistemas CRM pueden ayudar a seguir el ritmo de un mundo cambiante, son sistemas CRM son flexibles y escalables. 

    	Las empresas pueden aprovechar la inteligencia artificial, integrar las redes sociales y adoptar la movilidad, en cualquier lugar y en cualquier momento.



|| Certificados 

	Los certificados digitales (o simplemente certificados) son archivos electrónicos que identifican de forma única a personas y recursos en Internet.

	Los certificados también permiten la comunicación segura y confidencial entre dos entidades.

	Existen diferentes tipos de certificados, como los certificados personales, utilizados por particulares, y los certificados de servidor, utilizados para establecer sesiones seguras entre el servidor y los clientes mediante la tecnología de capa de sockets seguros (SSL).

	Los certificados se basan en la criptografía de clave pública (public key cryptography), que utiliza pares de claves digitales (digital keys) (números muy largos) para cifrar (encrypt), o codificar, la información de modo que sólo pueda ser leída por su destinatario. 

	A continuación, el destinatario descifra (decrypts) la información para leerla.

	Un par de claves contiene una clave pública (public key) y una clave privada (private key). 

	El propietario (owner) distribuye la clave pública y la pone a disposición de cualquiera. 

	Pero el propietario nunca distribuye la clave privada; siempre se mantiene en secreto. 

	Como las claves están relacionadas matemáticamente, los datos cifrados con una clave sólo pueden descifrarse con la otra clave del par.

	Un certificado es como un pasaporte: identifica al titular y proporciona otra información importante. 

	Los certificados los emite un tercero de confianza llamado Autoridad de Certificación (AC). 

	La CA es análoga a la oficina de pasaportes: valida la identidad del titular del certificado y firma el certificado para que no pueda ser falsificado o manipulado. 

	Una vez que una CA ha firmado un certificado, el titular puede presentarlo como prueba de identidad y para establecer comunicaciones cifradas y confidenciales.

	Y lo que es más importante, un certificado vincula la clave pública del titular a su identidad. 

	Al igual que un pasaporte vincula una fotografía a la información personal de su titular, un certificado vincula una clave pública a la información sobre su propietario.

	Además de la clave pública, un certificado suele incluir información como:

   		El nombre del titular y otra identificación, como la URL del servidor Web que utiliza el certificado o la dirección de correo electrónico de una persona.

    	El nombre de la CA que emitió el certificado.

    	Una fecha de caducidad.

	Los certificados digitales se rigen por las especificaciones técnicas del formato X.509. 

	Para verificar la identidad de un usuario en el ámbito de los certificados, el servicio de autenticación verifica un certificado X.509, utilizando el campo de nombre común del certificado X.509 como nombre principal.


	Cadenas de Certificados: 

		Los navegadores web están preconfigurados con un conjunto de certificados de CA raíz en los que el navegador confía automáticamente. 

		Cualquier certificado procedente de otro lugar debe ir acompañado de una cadena de certificados para verificar su validez. 

		Una cadena de certificados es una serie de certificados emitidos por sucesivas CA que acaban en un certificado de CA raíz.

		Cuando se genera un certificado por primera vez, se trata de un certificado autofirmado. 

		Un certificado autofirmado es aquel cuyo emisor (firmante) es el mismo que el sujeto (la entidad cuya clave pública está siendo autenticada por el certificado). 

		Cuando el propietario envía una solicitud de firma de certificado (CSR) a una CA e importa la respuesta, el certificado autofirmado se sustituye por una cadena de certificados. 

		Al final de la cadena se encuentra el certificado (respuesta) emitido por la CA que autentica la clave pública del sujeto. 

		El siguiente certificado de la cadena es el que autentica la clave pública de la CA.

		Normalmente, se trata de un certificado autofirmado (es decir, un certificado de la CA que autentica su propia clave pública) y el último certificado de la cadena.

		En otros casos, la CA puede devolver una cadena de certificados. 

		En este caso, el certificado inferior de la cadena es el mismo (un certificado firmado por la CA, que autentica la clave pública de la entrada de claves), pero el segundo certificado de la cadena es un certificado firmado por una CA diferente, que autentica la clave pública de la CA a la que enviaste la CSR. 

		A continuación, el siguiente certificado de la cadena es un certificado que autentica la clave de la segunda CA, y así sucesivamente, hasta llegar a un certificado raíz autofirmado.

		Así, cada certificado de la cadena (después del primero) autentica la clave pública del firmante del certificado anterior de la cadena.


	SSL:

		Secure Sockets Layer (SSL) es el estándar más popular para proteger las comunicaciones y transacciones en Internet. 

		Las aplicaciones web utilizan HTTPS (HTTP sobre SSL), que emplea certificados digitales para garantizar comunicaciones seguras y confidenciales entre el servidor y los clientes. 

		En una conexión SSL, tanto el cliente como el servidor cifran los datos antes de enviarlos y los descifran al recibirlos.

		Cuando un navegador web (cliente) quiere conectarse a un sitio seguro, se produce un intercambio (handshake) SSL:

		    El navegador envía un mensaje a través de la red solicitando una sesión segura (normalmente, solicitando una URL que empiece por https en lugar de http).

		    El servidor responde enviando su certificado (incluida su clave pública).

		    El navegador comprueba que el certificado del servidor es válido y está firmado por una CA cuyo certificado está en la base de datos del navegador (y que es de confianza). 

		    También comprueba que el certificado de la CA no haya caducado.

		    Si el certificado es válido, el navegador genera una única clave de sesión (session key) y la cifra (encrypt) con la clave pública del servidor. 

		    A continuación, el navegador envía la clave de sesión cifrada al servidor para que ambos dispongan de una copia.

		    El servidor descifra (decrypts) el mensaje utilizando su clave privada y recupera la clave de sesión.


		Tras el apretón de manos, el cliente ha verificado la identidad del sitio web, y sólo el cliente y el servidor web disponen de una copia de la clave de sesión. 

		A partir de ese momento, el cliente y el servidor utilizan la clave de sesión para cifrar todas las comunicaciones entre ellos.

		De este modo, se garantiza la seguridad de sus comunicaciones.

		La versión más reciente de la norma SSL se denomina TLS (Transport Layer Security). 

		El Servidor de Aplicaciones soporta los protocolos de encriptación Secure Sockets Layer (SSL) 3.0 y Transport Layer Security (TLS) 1.0.

		Para utilizar SSL, el Servidor de Aplicaciones debe tener un certificado para cada interfaz externa, o dirección IP, que acepte conexiones seguras. 

		El servicio HTTPS de la mayoría de los servidores Web no funcionará a menos que se haya instalado un certificado digital.

		Generar un certificado utilizando la utilidad keytool para configurar un certificado digital que su servidor Web pueda utilizar para SSL.


	Cifrados (Ciphers): 

		Un cifrado es un algoritmo criptográfico utilizado para cifrar o descifrar. 

		Los protocolos SSL y TLS admiten diversos cifrados que se utilizan para autenticar el servidor y el cliente entre sí, transmitir certificados y establecer claves de sesión.

		Algunos cifrados son más potentes y seguros que otros. 

		Los clientes y servidores pueden soportar diferentes suites de cifrado. 

		Elija cifradores de los protocolos SSL3 y TLS. 

		Durante una conexión segura, el cliente y el servidor acuerdan utilizar el cifrado más potente que ambos tengan activado para la comunicación, por lo que suele ser suficiente con activar todos los cifrados.


	Name-based Virtual Hosts:

		El uso de hosts virtuales basados en nombres para una aplicación segura puede ser problemático. 

		Se trata de una limitación de diseño del propio protocolo SSL.

		El protocolo SSL, en el que el navegador del cliente acepta el certificado del servidor, debe producirse antes de que se acceda a la solicitud HTTP. 

		Como resultado, la información de la solicitud que contiene el nombre del host virtual no puede determinarse antes de la autenticación y, por tanto, no es posible asignar varios certificados a una única dirección IP.

		Si todos los hosts virtuales de una misma dirección IP necesitan autenticarse con el mismo certificado, la adición de múltiples hosts virtuales probablemente no interferirá con las operaciones SSL normales del servidor. 

		Sin embargo, tenga en cuenta que la mayoría de los navegadores compararán el nombre de dominio del servidor con el nombre de dominio que aparece en el certificado, si lo hay (aplicable principalmente a certificados oficiales firmados por CA). 

		Si los nombres de dominio no coinciden, estos navegadores muestran una advertencia. 

		En general, sólo los hosts virtuales basados en direcciones se utilizan habitualmente con SSL en un entorno de producción.


	Claves de los certificados en los sitios web: 

		SSL es la tecnología de seguridad estándar para establecer un enlace cifrado entre un servidor web y un navegador. 

		Este enlace protege la privacidad de todos los datos que se comuniquen entre el servidor web y el navegador.

		Analicemos esta definición con un ejemplo: imagina que llegas a un sitio web que cuenta con un formulario y, después de completarlo y seleccionar «enviar», la información que acabas de mandar es interceptada por un hacker debido a que se trataba de un sitio web no seguro.

		Los datos que compartes pueden ser de cualquier tipo, desde información bancaria, fiscal, de identidad, tus contactos, etc. 

		En la jerga de los hackers, esta intercepción se conoce como «ataque de intermediario». 

		El ataque puede ocurrir de varias maneras, pero una de las más comunes es cuando un hacker coloca un pequeño programa de espionaje indetectable en el servidor que aloja un sitio web.

		Ese programa espera en segundo plano y, cuando un visitante comienza a escribir sus datos en el sitio, se activa para captar la información y enviársela al hacker. 

		Si una organización desea tener un sitio web seguro que utilice cifrado, necesita obtener un certificado de sitio, o de host.

		Hay dos elementos que indican que un sitio utiliza cifrado (para más información, consulte Protección de su privacidad):

	    	Un candado cerrado, que, dependiendo de su navegador, puede estar situado en la barra de estado de la parte inferior de la ventana del navegador o en la parte superior de la ventana del navegador, entre los campos de dirección y búsqueda.

	   		Un Localizador Uniforme de Recursos (URL) que comienza por "https:" en lugar de "http:"

		Al asegurarse de que un sitio web cifra su información y tiene un certificado válido, puede ayudar a protegerse contra los atacantes que crean sitios maliciosos para recopilar su información. 

		Asegúrese de saber adónde va su información antes de enviar nada (para más información, consulte Cómo evitar los ataques de ingeniería social y phishing).

		Si un sitio web tiene un certificado válido, significa que una autoridad de certificación ha tomado medidas para verificar que la dirección web pertenece realmente a esa organización.

		Cuando escriba una URL o siga un enlace a un sitio web seguro, su navegador comprobará el certificado para las siguientes características:

		    La dirección del sitio web coincide con la del certificado.

		    El certificado está firmado por una autoridad de certificación que el navegador reconoce como autoridad "de confianza".

		Si el navegador detecta un problema, puede presentarle un cuadro de diálogo en el que se indica que hay un error con el certificado del sitio. 

		Esto puede ocurrir si el nombre con el que está registrado el certificado no coincide con el nombre del sitio, si ha decidido no confiar en la empresa que emitió el certificado o si el certificado ha caducado.

		Normalmente se le ofrecerá la opción de examinar el certificado, tras lo cual podrá aceptarlo para siempre, aceptarlo sólo para esa visita concreta o decidir no aceptarlo. 

		A veces la confusión es fácil de resolver (quizá el certificado se emitió para un departamento concreto de la organización y no con el nombre que figura en el expediente). 

		Si no está seguro de que el certificado sea válido o cuestiona la seguridad del sitio, no envíe información personal.

		Aunque la información esté encriptada, asegúrese de leer primero la política de privacidad de la organización para saber qué se hace con ella (para más información, consulte Protección de su privacidad).


	Verificar certificado en el navegador: 

		Hay dos formas de verificar el certificado de un sitio web en Edge, Firefox o Chrome. 

		Una opción es hacer clic en el icono del candado. 

		Sin embargo, es posible que los ajustes de su navegador no estén configurados para mostrar la barra de estado que contiene el icono. 

		Además, es posible que los atacantes puedan crear sitios web maliciosos que falsifiquen el icono del candado y muestren una ventana de diálogo falsa si hace clic en ese icono.

		Una forma más segura de encontrar información sobre el certificado es buscar la función de certificado en las opciones del menú. 

		Esta información puede estar en las propiedades del archivo o en la opción de seguridad dentro de la información de la página.

		Obtendrá un cuadro de diálogo con información sobre el certificado, incluyendo:

    		Quién emitió el certificado:

    			Debe asegurarse de que el emisor es una autoridad de certificación legítima y de confianza (puede ver nombres como VeriSign o Entrust).

    			Algunas organizaciones también tienen sus propias autoridades de certificación que utilizan para emitir certificados para sitios internos como intranets.


    		A nombre de quién se emite el certificado:

    			El certificado debe emitirse a nombre de la organización propietaria del sitio web. 

    			No confíe en el certificado si el nombre que aparece en él no coincide con el de la organización o persona que espera.
			

			Fecha de caducidad:

				La mayoría de los certificados se emiten para uno o dos años. 

				Una excepción es el certificado para la propia autoridad de certificación, que, debido a la cantidad de implicación necesaria para distribuir la información a todas las organizaciones que poseen sus certificados, puede ser de diez años.

				Desconfíe de las organizaciones con certificados válidos durante más de dos años o con certificados caducados.




	Certificados SSL: 

		Cada vez que los visitantes de tu sitio web acceden a tu sitio, los datos se transfieren de un servidor a otro antes de que lleguen a su destino. 

		A medida que internet evoluciona, también lo hacen tus usuarios (y aquellos que desean explorarlo). Sin una conexión segura, los datos transmitidos están en riesgo. 

		¿Cómo proteges a tus usuarios, prospectos y clientes mientras navegan? con SSL: 

			Tecnología de seguridad que establece un cifrado en la comunicación o intercambio de datos sensibles (usuario/contraseña, datos de formularios, transferencias financieras, etc.) y otros, entre el cliente/navegador y servidor de aplicaciones.  

		Cuando veas un icono de candado junto a la URL en la barra de direcciones de ciertos sitios, significa que están protegidos por SSL. 


		Tipos de certificados SSL: 





		Obtener certificados SSL: 

			Una vez que elijas el tipo de certificado que necesitas, podrás buscar proveedores de certificados que ofrezcan SSL de esas características. 


			1. Verificar la información de nuestro tu sitio web en ICANN Lookup : 

				Antes de que apliques para un certificado SSL, debes asegurarte de que tu registro ICANN Lookup está actualizado y coincide con lo que presentas a la Autoridad de Certificación. 

				Ingresa a la herramienta ICANN Lookup y revisa tu nombre de servidor, tu información de registro y tus servidores de autoridad. 


			2. Genera la Petición de Registro de Certificado (CSR, por sus siglas en inglés)

				Primero debes generar una Petición de Registro de Certificado, o Certificate Signing Request (CSR). 

				Lo puedes hacer a través de tu servidor, tu cPanel o un generador CSR en línea.

				Opción 1: Servidor

					Si tienes acceso a tu servidor, puedes generar el CSR sin ayuda. 

					Encuentra las instrucciones específicas de tu servidor aquí. 

					Esta opción es recomendada para usuarios avanzados o desarrolladores web. 
					

				Opción 2: cPanel

					Si tienes acceso a tu cPanel a través de tu proveedor de hosting, también puedes generar un CSR utilizando sus herramientas. 

					Ingresa a tu cPanel por medio de tu proveedor de hosting

					Ve hacia abajo hasta la sección que se llama «Seguridad». Haz clic en la opción «SSL/TSL». 

					Desde ahí podrás encontrar una opción para generar un CSR.

					Luego de hacer clic, la aplicación te llevará a un formulario que pide tu dominio, ciudad, estado, país y empresa.

				Generador de CSR en línea 

					Finalmente, puedes evitarte cualquier complicación y simplemente usar un generador CSR en línea gratuito.

					Algunas opciones incluyen:

				    	Namecheap's CSR Generator (recomendado para usuarios avanzados).
				    	
				    	Digicert’s CSR Wizard (recomendado para principiantes).

					Te sugerimos utilizarlo como último recurso porque no está conectado a tu servidor, servicio de hosting o cPanel.

				Si no sabes cómo avanzar, contacta a tu proveedor de hosting para que te dé soporte, así tendrás instrucciones específicas para tu sitio web. 

				También pueden recomendarte el tipo de certificado CSR que debes pedir.

		
			3. Presenta tu CSR a la autoridad de certificación para validar tu dominio 

				Cuando compras un certificado SSL a una autoridad de certificación, se te pedirá que presentes tu CSR. 

				Asegúrate de que lo tienes a la mano cuando termines el proceso de registro para tu certificado SSL. 


			4. Instala el certificado en tu sitio web 

				Por último, instala el certificado en tu sitio web, La mejor manera de hacerlo es a través de tu cPanel. 

				En el menú de «Seguridad» haz clic en «SSL/TLS». Luego en «Gestionar sitios SSL». 

				Ahí podrás subir un nuevo certificado al dominio de tu elección. 

				Si compraste un SSL a tu proveedor de hosting, el certificado ya debería haberse instalado automáticamente en tu sitio, así que no tendrás que hacerlo manualmente. 


		Plugins de WordPress para la instalación de SSL:

			Si utilizas WordPress para alojar tu contenido y tu sitio web, podrías necesitar un certificado SSL en función de tu proveedor de dominio. 

			A continuación, compartimos contigo algunos plugins que podrían ayudarte en el proceso:

			    Really Simple SSL: 		

			    	Adquirir el certificado SSL es solo el primer paso. Este plugin te ayuda a instalarlo en todo tu contenido alojado en WordPress. 

			    	Existen versiones premium disponibles para facilitar la instalación en todos tus sitios y verificar que ninguno de ellos presentará advertencias de seguridad. 

			    	El precio de las versiones premium oscila entre los 20 USD y los 145 USD por una configuración completa y 
			    	optimización de SSL.


			    Insecure Content Fixer:  

			    	Una vez que hayas obtenido e instalado tu certificado SSL, deberás considerar otros aspectos, por ejemplo, si tu sitio web fue desarrollado utilizando referencias codificadas a "http" (p. ej., un archivo de imagen), mostrará una advertencia cuando se intente cargar de modo seguro. 

			    	Este plugin te ayudará a encontrar y resolver cualquier contenido codificado de tu sitio para que se muestre de manera segura a todos los visitantes.


			    WP Force SSL:

			    	Cuando finalmente hayas obtenido e instalado tu certificado SSL y hayas solucionado todos los errores posibles, deberás garantizar que todo tu tráfico visualice la versión segura de tu sitio web. 

			    	Con este plugin, podrás dirigir todo tu tráfico a tu versión HTTPS de modo que únicamente se cargará la versión segura. 

			    	Recomendamos verificar que no dispones de contenido no seguro (es decir, «contenido mixto») antes de activar este plugin. 

			    	Si no completas dicha comprobación, es posible que tu sitio se muestre como no seguro.


		Lets'Encrypt:

			Para habilitar HTTPS en tu página de web, tienes que obtener un certificado (un tipo de archivo) de una Autoridad de Certificación (AC, o CA por sus siglas en inglés). 

			Let’s Encrypt es una AC. 

			Para obtener un certificado para tu dominio de sitio web de Let’s Encrypt, tienes que demonstrar control sobre ese dominio. 

			Con Let’s Encrypt, puedes hacer esto con software que usa el protocolo ACME, el cual típicamente corre en tu hospedaje de web.

			Para averiguar cuál método funcionará mejor para ti, tendrás que saber si tienes acceso shell (también conocido como acceso SSH) a tu hospedaje de web. 

			Si manejas tu sitio web enteramente mediante un panel de control como cPanel, Plesk, o WordPress, hay una buena posibilidad que no tienes acceso shell. 

			Puedes preguntarle a tu proveedor de hospedaje para estar seguro.


			Con Acceso Shell:

				Recomendamos que la mayoría de las personas con acceso shell usen el cliente ACME llamado Certbot. 

				Éste puede automatizar la emisión e instalación de certificados con cero tiempo de inactividad.

				También tiene modos de expertos para personas que no quieren autoconfiguración. 

				Es fácil de usar, funciona en muchos sistemas operativos, y tiene documentación genial.

				Visita la página web de Certbot para conseguir instrucciones para tu sistema operativo y servidor de web.

				Si Certbot no cumple con tus necesidades, o quisieras tratar otra cosa, hay muchos otros clientes ACME para escoger. 

				Una vez hayas escogido un cliente ACME, ve la documentación para ese cliente para proceder.

				Si estás experimentando con diferentes clientes ACME, usa nuestro ambiente de staging para evitar que llegues a nuestros limites de tarifa.


			Sin Acceso Shell:

				La mejor forma de utilizar Let’s Encrypt sin acceso shell es usando el soporte incorporado de tu proveedor de hospedaje.

				Si tu proveedor de hospedaje ofrece soporte para Let’s Encrypt, pueden solicitar un certificado gratis en su nombre, instalarlo, y mantenerlo actualizado automáticamente. 

				Para algunos proveedores de hospedaje, esto es un ajuste de configuración que tienes que prender.

				Otros proveedores automaticamente solicitan e instalan certificados para todos sus clientes.

				Revisa nuestra lista de proveedores de hospedaje para ver si el tuyo está en ella. 

				Si lo está, sigue su documentación para configurar tu certificado de Let’s Encrypt.

				Si tu proveedor de hospedaje no tiene soporte para Let’s Encrypt, puedes contactarlos para que lo soporten. 

				Hacemos lo mejor que podemos para hacer fácil añadir soporte para Let’s Encrypt, !y proveedores suelen estar felices de escuchar sugerencias de clientes!

				Si tu proveedor de hospedaje no quiere integrar Let’s Encrypt, pero sí tiene soporte para subir certificados custom, puedes instalar Certbot en tu propia computadora y usarlo en modo manual. 

				En modo manual, tu subes un archivo específico a tu sitio web para probar tu control. 

				Certbot recuperará un certificado que tu puedes subir a tu proveedor de hospedaje. 

				No recomendamos esta opción porque es un contratiempo y necesitaras repetirlo varias veces durante el año cuando tu certificado expira. 

				Para la mayoría de las personas es mejor solicitar soporte para Let’s Encrypt de su proveedor de hospedaje, o cambiar de proveedor si no tienen planes de implementarlo.



|| Session Key y Credenciales 


	Session Key: 


		Una clave de sesión es una clave de cifrado y descifrado que se genera aleatoriamente para garantizar la seguridad de una sesión de comunicaciones entre un usuario y otro ordenador o entre dos ordenadores. 

		Las claves de sesión se denominan a veces claves simétricas (symmetric keys) porque se utiliza la misma clave para cifrar y descifrar.

		La clave de sesión sólo se utiliza para una sesión. 

		Después se descarta y se genera aleatoriamente una nueva clave para la siguiente sesión. 

		Las claves públicas (Public keys) o el cifrado asimétrico (asymmetric encryption), por el contrario, utilizan dos claves (una pública y otra privada) en lugar de una única para proteger la comunicación de datos entre dos partes a través de una red abierta (SSL/TLS).


	Sessión: 

		Una sesión es una interacción entre un usuario y un servidor web caracterizada por un intercambio de información. 

		Este intercambio puede adoptar la forma de una solicitud-respuesta entre un navegador y un servidor web.

		Alternativamente, la interacción puede no implicar una petición o respuesta entre las dos partes.

		Por ejemplo, cuando un usuario se registra en un servicio web, la sesión es esencialmente un intercambio de información que tiene como resultado que el usuario se registra y el servidor almacena esta información para su uso posterior.

		Otro tipo de sesión es la sesión de navegador, que se produce cuando alguien realiza una petición a un servidor web. 

		En este caso, una sesión comienza cuando un usuario solicita por primera vez una página a un servidor web y finaliza cuando ese navegador ha enviado todos los paquetes de información que el servidor solicitó, como cuando un usuario inicia sesión en un sitio web. 

		Esto se considera una sesión porque se trata de una serie de interacciones con el sitio web que requieren una conexión de datos.


		Otros tipos de sesiones son los siguientes: 

		    Sesiones HTTP (Hypertext Transfer Protocol):

		    	Una sesión HTTP es una serie de interacciones entre el navegador de un usuario y un servidor web que persiste más allá de la visualización de una sola página y permite al servidor realizar un seguimiento de la actividad de un usuario.


		    Sesión TCP (Protocolo de Control de Transmisión):

		    	Una sesión TCP es una conexión lógica entre dos hosts de red establecida por el intercambio de segmentos de la capa de transporte.


		    Sesión de inicio de sesión remota Telnet (Protocolo para acceder a otros ordenadores de forma remota):

		    	Una sesión de inicio de sesión remota Telnet es un método utilizado para conectarse e interactuar con un servidor remoto.
	

	Criptográfica: 	

		Los términos más importantes que hay que conocer cuando se habla de criptografía, incluidas las claves de sesión, son los siguientes:

	    Cifrado (Encryption): 

	    	Proceso de convertir datos en un formato ilegible sin conocimientos especiales.


	    Descifrado (Decryption):

	    	El proceso de volver a convertir los datos cifrados a su formato original legible.


	    Clave simétrica (Symmetric key):

	    	Clave única y compartida utilizada por dos partes para cifrar y descifrar datos.


	    Clave asimétrica (Asymmetric key):

	    	Dos claves distintas utilizadas para cifrar y descifrar datos.


	Ventajas de las claves de sesión criptográficas:

		La criptografía es una herramienta esencial en la lucha contra la usurpación de identidad que se utiliza para proteger la información en una amplia gama de aplicaciones, como el comercio electrónico, la seguridad de la información y el almacenamiento de datos. 

		La criptografía utiliza claves para cifrar y descifrar datos. 

		El tipo más común de clave criptográfica es una clave simétrica, que utiliza la misma clave para cifrar y descifrar datos, a diferencia de las claves asimétricas, que utilizan una clave distinta para cifrar y descifrar.

		Generadas mediante un algoritmo simétrico, las claves de sesión tienen varias ventajas:

		    La principal ventaja de las claves de sesión es su comodidad de uso. 

		    Las claves de sesión pueden ser una única clave fija o pueden generarse dinámicamente a partir de un conjunto de claves existentes.

		    Las claves de sesión ofrecen una protección añadida porque la clave se descarta después de haber sido utilizada para establecer un canal de comunicación seguro, como durante una conexión TLS (Transport Layer Security).

		    Los algoritmos asimétricos suelen tardar más en calcularse que los simétricos. 

		    Dado que las claves de sesión son claves simétricas de un solo uso, son mucho más rápidas de utilizar para aplicaciones concretas, incluido el almacenamiento en caché de datos temporales.


	Desventajas de las claves de sesión:

		Las claves de sesión no están exentas de desventajas, entre las que se incluyen las siguientes:

		    La mayor desventaja de utilizar claves de sesión es que no son tan seguras como las claves públicas debido a su simplicidad. 

		    Utilizar una clave de sesión para más de una sesión puede comprometerla.

		    Otra desventaja de utilizar una clave de sesión para cifrar datos es que es vulnerable a las escuchas y al compromiso. 

		    Como clave simétrica, una clave de sesión se utiliza tanto para cifrar como para descifrar datos. 

		    Esto hace que la información sea vulnerable si malos actores interceptan la clave en tránsito por la red o la roban cuando está almacenada en la memoria de un servidor.


	Cifrado HTTPS y claves de sesión:

		HTTP sobre Secure Sockets Layer, o SSL, también conocido como HTTP seguro (HTTPS), es un protocolo web que cifra los datos enviados entre un navegador y un sitio web. 

		La encriptación lleva los datos a su destino de forma segura para que no puedan ser interceptados y leídos en tránsito.

		Al añadir una capa de cifrado a la conexión, HTTPS garantiza que la conexión sea privada. 

		Con HTTPS, cuando un navegador envía una solicitud para acceder a un sitio web, genera una clave de sesión. 

		La clave de sesión cifra los datos enviados y los descifra cuando los recibe.

		Por ejemplo, si un usuario introduce los datos de su cuenta corriente para comprar artículos en Internet, su navegador cifrará esa información mediante una clave de sesión. 

		A continuación, el servidor del sitio web la descifrará utilizando la clave de sesión que recibió del navegador.


	TLS Handshake: 

		Para crear una conexión segura entre dos ordenadores, hay que seguir una serie de pasos.

		Denominados "protocolo TLS", estos pasos son lo primero que ocurre al conectarse a un sitio web con HTTPS.

		Piensa en el handshake TLS como un protocolo que permite a dos ordenadores ponerse de acuerdo sobre cómo se van a comunicar. 

		Si el handshake falla, entonces la conexión no es segura. 

		Aunque un protocolo TLS puede fallar de muchas maneras diferentes, la razón más común es debido a información errónea transmitida de un lado a otro entre dos ordenadores que se comunican.


		Un protocolo TLS consta de los tres pasos siguientes:

		    El servidor envía su certificado SSL al cliente.

		    El cliente comprueba el certificado.

		    El cliente cifra un número aleatorio con una clave pública.


		La clave de sesión cifra la mayor parte de los datos transmitidos en el protocolo TLS y se genera y negocia independientemente de la versión del protocolo y del conjunto de cifrado seleccionados por los clientes y los servidores. 

		Como resultado, la clave de sesión es la misma para todas las conexiones establecidas entre dos pares que soporten la misma versión de protocolo.


	Conceptos relacionados:
		
		Master encryption key/Clave maestra de cifrado (MEK):

			Una MEK es una clave de cifrado que protege otras claves de cifrado. 

			Clave criptográfica utilizada para generar un gran número de otras claves, una clave maestra no suele utilizarse directamente para cifrar o descifrar. 

			Más bien se utiliza para generar claves de sesión que luego se utilizan para las comunicaciones. 

			Dado que las claves de sesión sólo se necesitan durante un breve periodo de tiempo, una clave maestra es más práctica que una clave por uso.


		Key encryption key/Clave de cifrado (KEK):

			Una KEK se utiliza para cifrar otras claves, como la clave de cifrado de datos o la clave de cifrado de tráfico, que se utilizan para cifrar datos sensibles.


		Content encryption key/Clave de cifrado de contenido (CEK):

			Una CEK es una clave que puede encriptarse aún más utilizando una KEK. 

			La CEK se utiliza para cifrar contenidos para su almacenamiento o transmisión, incluidos contenidos en forma de mensajes, imágenes, audio, etc.


	Credenciales: 	

		Una credencial de inicio de sesión es una combinación de ID de usuario y contraseña que permite a los usuarios acceder a un sitio web o una aplicación.

		Los usuarios tienen que introducir sus credenciales de inicio de sesión cada vez que quieran utilizar el sitio o la aplicación.

		Las credenciales de inicio de sesión también se conocen como nombre de usuario y contraseña, ID de usuario y contraseña, o simplemente datos de la cuenta.

		Los usuarios pueden registrarse en un sitio web utilizando su dirección de correo electrónico actual, crear una nueva dirección de correo electrónico específica para ese sitio o hacerlo a través de otra cuenta de redes sociales conectada al mismo sitio web.

		Al crear una cuenta en la mayoría de los sitios web o aplicaciones, se le pedirá que introduzca su nombre de usuario y contraseña.

		Los usuarios pueden tener diferentes credenciales de inicio de sesión para distintos servicios, como sitios de redes sociales, entidades financieras y tiendas en línea.

		Suelen utilizarse para verificar la identidad de una persona que inicia sesión en el sistema cuando ello puede entrañar algún riesgo, como en el caso de una cuenta bancaria en línea, un servicio de comercio electrónico o una plataforma de redes sociales en la que se publican algunos datos personales, como la fecha de nacimiento o el domicilio.


	Tipos de credenciales de inicio de sesión:

		Existen dos tipos principales de credenciales de inicio de sesión, en función de cómo se generan y cómo se protegen:

	    Estáticas/Static: 

	    	Se trata de una credencial que se genera y guarda en un servidor y que permanece invariable durante toda la sesión de inicio de sesión del usuario. 

	    	Esto significa que tu contraseña seguirá siendo la misma a menos que la actualices.


	    Transitoria/Transient: 

	    	Se trata de una credencial que se genera cada vez que un usuario inicia sesión: cambia cada vez.

	    	También se conoce como "contraseña de un solo uso", o OTP, porque el servidor generará un código totalmente nuevo cada vez que el usuario inicie sesión. 

	    	Muchas instituciones financieras utilizan las OTP como credenciales de inicio de sesión, por ejemplo para acceder a su cuenta corriente o de ahorros. 

	    	Las OTP se recomiendan para las credenciales de inicio de sesión cuando existe el riesgo de que agentes maliciosos entren en un servidor y accedan a información privada.


	Recordar credenciales: 	

		Existen algunas formas probadas de recordar las credenciales de inicio de sesión, pero sólo si el sitio o la aplicación en la que te registras es de uso habitual.

		Esto significa que probablemente deberías olvidarte de la libreta digital o el diario de papel donde escribías tus credenciales de inicio de sesión. 

		Hay otras formas mejores y más seguras de llevar un registro de tus diferentes credenciales, por ejemplo, utilizar un gestor de contraseñas.

		La mejor forma de llevar un registro de las credenciales de inicio de sesión es utilizar un gestor de contraseñas.

		Esta herramienta te permite almacenar las credenciales de inicio de sesión en un solo lugar y generar nuevas credenciales de inicio de sesión seguras cuando necesites iniciar sesión en un nuevo sitio o aplicación.


	Credenciales fuertes: 

	    Utilice contraseñas largas:

	    	Si un sitio web o una aplicación te permite crear contraseñas largas con letras, números y símbolos, hazlo. 

	    	Las contraseñas largas son más difíciles de descifrar y tardan más tiempo en piratearse por fuerza bruta, pero sólo si utilizas una contraseña fuerte y difícil de descifrar.


	    Evite palabras comunes en las contraseñas:

	    	Las herramientas de pirateo como los diccionarios y las herramientas de fuerza bruta pueden probar miles de contraseñas sencillas como "password" o "12345678" antes de pasar a contraseñas más complicadas.


	    No utilices la misma contraseña para varios sitios web o aplicaciones:

	    	Si necesitas configurar las credenciales de inicio de sesión para un nuevo sitio web, asegúrate de que no estás reutilizando la misma contraseña de otro sitio web.

	    	Si la reutilizas, sustitúyela por una contraseña más segura y exclusiva para el nuevo sitio.


	Tecnológias que refuerzan la identificación de usuarios: 

		Los nombres de usuario y las contraseñas por sí solos sólo proporcionan niveles de seguridad limitados y son relativamente fáciles de interceptar por los piratas informáticos o de olvidar o perder por los usuarios. 

		Es vital complementar las credenciales de inicio de sesión con tecnologías que refuercen el proceso de autenticación e impidan el acceso no autorizado a las redes.


		Autenticación de dos factores ( Two-factor Authentication):

			La autenticación de dos factores (2FA) refuerza las credenciales de inicio de sesión proporcionando un nivel adicional de certeza de que el usuario es quien dice ser. 

			Cuando un usuario inicia sesión con su nombre de usuario y contraseña, se le pide que introduzca un segundo dato que verifica su identidad.

			Esta información suele ser algo que sabe, como un PIN o un código de acceso; algo que posee, como un código en una aplicación de autenticación o en su dispositivo móvil; o algo que es, normalmente un factor biométrico.


		Biometría (Biometrics):

			Los datos biométricos son atributos personales o algo que el usuario es, como su huella dactilar, su cara o su voz. 

			También incluyen la biometría del comportamiento, como la dinámica de pulsación de teclas o el patrón de habla de un usuario. 

			La autenticación biométrica se utiliza habitualmente para proteger dispositivos como ordenadores y teléfonos móviles para evitar accesos no autorizados. 

			Esto añade una capa de seguridad más difícil de obtener con las credenciales de inicio de sesión tradicionales.


		Inicio de sesión único (Single Sign-on):

			El inicio de sesión único es una técnica que permite a los usuarios iniciar sesión en varios servicios y sitios web utilizando un conjunto de credenciales de inicio de sesión. 

			Valida a los usuarios en varias aplicaciones utilizando un token de autenticación para verificar su identidad ante los proveedores de servicios conectados. 

			Los usuarios sólo tienen que recordar un conjunto de credenciales de inicio de sesión, lo que fomenta el uso de una contraseña fuerte y única y reduce la repetición de contraseñas.


	Amenazas para las credenciales de usuario/Threats To User Credentials:

		Las credenciales de inicio de sesión de los usuarios son objetivos muy valiosos para los piratas informáticos, que utilizan diversas técnicas para intentar robar estos datos. 

		Esto supone un riesgo importante para la información sensible de los usuarios, que podría utilizarse para cometer robos de identidad o llevar a cabo ataques más amplios contra las organizaciones. 

		Varios ataques específicos tienen como objetivo las credenciales de inicio de sesión.


		Ataque de fuerza bruta (Brute-force Attack): 

			Un ataque de fuerza bruta consiste en que los hackers utilizan un método de ensayo y error para descifrar las credenciales de inicio de sesión, las contraseñas y las claves de cifrado de los usuarios. 

			Es una táctica sencilla, fiable y popular que los hackers utilizan para obtener acceso no autorizado a cuentas, redes y sistemas informáticos.


		Phishing:

			Los ataques de phishing consisten en que los hackers utilizan credenciales de inicio de sesión para enviar un correo electrónico desde lo que parece un remitente de confianza de una empresa legítima. 

			El hacker suele incluir enlaces o archivos adjuntos maliciosos en el mensaje o pide a la víctima que realice una transacción financiera.
		

		Malware: 

			El malware es software malicioso, como ransomware, spyware y virus, que los hackers utilizan para tomar el control de un dispositivo, obtener acceso a una red o dañar datos y sistemas.


		Spyware: 

			El spyware es una forma de malware que recopila datos del dispositivo de un usuario y los envía a un tercero sin su consentimiento, lo que los hackers pueden utilizar para suplantar la identidad.

			Algunos programas espía están diseñados para dañar los dispositivos. 

			Los piratas informáticos también pueden utilizar programas espía para ver o robar la actividad de navegación y las credenciales de inicio de sesión de los usuarios.


	Autentificación sin contraseña: 

		La autenticación sin contraseña es un proceso de inicio de sesión en una cuenta que permite a los usuarios verificar su identidad utilizando un método distinto a la combinación tradicional de nombre de usuario y contraseña.

		Las formas más populares incluyen el uso de un segundo dispositivo o la biometría para verificar la identidad de un usuario. 


		Entre los distintos tipos de autenticación sin contraseña se encuentran: 

	    Autenticación biométrica: 

	    	Una de las formas más seguras de verificar la identidad de una persona es utilizar algo que es único para cada individuo. 

	    	La autenticación biométrica se basa en rasgos físicos únicos, normalmente una huella dactilar y el reconocimiento facial o del iris, para verificar que un usuario es quien dice ser. 


	    Códigos de un solo uso: 

	    	Este método de autenticación sin contraseña se basa en que los usuarios introduzcan un código único que se les envía cuando intentan acceder a una cuenta. 

	    	Se les enviará un código de un solo uso (OTC) o una contraseña de un solo uso (OTP) a su dirección de correo electrónico o dispositivo móvil, y deberán introducir el mismo código en el dispositivo original para verificar su identidad.


	    Enlaces mágicos: 

	    	En este tipo de autenticación sin contraseña, los usuarios introducen su dirección de correo electrónico en un cuadro de inicio de sesión de una aplicación o servicio. 

	    	A continuación, se les envía un correo electrónico con un enlace en el que deben hacer clic para confirmar su identidad.


	    Notificaciones push: 

	    	Este proceso de autenticación sin contraseña implica el uso de aplicaciones de autenticación, como FortiAuthenticator y Google Authenticator. 

	    	El usuario recibe una notificación push que le lleva a la aplicación, donde puede verificar si ha intentado o no acceder a un servicio conectado a la aplicación.


	Ventajas de la autenticación sin contraseña: 

		La autenticación sin contraseña biológica refuerza el proceso de inicio de sesión al proporcionar un mayor nivel de certeza de que un usuario es quien dice ser. 

		Por ejemplo, los procesos de autenticación biométrica, como el escaneado de huellas dactilares o el reconocimiento del iris, ofrecen más garantías de que el usuario es auténtico que la simple introducción de las credenciales de inicio de sesión.

		Los métodos de autenticación sin contraseña eliminan la dependencia de que los usuarios recuerden sus contraseñas. 

		La gente olvida a menudo sus contraseñas para varias cuentas en línea o reutiliza la misma contraseña para distintos servicios. 

		Esto supone importantes riesgos para la seguridad, por lo que eliminar la necesidad de contraseñas es crucial para reforzar los inicios de sesión.

		Los sistemas de autenticación sin contraseña también utilizan métodos de autenticación modernos, como los dispositivos compatibles con Fast IDentity Online (FIDO), que reducen la vulnerabilidad de una organización a los ataques de malware y phishing.



||Cookies










|| APIs 





|| Protocolo SSH (Secure Shell)





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




|| Cómo funcionana los navegadores




|| APIs




|| Seguridad en la Web
	





|| Diseño de Software y Arquitectura 






|| Conteinerización y Virtualización


