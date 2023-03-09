---
title: "Cacharreando Con C++"
date: 2023-03-09T18:50:40+01:00
draft: true
---

# Mi primera aventura con C++

Hola en el post de hoy vengo a comentaros como han sido mi primera toma de contacto con un proyecto más avanzado de C++, más allá de los pequeños programas que nos hacen hacer en la universidad.  

He de decir que me ha sorprendido en más de un aspecto el flujo de trabajo, para empezar he notado la imposición a aprender y adoptar varios lenguajes de apoyo como make, cmake para poder cimentar las reglas para compilar los proyectos en este lenguaje. Me disculpo por los que realmente saben del tema por si soy poco preciso con algún concepto pero queria dejar constancia de mi travesia en este proyecto.  

Para dar algo de contexto voy a explicar que este proyecto nace de una libreria para comunicarse con servidores de correo. En la empresa para la que trabajo hacen uso de [Vmime](https://github.com/kisli/vmime) para añadir la comunicación por medio de diferentes protocolos a los servidores de correo que usen nuestros clientes.  
Pues desde hace unos meses varios clientes reportaon problemas para usar sus cuentas de un proveedor especifico que no mencionaré, el punto es que esta misma libreria está obsoleta, dejó de actualizarse en 2021 a fecha de hoy y no parece que vayan a volver a mantenerla en los próximos años.  

Por una serie de desdichas acabó en mi la responsabilidad de arreglar este problema, de esto hará ya 3 meses y por el camino puedo decir que he experimentado la mayor mezcla de frustación y aprendizaje de mi tiempo como programador y estudiante.  

Pero tocó empezar a mirar el proyecto, por suerte he tenido a mi disposición todas las herramientas que podría necesitar, tengo una dilatada experiencia de navegar a través de código sin documentar y entremezclado, he podido disfrutar de un amplio tiempo acomodando conocimientos sobre los procolos de correo, de sus metodos de autenticación y sobretodo las excelentes clases de iniciación de c++ por parte de dos de los mejores ingenieros que he tenido oportunidad de conocer.
Con todo me puse a estudiar la libreria como se compila, las principales clases que interfieren en mi cometido o sus dependecias.

Con esto empieza mi aventura en C++, donde relataré mis descubrimientos en este mismo blog para dejar constancia de ello.