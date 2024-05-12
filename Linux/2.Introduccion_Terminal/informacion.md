<!-- Autor: Daniel Benjamin Perez Morales -->
<!-- GitHub: https://github.com/DanielPerezMoralesDev13 -->
<!-- Correo electrónico: danielperezdev@proton.me  -->

# **_Introduccion ala terminal_**

## **Indice**

- [**_Introduccion ala terminal_**](#introduccion-ala-terminal)
  - [**Indice**](#indice)
- [**_Primeros Comandos_**](#primeros-comandos)

---

# **_Primeros Comandos_**

> **Conceptos importantes sobre linux**

1. _Directorio: En programacion un directorio es una carpeta_

2. _Fichero: En programacion un fichero es una archivo con o sin extensio_

   1. **Ejemplo:**

        ```bash
         script.py
         ```

   2. _script es el nombre del fichero y lo que esta luego del punto es la extension del fichero_

3. _**.** : Representa el directorio actual._

4. _**~**: Representa el directorio home del usuario actual._

   1. _Por ejemplo, si tu nombre de usuario es daniel, ~ generalmente se traduciría a /home/daniel._

5. _**..**: Representa el directorio padre del directorio actual. Entonces, si estás en /home/daniel/Escritorio/carpeta y ejecutas cd .., te moverías al directorio /home/daniel/Escritorio._

   1. _**Ejemplo:** ../descargas: Esto te movería al directorio descargas que se encuentra en el mismo nivel que tu directorio actual. Entonces, si estás en /home/daniel/Escritorio/carpeta y ejecutas_

       ```bash
       cd ../descargas 
       ```

   2. _Te moverías al directorio /home/daniel/Escritorio/descargas._

> _**Comandos**_

1. _<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>t</kbd>_

   - _Abre una nueva ventana de terminal_

2. `_whoami_`

   ```bash
   whoami
   ```

    - _imprimir el nombre de usuario del usuario actual_

    - **Traduccion:** _whoami ,quién soy yo?_

3. `_pwd_`

   ```bash
   pwd
   ```

    - _muestra la ruta completa del directorio en el que te encuentras actualmente_
    - Traduccion: _"Print Working Directory", que se traduce al español como "Imprimir el Directorio de Trabajo_

4. _clear_

   ```bash
   clear
   ```

    - _limpiar la pantalla de la termina_
    - **Traduccion:** _clear, limpiar_

   1. _Otra manera de hacerlo_

      - <kbd>Ctrl</kbd> + <kbd>l</kbd>

5. `_cd <directorio>_`

     ```bash
      cd <directorio>
      ```

   - _Este comando se utiliza para cambiar el directorio de trabajo actual a otro directorio y toma como parametro el nombre del directorio_

     - _Entonces, cd . simplemente te mantendría en el mismo directorio._

   - **Traduccion:** _Change Directory, Cambiar - Directorio_

6. `_ls_`

   ```bash
   ls ./
   ```

   ```bash
   ls ./Escritorio/
   ```

   ```bash
   ls ../
   ```

   ```bash
   ls ../carpeta/
   ```

   - _Este comando se utiliza para listar los archivos y directorios en el directorio actual. **Tambien se le puede pasar rutas relativas como absoluta**_
   - **Traduccion:** _"List", lista_

7. `_mkdir_`

   ```bash
   mkdir directorio/
   ```

   ```bash
   mkdir ./Escritorio/carpeta/
   ```

   ```bash
   mkdir ../carpeta/
   ```

   ```bash
   mkdir directorio/ otro/
   ```

   ```bash
   mkdir ./Escritorio/carpeta ./Escritorio/otro/
   ```

   ```bash
   mkdir ../carpeta/ ../otro/
   ```

   ```bash
   mkdir ./"nuevo directorio"/
   ```

   ```bash
   mkdir ./nuevo\ directorio/
   ```

   - _Este comando se utiliza para crear un nuevo directorio. Toma como parámetro el nombre del directorio que se desea crear. **Tambien se le puede pasar rutas relativas como absoluta**_

   - **Traduccion:** _Make Directory, Crear Directorio_

8. `_rmdir_`

   ```bash
   rmdir directorio/
   ```

   ```bash
   rmdir ./Escritorio/carpeta/
   ```

   ```bash
   rmdir ../carpeta/
   ```

   ```bash
   rmdir directorio/ otro/
   ```

   ```bash
   rmdir ./Escritorio/carpeta/ ./Escritorio/otro/
   ```

   ```bash
   rmdir ../carpeta/ ../otro/
   ```

   ```bash
   rmdir ./"nuevo directorio"/
   ```

   ```bash
   rmdir ./nuevo\ directorio/
   ```

   - _Este comando se utiliza para eliminar un directorio vacío. Toma como parámetro el nombre del directorio que se desea eliminar. **Tambien se le puede pasar rutas relativas como absoluta**_

     - _**Nota:** rmdir sólo eliminará un directorio si está vacío_

     - **Se pueden pasar mas de un parametro**

   - **Traduccion:** _Remove Directory,Eliminar Directorio_

9. `_touch_`

   ```bash
   touch fichero.txt
   ```

   ```bash
   touch ./Escritorio/carpeta/fichero.txt
   ```

   ```bash
   touch ../carpeta/fichero.txt
   ```

      ```bash
      touch fichero.txt fichero2.txt
      ```

      ```bash
      touch ./Escritorio/carpeta/fichero.txt ./Escritorio/carpeta/fichero2.txt
      ```

      ```bash
      touch ../carpeta/fichero.txt ../carpeta/copia.txt
      ```

      ```bash
      touch ./"mi primer programa.py"
      ```

      ```bash
      touch ./"mi primer programa".py
      ```

      ```bash
      touch ./mi\ primer\ programa.py
      ```

   - _El comando touch en Linux se utiliza para cambiar las marcas de tiempo de acceso y modificación de un archivo. También se puede utilizar para crear un nuevo archivo si el archivo especificado no existe. **Tambien se le puede pasar rutas relativas como absoluta**_

   - **Se pueden pasar mas de un parametro**

10. `_rm_`

      ```bash
      rm fichero.txt
      ```

      ```bash
      rm ./Escritorio/carpeta/fichero.txt
      ```

      ```bash
      rm ../carpeta/fichero.txt
      ```

      ```bash
      rm fichero.txt copia.txt
      ```

      ```bash
      rm ./Escritorio/carpeta/fichero.txt ./Escritorio/carpeta/copia.txt
      ```

      ```bash
      rm ../carpeta/fichero.txt ../carpeta/copia.txt
      ```

      ```bash
      rm ./"mi primer programa.py"
      ```

      ```bash
      rm ./"mi primer programa".py
      ```

      ```bash
      rm ./mi\ primer\ programa.py
      ```

      - _El comando rm en Linux se utiliza para eliminar archivos y directorios. **Tambien se le puede pasar rutas relativas como absoluta**_

        - **Se pueden pasar mas de un parametro**

        - _Este comando eliminará el archivo llamado fichero.txt del directorio actual. Ten en cuenta que este comando no moverá el archivo a la papelera de reciclaje, sino que lo eliminará permanentemente. Por lo tanto, debes tener cuidado al usarlo._

      - **Traduccion:** _Las siglas rm provienen del inglés y significan "remove", que en español se traduce como "eliminar"._

11. `_cp_`

      ```bash
      cp fichero.txt ./copia.txt
      ```

      ```bash
      cp ./Escritorio/carpeta/fichero.txt ./Escritorio/carpeta/copia.txt
      ```

      ```bash
      cp ../carpeta/fichero.txt ../carpeta/copia.txt
      ```

      - _Se utilizan para copiar ficheros._

        - _Si la el fichero ya existe, será sobrescrito._

      - **Traduccion:** _cp proviene de las siglas en inglés "copy", que significa "copiar"._

12. `_mv_`

    ```bash
    mv fichero.txt ./copia.txt
    ```

    ```bash
    mv ./Escritorio/carpeta/fichero.txt ./Escritorio/carpeta/copia.txt
    ```

    ```bash
    mv ../carpeta/fichero.txt ../carpeta/copia.txt
    ```  

    - _Este comando mover el fichero a otra ubicacion si ya existe, será sobrescrito._

      - _Además, mv también se puede utilizar para renombrar archivos._

    - **Traduccion:** _mv proviene de las siglas en inglés "move", que significa "mover"._

13. `_echo_`

      ```bash
       echo "Este mensaje se imprimira en la terminal"
       ```

      ```bash
      echo $HOME
      ```

     - _El comando echo en Linux se utiliza para mostrar una línea de texto u otras variables de entorno en la terminal._

     - **Traduccion:** _echo es una palabra en inglés que significa "eco", en el sentido de repetir lo que se le da._

14. `_cat_`

      ```bash
      cat ./fichero.txt
      ```

      ```bash
      cat ./fichero.txt ./fichero2.txt
      ```

      ```bash
      cat ./fichero.txt > ./fichero2.txt
      ```

      ```bash
      cat ./Escritorio/carpeta/fichero.txt
      ```

      ```bash
      cat ./Escritorio/carpeta/fichero.txt ./Escritorio/carpeta/fichero2.txt
      ```

      ```bash
      cat ./Escritorio/carpeta/fichero.txt > ./Escritorio/carpeta/fichero2.txt
      ```

      ```bash
      cat ../carpeta/fichero.txt
      ```

      ```bash
      cat ../carpeta/fichero.txt ../carpeta/fichero2.txt
      ```

      ```bash
      cat ../carpeta/fichero.txt > ../carpeta/fichero2.txt
      ```

      ```bash
      cat ./fichero.txt ./fichero2.txt > fichero3.txt
      ```

     - _El comando cat en Linux se utiliza para concatenar y mostrar archivos._

       - _Este comando concatenará el contenido de **fichero.txt** y **fichero2.txt**, y el resultado se guardará en **archivo3.txt**. **Si fichero3.txt ya existe, será sobrescrito si no sera se creara el archivo.**_

       - _El símbolo > en Linux se utiliza para redirigir la salida de un comando a un fichero._

       - **Se pueden pasar mas de un parametro**

     - **Traduccion:** _cat es una abreviatura de la palabra en inglés "concatenate", que significa "concatenar"._

15. `_man <command>_`

      ```bash
      man ls
      ```

      - _El comandos man en Linux se utiliza para obtener ayuda sobre un comando toma como parametro el comando._

      - **Traduccion:** _man es un acrónimo de "manual", y man `<comando>` muestra la página del manual para el `<comando>`. Las páginas del manual contienen una descripción detallada del comando, sus opciones y su uso._

16. `_nano <fichero>_`

      ```bash
      nano fichero.txt
      ```

      - _nano es un editor de texto en la línea de comandos de Linux. nano archivo.txt abrirá el archivo archivo.txt en el editor nano._

17. `_grep palabra <fichero>_`

      ```bash
      grep lista fichero.txt
      ```

    - _El comando grep en Linux se utiliza para buscar texto en archivos._

      - _El comando grep lista fichero.txt buscará la palabra "lista" en el archivo fichero.txt y mostrará las líneas que contienen esa palabra._

    - **Traduccion:** _grep es un acrónimo de "Global Regular Expression Print", Impresión global de expresiones regulares._

18. `_comando con opciones_`

     - > _Las opciones en Linux, también conocidas como flags o switches, son argumentos que se utilizan para modificar el comportamiento de un comando. Generalmente se añaden después del nombre del comando y antes de cualquier otro argumento._

       - > _Las opciones suelen comenzar con un guion - o dos guiones --. Las opciones que comienzan con un solo guion suelen ser abreviaturas de una sola letra, mientras que las opciones que comienzan con dos guiones suelen ser palabras completas._

     ```bash
     <command> --help
     ```

      ```bash
      ls --help
      ```

       - _Este comando mostrará la ayuda para el comando `ls`_

   ```bash
   rm -r ./carpeta
   ```

   ```bash
   rm -r -i ./carpeta
   ```

   ```bash
   rm -ri ./carpeta
   ```

   ```bash
   rm -ir ./carpeta
   ```

   ```bash
   rm --recursive ./carpeta 
   ```

   ```bash
   rm --recursive --interactive ./carpeta
   ```

   ```bash
   rm --interactive --recursive ./carpeta
   ```

   ```bash
   rm --recursive -i ./carpeta
   ```

   ```bash
   rm -i --recursive ./carpeta
   ```

   ```bash
   rm -r --interactive ./carpeta
   ```

   ```bash
   rm --interactive -r ./carpeta
   ```
