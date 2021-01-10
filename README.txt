********************************************************************************************************************************
Maximiliano Ojeda 201773576-7

Forward Checking y CBJ para resolver el VRPB

Se adjuntan las intrucciones para la compilación y ejecución del programa. Para ejecutar los siguientes
comandos se debe estar en el directorio donde se encuentran los archivos de código de fuente con el makefile.

Compilación:
    make

Ejecución:
    make exe ins={nombre_instancia.txt}     Ej: make exe ins=GA2.txt; siempre y cuando la instancia este en el mismo directorio.

Borrar archivos generados:
    make clean

Notas:
-Para la ejecución del programa con "make exe ins={}", el nombre de la instancia debe ir con la extensión ".txt".
-La instancia se puede encontrar dentro de una carpeta en el path que se encuentra el programa y pasar la instancia
 al programa como "make exe ins=Carpeta/instancia.txt" En este caso el archivo de salida se creará dentro de esa misma carpeta.
-Al ejecutar solo "make exe" el programa buscará la instancia GA1.txt como predeterminado para la ejecución.
**********************************************************************************************************************************
