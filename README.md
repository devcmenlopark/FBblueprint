## Grupo de Estudio DevC LATAM para la Certificación en Facebook Ad Products Developer I 🤖 
Documentación en Español para la preparación a la [Certificación en Facebook Ad Products Developer I](https://www.facebook.com/business/learn/certification/exams/500-101-exam)
 del programa Facebook Blueprint: https://www.facebook.com/business/learn/certification/ La traducción del repositorio está desarrollada mediante la contribución de líderes de comunidades Developer Circles de LATAM en ciudades como 🇲🇽 Ciudad de México, 🇨🇴 Bogotá, 🇬🇹 Guatemala & 🇨🇷 San José. 



#### Capítulo 1 - Facebook Pixel: Qué es y cómo funciona?
En este capítulo, aprenderá los beneficios de usar un píxel de Facebook, qué es y cómo funciona. El píxel de Facebook es una herramienta que lo ayuda a comprender las actividades de un consumidor en su sitio web y a utilizar esas actividades en la plataforma de Facebook para medir la efectividad de su publicidad, optimizar el targeting & retargeting de sus anuncios y definir su propio público objetivo.

**Beneficios:**
1)Evaluar el retorno sobre su inversión en el gasto de anuncios.
2)Medir conversiones en múltiples dispositivos.
3)Optimizar la efectividad de sus anuncios. 

**FB Live:** https://www.facebook.com/leo.aiassistant/videos/10157336070437279/

> Curso 1: https://www.facebookblueprint.com/student/path/187904/activity/157872

#### Capítulo 2 - Business Manager
En este capítulo, aprenderá todo lo que necesita para comenzar con Business Manager: https://business.facebook.com desde crear su cuenta y agregar activos, hasta asignar los permisos correctos a todo su equipo. El Business Manager es una plataforma gratuita de FB que nos ayuda a integrar los esfuerzos de Marketing en un solo lugar:

-Realice y mida sus campañas de anuncios.
-Administre activos (Páginas & Cuentas de anuncios)
-Agregue agencias or Partners de Marketing

**Cada Business Manager puede crear un máximo de 10 Pixel codes. **

**FB Live:** https://www.facebook.com/leo.aiassistant/videos/10157336070437279/

> Curso 2: https://www.facebookblueprint.com/student/path/187904/activity/157873



#### Capítulo 3 - Crear y Configurar Facebook Pixel
En este capítulo, aprenderá cómo crear un píxel de Facebook, configurarlo en un sitio web y comenzar a enviar eventos. Existen 3 opciones para integrar el código Píxel: i_Integrar Manualmente, ii_Utilizar un Tag Manager o iii_Enviar por email las instrucciones al desarrollador.

A continuación se describe la opción de integración manualmente:

> Una vez que haya creado su píxel, debe incrustar el código de píxel en su sitio web.

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
  src="https://www.facebook.com/tr?id={SU_ID}&ev=PageView&noscript=1"
/></noscript>
<!-- End Facebook Pixel Code -->

```

> En el código de su página web, busque las etiquetas < head > </ head>. Antes del final de la etiqueta < head >, inserte su código de píxel.

**Cómo se hace el match de personas?**
1. FB almacena un hash (IP, Agent, FB Login Data).
2. Cuanda un sitio web recibe una visita (FB server recibe un PixellCall).
3. FB almacena esa visita con un Hash.
4. En este momento FB puede asociar patrones con un id. 


**FB Live:** https://www.facebook.com/leo.aiassistant/videos/10157336070437279/

> Curso 3: https://www.facebookblueprint.com/student/path/187904/activity/157874



#### Capítulo 4 - Eventos y Parámetros avanzados
En este capítulo, aprenderá a usar JavaScript para enviar eventos múltiples y personalizados en una página, e incluirá datos más allá de la URL de referencia. Luego puede usar estos eventos y los datos personalizados asociados en Facebook para definir una audiencia personalizada y realizar un seguimiento del rendimiento de sus campañas publicitarias.

> Curso 4: https://www.facebookblueprint.com/student/path/187904/activity/157875


#### Capítulo 5 - Sistemas de Tag Manager
En este capítulo, aprenderá cómo colocar el píxel de Facebook en diferentes gestores de etiquetas e integrarlo en diferentes plataformas de sitios web. Para más detalles, haga clic aquí.

El Administrador de etiquetas permite a las personas actualizar rápida y fácilmente los códigos de seguimiento y los fragmentos de código relacionados conocidos colectivamente como "etiquetas" en su sitio web. Una vez que se ha agregado el fragmento web de Tag Manager, los especialistas en marketing pueden configurar e implementar sus configuraciones de etiquetas desde una interfaz de usuario basada en la web sin involucrar a ningún desarrollador cada vez que necesiten hacer cambios.

> Curso 5: https://www.facebookblueprint.com/student/path/187904/activity/158699

#### Capítulo 6 - Matching Avanzado
En este capítulo, aprenderá cómo puede enviar datos de clientes adicionales a través del píxel de Facebook para hacer coincidir más acciones del sitio web con los usuarios de Facebook.

> Curso 6: https://www.facebookblueprint.com/student/path/187904/activity/159199

#### Capítulo 7 - Ads Dinámicos

En este capítulo, aprenderá qué son los anuncios dinámicos, cómo funcionan y cómo configurarlos para promocionar sus productos en Facebook.

> Curso 7: https://www.facebookblueprint.com/student/path/187904/activity/159200

#### Capítulo 8 - Configurar Catalog 
En este capítulo, aprenderá cómo configurar un catálogo y cómo actualizarlo para promover su inventario (como productos físicos, hoteles, vuelos u otros servicios) en Facebook.

Un catálogo es un contenedor para el inventario que desea vender o promocionar de otra manera en Facebook, Instagram, WhatsApp o Audience Network. Se puede usar para entregar anuncios dinámicos, crear publicaciones de Instagram Shopping, agregar a la sección Comprar de una página de Facebook o crear listados en Marketplace.

> Curso 8: https://www.facebookblueprint.com/student/path/187904/activity/159375

#### Capítulo 9 - Matching de Eventos

En el Capítulo 7 ("Eventos y parámetros"), trabajamos en la configuración de señales y catálogos para ejecutar anuncios dinámicos de productos, y pudimos echar un vistazo a las soluciones específicas que Facebook tiene para diferentes verticales.

La primera solución que Facebook lanzó para una vertical específica fue Dynamic Ads for Travel (ahora conocida como Travel ads). Esta industria tiene reglas diferentes al comercio electrónico clásico, donde la información, como las fechas de entrada y salida, las estrellas del hotel y la ubicación son más importantes que una categoría de producto. Las campañas relacionadas con los viajes se benefician enormemente al disparar señales que son más ricas en datos relacionados con los viajes.
 
> Curso 9: https://www.facebookblueprint.com/student/path/187904/activity/160302

#### Contributors: DevC Lead: Ciudad de México (Martín Manriquez), Bogotá (Ana B. Martínez, Camilo Montañez & Oscar Barajas), Guatemala (Daniel Lara), San José (Leo Camacho).  

