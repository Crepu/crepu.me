Title: Primer post!
Date: 2020-04-08 16:21
Modified: 2020-04-08 16:21
Category: Test
Tags: testing, learning, documenting
Slug: primer-post
Author: Creps
Summary: Como hice para que puedas ver este sitio.
Status: published

# Benvendid

Por fin llegó la hora de armar mi sitio. Luego de levantar una instancia en AWS, con toda la configuración de las redes e interfaces para dejarla pública en internet, pude obtener mi dirección IP.

Esa IP la usé en el gestor de mi dominio, que es Gandi, para que el dominio que tengo (crepu.me) mostrara la página. En el servidor instalé lighttpd como servidor de contenidos web.

Usé certbot para crear un certificado de confianza y poder navegar a través de la capa segura de HTTP. Tuve que agregar algunos parametros especiales y combinar un par de archivos generados por certbot para que funcionara.

Para la creación de la página principal y el blog, utilizo [Pelican]({static}/pdfs/pelican-stable-docs.pdf){:target="_blank"} y Markdown.