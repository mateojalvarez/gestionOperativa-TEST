//Descripción//

Script específico para realizar una consulta, recorriendo todos los ítems publicados por el seller_id = 179571326 del site_id = "MLA" . Además, genera un archivo de LOG que contiene los siguientes datos de cada ítem: a. "id" del ítem, "title" del item, "category_id" donde está publicado, "domain_id" de la categoría.

Dos soluciones están cargadas, en primer lugar utilizando únicamente PHP

// INTRSTUCCIONES DE USO //

APACHE DEBE ESTAR INICIALIZADO

- Abrir script.php con un editor de código.
- Insertar la información necesaria para ejecutar la consulta ($SITE_ID && $SELLER_ID)
- Con dicha información realizará la consulta:
	- Ejecutar el archivo en el navegador.
	- En caso de éxito, creará un archivo .json con la siguiente información:
		-"id" del ítem,
		-"title" del item,
		-"category_id" donde está publicado,
		-"name" de la categoría.
	Además imprimirá en pantalla el desglose de los resultados obtenidos.
  
Implementando JAVASCRIPT Y JQUERY 
  
// INTRSTUCCIONES DE USO //

APACHE DEBE ESTAR INICIALIZADO

- Abrir script.html en el navegador
- La aplicación solicitará la información necesaria para realizar la consulta (site_id && seller_id)
- Con dicha información realizará la consulta:
	- En caso de éxito, creará un archivo .json con la siguiente información:
		-"id" del ítem,
		-"title" del item,
		-"category_id" donde está publicado,
		-"name" de la categoría.
	Además, le ofrecerá al usuario descargar el archivo en el momento.
	- En caso de no poder realizar la consulta, se desplegará un alert()
