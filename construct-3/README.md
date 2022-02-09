<div align="justify">
<div align="center">
<h1>Análisis del framework Construct 3</h1>

  <img src="https://editor.construct.net/media/og-image-promo.png" width="800px" />
</div>

## Índice
1. [Introducción](#id1)
2. [Herramienta analizada](#id2)
3. [Requisitos del sistema](#id3)
4. [Instalación](#id4)
5. [Hola Mundo](#id5)
6. [Construct 3 VS Construct 2](#id6)
7. [Conclusión](#id7)
  
<div id='id1' />
<h2>Introducción</h2>

<p>La presente entrada tiene como objetivo realizar un análisis del framework Construct 3, utilizado para la creación de videojuegos en 2D. Para ello expondremos en los siguientes apartados las principales características de Construct 3, aquellos requisitos que demanda del sistema y su uso mediante un ejemplo sencillo. Por último realizaremos una comparación con respecto a su predecesor, Construct 2, para finalizar con una conclusión sopesando tanto los aspectos positivos como los problemáticos del framework.

<div id='id2' />
<h2>Herramienta analizada</h2>

<p>Inicialmente lanzado al público en 2017, Construct 3 se presenta como el sucesor de Construct 2, otro framework para el desarrollo de videojuegos con muchos años a sus espaldas en el mercado y una gran comunidad que lo apoya de diversas maneras desarrollando plugins, tutoriales y, por supuesto, videojuegos con esta herramienta. No obstante Construct 3, pese a tener menos historia que su predecesor, cuenta con muchas nuevas funcionalidades y características que lo convierten en la evolución lógica de Construct 2 y una opción viable para toda aquella persona que desee desarrollar un videojuego en 2D.</p>
  
<p>Nótese que hacemos alusión a la “persona” en lugar de al “programador” que desee desarrollar un videojuego porque esta herramienta, al igual que Construct 2, es bastante amigable con aquellos que no tienen conocimientos de programación. En primer lugar, es muy sencillo comenzar a utilizar la herramienta puesto que no es necesario realizar ningún tipo de instalación o registrarse en la web de Construct 3; empleando un navegador web, el usuario podrá hacer uso de Construct 3 sin siquiera tener que mantener conexión con Internet en todo momento. Por si fuera poco la propia web otorga al usuario la opción de experimentar con la versión gratuita de la herramienta para poder familiarizarse con esta y darle tiempo para sopesar si desea pagar o no por una licencia de uso, cuyas características y cambios con respecto a la versión gratuita mencionaremos más adelante. También es importante destacar que la herramienta cuenta no solo con multitud de tutoriales en su propia web disponibles para guiar a los principiantes en la creación de su primer videojuego, sino que además está construida de tal modo que se adapta tanto a los programadores más veteranos como a aquellos que están dando sus primeros pasos con ella.</p>
  
<p>En relación a este último punto, Construct 3 debe en gran parte esta adaptabilidad mencionada al lenguaje de programación del que hace uso, JavaScript. Reconocido como uno de los lenguajes más utilizados por los programadores, JavaScript se adecúa a las necesidades de expertos y novatos al permitir a los primeros desarrollar sus trabajos en un entorno ya familiar para ellos, dada la popularidad con la que cuenta el lenguaje entre los profesionales de la programación, y a los segundos aprender a usarlo mediante un sistema guiado por pequeños logros que busca no solo enseñar al usuario a utilizar JavaScript sino también motivarlo para que continúe aprendiendo y llegue en el futuro a convertirse también en un usuario competente de este lenguaje. De hecho, Construct 3 implementa una curva de aprendizaje tan acertada para los usuarios sin experiencia en programación que es utilizado por instituciones educativas para enseñar a sus alumnos las bases del desarrollo con JavaScript. En la actualidad la web de Construct 3 ofrece la adquisición de una licencia orientada específicamente para los educadores por 8,99 euros por asiento (dispositivo con Construct 3 que usará el alumno) al mes y 29,99 euros por asiento al año, diferenciándose las versiones de Construct 3 adquiridas con la licencia educativa de las versiones gratuitas al ofrecer características tales como el uso de demos y la eliminación de aquellos límites con los que cuentan las versiones gratuitas.</p>
  
<p>Hablando de las diferencias entre versiones de pago y gratuitas de Construct 3 cabe destacar el gran salto que existe en cuanto a nuevas características y eliminación de constricciones con respecto una y otra al realizar el pago. La adquisición de una licencia, ya sea esta personal, de educador o de negocio, otorga a cambio del pago mensual/anual la posibilidad de no solo desarrollar un videojuego sin tener que limitarte por ejemplo al número máximo de eventos existentes (50) o de layers (2) con los que cuentan las versiones gratuitas, sino también el permiso de comercializar todo aquel videojuego creado por la herramienta y obtener con ellos el 100% de los beneficios que le corresponden al poseedor de la licencia sin tener que conceder este parte de dichos beneficios a terceros; en definitiva, una característica bienvenida para los desarrolladores de videojuegos y complementada por las opciones que también proveen las licencias de pago de publicar el producto creado en los formatos HTML5, Construct Arcade, Android APK, IPhones, IPads, Facebook Instant Games, Playable Ads y el escritorio de Windows, MacOS y Linux.</p>

<div id='id3' />
<h2>Requisitos del sistema</h2>

<p>Si bien mencionamos en el apartado anterior que Construct 3 puede ser usado sin necesidad de contar con una conexión constante a Internet, es necesario que la primera vez que sea cargada esta herramienta por el usuario este cuente con conexión a Internet hasta que sea notificado a los pocos minutos de que ya es posible trabajar con Construct 3 offline. Asimismo, todo usuario con licencia que trabaje de forma offline debe realizar este paso al menos una vez cada 7 días para poder volver a  validar su suscripción.<br>
También comentamos que Construct 3 puede ser usado desde el navegador web sin necesidad de instalar nada, pero para ello se debe contar con uno de los siguientes tipos de navegadores:</p>
 
 <ul>
<li>Google Chrome: a partir de la versión 57, incluyendo aquellos navegadores que usan el engine Chromium, como Opera y Yandex.</li>
<li>Firefox: a partir de la versión 55.</li>
<li>Safari: a partir de la versión 13.</li>
<li>Microsoft Edge: a partir de la versión 79, incluyendo Edge Browser en Windows 10.</li>
</ul
   
<p>En cuanto al tipo de sistema operativo del dispositivo, Construct 3 soporta:</p>
<ul>
<li>Windows: versiones 7, 8, 8.1, 10 y posteriores.</li>
<li>Mac: OS X/MacOs 10.9 y posteriores.</li>
<li>Linux: versión 14.04 y posteriores de Ubuntu 64-bit, versión 8 y posteriores de Debian, versión 13.3 y posteriores de openSUSE y versión 24 y posteriores de Fedora Linux.</li>
<li>Chrome OS: versión 57 y posteriores.</li>
<li>Android: versión 5.1 y posteriores con un mínimo de 1GB de RAM.</li>
<li>IOS: versión 13 y posteriores.</li>
</ul>

<p>Por último, cabe destacar en cuanto a requisitos del sistema que Construct 3 precisa del soporte de WebGL por parte del navegador utilizado por el usuario. En caso de recibir el usuario un mensaje que le advierte acerca del no soporte de WebGL por parte de su navegador, este deberá instalar la versión más reciente de su sistema operativo y comprobar si sus drivers gráficos se encuentran actualizados a fin de solventar dicho error y poder hacer uso de Construct 3.</p>

<div id='id4' />
<h2>Instalación</h2>

<div id='id5' />
<h2>Ejemplo Hola Mundo</h2>
  
<div id='id6' />
<h2>Construct 3 VS Construct 2</h2>
  
<div id='id7' /> 
<h2>Conclusión</h2>

</div>
