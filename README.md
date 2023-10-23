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

	









