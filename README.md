## Curso para la Certificación en Facebook Ad Products Developer I 🤖 
Documentación en Español para la preparación a la Certificación de Facebook Ad Products Developer I del programa Facebook Blueprint. La traducción del repositorio está desarrollada mediante la contribución de líderes de comunidades Developer Circles de LATAM en ciudades como 🇲🇽 Ciudad de México, 🇨🇴 Bogotá, 🇬🇹 Guatemala & 🇨🇷 San José. 


#### Capítulo 1 - Facebook Pixel: Que, cómo y por qué?
En este capítulo, aprenderá los beneficios de usar un píxel de Facebook, qué es y cómo funciona.

El píxel de Facebook es una herramienta que lo ayuda a comprender las actividades de un consumidor en su sitio web y a utilizar esas actividades en la plataforma de Facebook para medir la efectividad de su publicidad, optimizar la entrega de sus anuncios y definir su propio público objetivo.

https://www.facebookblueprint.com/student/path/187904/activity/157872

#### Capítulo 2 - Business Manager
En este capítulo, aprenderá todo lo que necesita para comenzar con Business Manager, desde crear su cuenta y agregar activos, hasta asignar los permisos correctos a todo su equipo.

https://www.facebookblueprint.com/student/path/187904/activity/157873

#### Capítulo 3 - Crear y Configurar Facebook Pixel
En este capítulo, aprenderá cómo crear un píxel de Facebook, configurarlo en un sitio web y comenzar a enviar eventos.

```
<!-- Facebook Pixel Code -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', 'SU_ID');
  fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
  src="https://www.facebook.com/tr?id=2437036956613639&ev=PageView&noscript=1"
/></noscript>
<!-- End Facebook Pixel Code -->

```

> Una vez que haya creado su píxel, debe incrustar el código de píxel en su sitio web.

> En el código de su página web, busque las etiquetas < head > </ head>. Antes del final de la etiqueta < head >, inserte su código de píxel.

https://www.facebookblueprint.com/student/path/187904/activity/157874

#### Capítulo 4 - Eventos y Parámetros avanzados
En este capítulo, aprenderá a usar JavaScript para enviar eventos múltiples y personalizados en una página, e incluirá datos más allá de la URL de referencia. Luego puede usar estos eventos y los datos personalizados asociados en Facebook para definir una audiencia personalizada y realizar un seguimiento del rendimiento de sus campañas publicitarias.

https://www.facebookblueprint.com/student/path/187904/activity/157875


#### Capítulo 5 - Sistemas de Tag Manager
En este capítulo, aprenderá cómo colocar el píxel de Facebook en diferentes gestores de etiquetas e integrarlo en diferentes plataformas de sitios web. Para más detalles, haga clic aquí.

El Administrador de etiquetas permite a las personas actualizar rápida y fácilmente los códigos de seguimiento y los fragmentos de código relacionados conocidos colectivamente como "etiquetas" en su sitio web. Una vez que se ha agregado el fragmento web de Tag Manager, los especialistas en marketing pueden configurar e implementar sus configuraciones de etiquetas desde una interfaz de usuario basada en la web sin involucrar a ningún desarrollador cada vez que necesiten hacer cambios.

https://www.facebookblueprint.com/student/path/187904/activity/158699

#### Capítulo 6 - Matching Avanzado
En este capítulo, aprenderá cómo puede enviar datos de clientes adicionales a través del píxel de Facebook para hacer coincidir más acciones del sitio web con los usuarios de Facebook.

https://www.facebookblueprint.com/student/path/187904/activity/159199

#### Capítulo 7 - Ads Dinámicos

En este capítulo, aprenderá qué son los anuncios dinámicos, cómo funcionan y cómo configurarlos para promocionar sus productos en Facebook.

https://www.facebookblueprint.com/student/path/187904/activity/159200

#### Capítulo 8 - Configurar Catalog 
En este capítulo, aprenderá cómo configurar un catálogo y cómo actualizarlo para promover su inventario (como productos físicos, hoteles, vuelos u otros servicios) en Facebook.

Un catálogo es un contenedor para el inventario que desea vender o promocionar de otra manera en Facebook, Instagram, WhatsApp o Audience Network. Se puede usar para entregar anuncios dinámicos, crear publicaciones de Instagram Shopping, agregar a la sección Comprar de una página de Facebook o crear listados en Marketplace.

https://www.facebookblueprint.com/student/path/187904/activity/159375

#### Capítulo 9 - Matching de Eventos

En el Capítulo 7 ("Eventos y parámetros"), trabajamos en la configuración de señales y catálogos para ejecutar anuncios dinámicos de productos, y pudimos echar un vistazo a las soluciones específicas que Facebook tiene para diferentes verticales.

La primera solución que Facebook lanzó para una vertical específica fue Dynamic Ads for Travel (ahora conocida como Travel ads). Esta industria tiene reglas diferentes al comercio electrónico clásico, donde la información, como las fechas de entrada y salida, las estrellas del hotel y la ubicación son más importantes que una categoría de producto. Las campañas relacionadas con los viajes se benefician enormemente al disparar señales que son más ricas en datos relacionados con los viajes.
 
https://www.facebookblueprint.com/student/path/187904/activity/160302

#### Contributors: DevC Lead: Ciudad de México (Martín Manriquez), Bogotá (Ana B. Martínez & Oscar Barajas), Guatemala (Daniel Lara), San José (Leo Camacho).  

