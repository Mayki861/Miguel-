1. Eclipse Public License 2.0 (EPL 2.0)
•	Descripción: Es una licencia de código abierto desarrollada por la Eclipse Foundation. Es una licencia "copyleft débil" o de alcance limitado, lo que significa que el código modificado debe licenciarse bajo la EPL, pero si el código EPL se integra en un módulo más grande, ese módulo no tiene que ser EPL.
•	Ventajas:
o	Permite la integración en software propietario con menos restricciones que las GPL.
o	Fomenta la colaboración y el uso comercial.
o	Evita "viralidad" a todo el proyecto.
•	Desventajas:
o	Requiere que las modificaciones al código EPL se distribuyan bajo la EPL.
o	Puede ser menos "libre" que las GPL en términos de asegurar que todo el software derivado sea libre.
•	Para qué sirve: Ideal para proyectos que buscan ser de código abierto pero que también desean permitir su uso en productos comerciales cerrados, como muchos proyectos de la comunidad Eclipse.
2. GNU Affero General Public License v3.0 (AGPLv3)
•	Descripción: Es una licencia "copyleft fuerte" de la Free Software Foundation. A diferencia de la GPL tradicional, la AGPLv3 cierra la "laguna de la red", lo que significa que si el software se ejecuta en un servidor y se ofrece como un servicio a través de una red, el código fuente modificado debe ponerse a disposición de los usuarios de ese servicio.
•	Ventajas:
o	Garantiza que el software y todos sus derivados permanezcan libres, incluso cuando se usan como servicios en la nube.
o	Maximiza la libertad del usuario final.
•	Desventajas:
o	Altamente "viral" – cualquier uso o modificación requiere la liberación del código bajo la AGPL.
o	Puede disuadir el uso en servicios comerciales donde no se desea liberar el código fuente de las modificaciones.
•	Para qué sirve: Para proyectos que desean garantizar que su código fuente y todas sus modificaciones sean accesibles a los usuarios, incluso cuando se implementan como servicios de red (SaaS).
3. GNU General Public License v2.0 (GPLv2) y v3.0 (GPLv3)
•	Descripción: Son licencias "copyleft fuerte" de la Free Software Foundation. Exigen que cualquier software que incorpore código GPL, o sea un derivado de él, también debe licenciarse bajo la GPL. La GPLv3 incluye protecciones contra la tivoización (restricción de hardware para ejecutar software modificado) y cláusulas de patentes.
•	Ventajas:
o	Garantizan que el software y sus derivados permanezcan libres.
o	Fomentan la colaboración en la comunidad de software libre.
o	La GPLv3 ofrece protecciones adicionales (patentes, tivoización).
•	Desventajas:
o	Altamente "viral" – cualquier proyecto que use código GPL se convierte en GPL.
o	Puede ser incompatible con licencias permisivas en algunos casos.
•	Para qué sirve: Para proyectos que buscan asegurar que su software siempre permanezca libre y de código abierto, promoviendo un ecosistema de software libre. Muchos proyectos populares como Linux (GPLv2) y Git (GPLv2) la usan.
4. GNU Lesser General Public License v2.1 (LGPL v2.1)
•	Descripción: Es una licencia "copyleft débil" de la Free Software Foundation. Permite que las bibliotecas licenciadas bajo la LGPL sean enlazadas con software propietario, sin que este software tenga que ser liberado bajo la LGPL. Sin embargo, cualquier modificación a la biblioteca LGPL en sí debe permanecer bajo la LGPL.
•	Ventajas:
o	Permite el uso de bibliotecas de software libre en proyectos propietarios.
o	Promueve la reutilización de código.
o	Mantiene las mejoras a la biblioteca bajo la LGPL.
•	Desventajas:
o	Las modificaciones a la propia biblioteca LGPL deben ser liberadas.
o	Menos "libre" que la GPL en términos de asegurar que todo el software derivado sea libre.
•	Para qué sirve: Ideal para bibliotecas o componentes que se desean ofrecer a desarrolladores para usar en una amplia variedad de proyectos, incluyendo aquellos de código cerrado, mientras se asegura que las mejoras a la biblioteca beneficien a la comunidad.
5. Mozilla Public License 2.0 (MPL 2.0)
•	Descripción: Es una licencia "copyleft débil" o "por archivo" de la Mozilla Foundation. Permite la mezcla de código MPL con código propietario o de otras licencias, siempre y cuando las modificaciones al archivo original con licencia MPL se liberen bajo la MPL.
•	Ventajas:
o	Flexibilidad para combinar con software propietario.
o	Fomenta la contribución a los archivos originales MPL.
o	Claridad sobre qué partes del código deben ser libres.
•	Desventajas:
o	Puede ser más compleja de gestionar en proyectos muy grandes con muchas dependencias.
o	Menos "viral" que las GPL, por lo que no garantiza que todo el proyecto sea libre.
•	Para qué sirve: Usada por proyectos como Firefox, es adecuada para el desarrollo de aplicaciones que desean ser de código abierto pero que necesitan coexistir con módulos propietarios o de otras licencias.
6. The Unlicense
•	Descripción: Es esencialmente una dedicación de software al dominio público. Intenta renunciar a todos los derechos de autor y derechos relacionados. Es una licencia extremadamente permisiva.
•	Ventajas:
o	Máxima libertad: el software puede ser usado sin restricciones de copyright.
o	No requiere atribución.
o	Extremadamente simple.
•	Desventajas:
o	Al no ser una licencia reconocida globalmente como tal, en algunas jurisdicciones puede que no sea legalmente vinculante para renunciar a todos los derechos.
o	Puede generar incertidumbre legal en entornos corporativos.
o	No hay garantías ni responsabilidades.
•	Para qué sirve: Para proyectos muy pequeños o fragmentos de código que el autor desea que sean de dominio público sin ninguna restricción legal.
7. Apache License 2.0
•	Descripción: Una licencia permisiva muy popular de la Apache Software Foundation. Permite el uso, modificación y distribución del software con muy pocas restricciones, incluyendo el uso en software propietario. Requiere que se mantengan los avisos de copyright y atribución.
•	Ventajas:
o	Muy permisiva, ideal para uso comercial y propietario.
o	Incluye una cláusula de patentes explícita que protege a los usuarios de demandas por patentes.
o	Amplia adopción y aceptación.
•	Desventajas:
o	No garantiza que las modificaciones o el software derivado permanezcan de código abierto.
o	Puede no ser compatible con licencias GPLv2 en algunos casos.
•	Para qué sirve: Ampliamente utilizada en proyectos empresariales y de código abierto que desean ser fácilmente adoptados y modificados por otros, incluyendo empresas. Ejemplos: Android, Hadoop.
8. MIT License
•	Descripción: Una de las licencias de software libre más simples y permisivas. Permite el uso, copia, modificación, fusión, publicación, distribución, sublicencia y/o venta de copias del software. La única condición es que el aviso de derechos de autor y este aviso de permiso se incluyan en todas las copias o partes sustanciales del software.
•	Ventajas:
o	Extremadamente simple y fácil de entender.
o	Máxima libertad para el usuario y el desarrollador.
o	Compatible con casi todas las demás licencias.
o	Favorece la adopción y el uso en proyectos propietarios.
•	Desventajas:
o	No ofrece protección de patentes (a diferencia de Apache 2.0).
o	No obliga a mantener el código abierto.
•	Para qué sirve: Ideal para proyectos que buscan la máxima flexibilidad y adopción, tanto en el ámbito de código abierto como en el propietario. Es muy común para bibliotecas JavaScript, front-end, etc.
9. BSD 2-Clause "Simplified" License y BSD 3-Clause "New" or "Revised" License
•	Descripción: Son licencias permisivas similares a la MIT, originarias de la Universidad de California, Berkeley.
o	BSD 2-Clause: Requiere mantener el aviso de copyright y la cláusula de descargo de responsabilidad.
o	BSD 3-Clause: Añade una tercera cláusula que prohíbe el uso del nombre de los contribuidores o de la organización para promocionar productos derivados sin permiso explícito.
•	Ventajas:
o	Muy permisivas, permiten el uso en software propietario.
o	Simples y fáciles de entender.
o	Compatibles con la mayoría de las licencias.
•	Desventajas:
o	No ofrecen protección de patentes.
o	No obligan a mantener el código abierto.
o	La cláusula de no respaldo de la BSD 3-Clause puede ser una ligera complicación.
•	Para qué sirve: Utilizadas por muchos proyectos de código abierto que buscan máxima flexibilidad y adopción comercial sin la "viralidad" de las GPL.
10. Boost Software License 1.0
•	Descripción: Una licencia permisiva diseñada para las bibliotecas C++ de Boost. Es similar a la MIT y BSD, permitiendo el uso y redistribución con la condición de mantener el aviso de licencia.
•	Ventajas:
o	Muy permisiva y compatible con software propietario.
o	Diseñada específicamente para bibliotecas, lo que puede ser útil para desarrolladores de C++.
•	Desventajas:
o	No obliga a mantener el código abierto.
o	No incluye protección de patentes explícita.
•	Para qué sirve: Principalmente para las bibliotecas Boost, pero también puede ser utilizada para otros proyectos que busquen una licencia permisiva y sencilla.
11. Creative Commons Zero v1.0 Universal (CC0)
•	Descripción: Aunque no es una licencia de software tradicional, CC0 es una dedicación al dominio público que permite a los creadores renunciar a sus derechos de autor y derechos conexos sobre su obra, colocando la obra en el dominio público a nivel mundial. A menudo se utiliza para datos, imágenes y otros contenidos, pero también se puede usar para código.
•	Ventajas:
o	Máxima libertad: la obra puede ser usada sin restricciones de copyright.
o	Simplifica enormemente el uso y la reutilización.
•	Desventajas:
o	No es una licencia de software formal y puede generar dudas legales en algunas jurisdicciones o entornos corporativos que prefieren licencias de software explícitas.
o	No hay garantías ni responsabilidades.
•	Para qué sirve: Principalmente para liberar contenido (datos, imágenes, textos, etc.) al dominio público. En el ámbito del software, se usa para pequeños fragmentos de código o scripts que el autor quiere que sean de dominio público sin ninguna restricción.

