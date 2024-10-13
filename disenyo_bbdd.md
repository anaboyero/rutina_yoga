++++++++++++++++++++++++++++++++++

TABLA CATEGORIA

id_cat PK
nombre
beneficios

++++++++++++++++++++++++++++++++++


TABLA NIVEL

id_nivel PK
nivel


++++++++++++++++++++++++++++++++++


TABLA POSTURA

(( id_postura PK 
id_cat FK 
id_nivel FK)) PK COMPUESTA

nombre
nombre_sans
descripcion
beneficios
url_svg,
url_png,
url_svg_alt


# id,nombre,nombre_sans,categoria,categoria_id,descripcion,beneficios,url_svg,url_png,url_svg_alt


+++++++++++++++++++++++++++++++++


