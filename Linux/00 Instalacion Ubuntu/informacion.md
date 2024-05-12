<!-- Autor: Daniel Benjamin Perez Morales -->
<!-- GitHub: https://github.com/DanielPerezMoralesDev13 -->
<!-- Correo electrónico: danielperezdev@proton.me  -->
# ***Instalacion de Ubuntu***

- [***Instalacion de Ubuntu***](#instalacion-de-ubuntu)
- [***VirtualBox***](#virtualbox)
- [***Instalar Ubuntu***](#instalar-ubuntu)
- [***Instalacion en Maquina Virtual***](#instalacion-en-maquina-virtual)
- [***Designaciones de Disco en Linux***](#designaciones-de-disco-en-linux)
- [***Instalacion del sistema operativo en Hardware***](#instalacion-del-sistema-operativo-en-hardware)
- [**Si tenemos problema al particionar el disco se puede deber a muchas razones**](#si-tenemos-problema-al-particionar-el-disco-se-puede-deber-a-muchas-razones)

---

# ***VirtualBox***

> *Una máquina virtual (VM, por sus siglas en inglés) es un entorno virtualizado que emula un sistema informático físico y permite ejecutar sistemas operativos y aplicaciones como si estuvieran instalados en hardware físico. Esto es útil para probar software, realizar pruebas de seguridad, ejecutar sistemas operativos múltiples en un mismo hardware, entre otros usos.*

- **Para instalar VirtualBox**

  - *Instalar desde su pagina oficial*

    - [***VirtualBox***](https://www.virtualbox.org/ "https://www.virtualbox.org/")

  - *Actualizar el sistema*

      ```bash
      sudo apt-get install update
      ```

     ```bash
      sudo apt-get install upgrade
     ```

  - *Instalar VirtualBox*

     ```bash
      sudo apt-get install virtualbox
      ```

     ```bash
      vboxmanage --version
      ```

# ***Instalar Ubuntu***

> *Ubuntu es un sistema operativo de código abierto basado en el kernel de Linux. Es conocido por su enfoque en la facilidad de uso, la estabilidad y la seguridad. Ubuntu se distribuye gratuitamente y está respaldado por una comunidad activa de desarrolladores y usuarios.*

1. **Versiones principales**

   1. **Ubuntu Desktop:**

      1. > *La versión de escritorio estándar, diseñada para usuarios de computadoras personales.*

   2. **Xubuntu:**

      1. *Utiliza el entorno de escritorio Xfce, siendo una opción más ligera y eficiente para sistemas con recursos limitados.*

   3. **Lubuntu:**

      1. > *Ofrece un entorno de escritorio LXQt, diseñado para ser liviano y adecuado para hardware más antiguo o menos potente.*

   4. Ubuntu Cloud:

      1. > *Orientado a la implementación y gestión de servicios en la nube, utiliza herramientas como OpenStack.*

   5. Ubuntu IoT:
      1. > *Diseñado para dispositivos de Internet de las cosas (IoT), proporciona un entorno de desarrollo para aplicaciones IoT.*

2. **Empresa detrás**

   1. > *Canonical Ltd. es la empresa que respalda y desarrolla Ubuntu. Fue fundada por Mark Shuttleworth y tiene como objetivo promover el uso de software de código abierto.*

3. **Características principales**

   1. **Entorno de escritorio:**

      - *Utiliza el entorno de escritorio GNOME por defecto en la versión estándar, pero ofrece variantes con otros entornos más ligeros.*

   2. **Ciclo de lanzamiento:**

      1. *Ubuntu sigue un ciclo de lanzamiento regular con versiones de soporte a largo plazo (LTS-Long Term Support) y versiones regulares.*

   3. **Centro de Software:**

      1. *Proporciona un fácil acceso a la instalación y gestión de aplicaciones.*

   4. **Seguridad:**
      1. *Ubuntu se enorgullece de su seguridad y ofrece actualizaciones regulares para mantener el sistema protegido.*

---

# ***Instalacion en Maquina Virtual***

1. *Ejecutamos el siguiente comando para abrir virtualbox*

     ```bash
      virtualbox
      ```

      1. ![*virtualbox #1*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox1.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox1.png?raw=true")

      2. ![*virtualbox #2*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox2.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox2.png?raw=true")

      3. ![*virtualbox #3*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox3.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox3.png?raw=true")

      4. ![*virtualbox #4*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox4.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox4.png?raw=true")

      5. ![*virtualbox #5*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox5.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox5.png?raw=true")

      6. ![*virtualbox #6*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox6.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox6.png?raw=true")

      7. ![*virtualbox #7*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox7.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox7.png?raw=true")

      8. ![*virtualbox #8*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox8.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox8.png?raw=true")

      9. ![*virtualbox #9*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox9.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox9.png?raw=true")

      10. ![*virtualbox #10*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox10.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox10.png?raw=true")

      11. ![*virtualbox #11*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox11.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox11.png?raw=true")

      12. ![*virtualbox #12*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox12.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox12.png?raw=true")

      13. ![*virtualbox #13*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox13.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox13.png?raw=true")

      14. ![*virtualbox #14*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox14.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox14.png?raw=true")

      15. ![*virtualbox #15*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox15.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox15.png?raw=true")

      16. ![*virtualbox #16*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox16.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox16.png?raw=true")

      17. ![*virtualbox #17*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox17.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox17.png?raw=true")

      18. ![*virtualbox #18*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox18.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox18.png?raw=true")

      19. ![*virtualbox #19*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox19.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox19.png?raw=true")

      20. ![*virtualbox #20*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox20.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox20.png?raw=true")

      21. ![*virtualbox #21*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox21.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox21.png?raw=true")

      22. ![*virtualbox #22*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox22.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox22.png?raw=true")

      23. ![*virtualbox #23*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox23.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox23.png?raw=true")

      24. ![*virtualbox #24*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox24.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox24.png?raw=true")

      25. ![*virtualbox #25*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox25.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox25.png?raw=true")

      26. ![*virtualbox #26*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox26.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox26.png?raw=true")

      27. ![*virtualbox #27*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox27.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox27.png?raw=true")

      28. ![*virtualbox #28*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox28.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox28.png?raw=true")

      29. ![*virtualbox #29*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox29.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox29.png?raw=true")

      30. ![*virtualbox #30*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox30.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox30.png?raw=true")

      31. ![*virtualbox #31*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox31.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox31.png?raw=true")

      32. ![*virtualbox #32*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox32.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox32.png?raw=true")

      33. ![*virtualbox #33*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox33.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox33.png?raw=true")

      34. ![*virtualbox #34*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox34.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox34.png?raw=true")

      35. ![*virtualbox #35*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox35.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox35.png?raw=true")

      36. ![*virtualbox #36*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox36.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox36.png?raw=true")

      37. ![*virtualbox #37*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox37.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox37.png?raw=true")

      38. ![*virtualbox #38*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox38.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox38.png?raw=true")

      39. ![*virtualbox #39*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox39.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox39.png?raw=true")

      40. ![*virtualbox #40*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox40.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox40.png?raw=true")

      41. ![*virtualbox #41*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox41.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox41.png?raw=true")

      42. ![*virtualbox #42*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox42.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox42.png?raw=true")

      43. ![*virtualbox #43*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox43.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox43.png?raw=true")

      44. ![*virtualbox #44*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox44.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox44.png?raw=true")

      45. ![*virtualbox #45*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox45.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox45.png?raw=true")

      46. ![*virtualbox #46*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox46.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox46.png?raw=true")

      47. ![*virtualbox #47*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox47.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox47.png?raw=true")

      48. ![*virtualbox #48*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox48.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox48.png?raw=true")

      49. ![*virtualbox #49*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox49.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox49.png?raw=true")

      50. ![*virtualbox #50*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox50.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox50.png?raw=true")

      51. ![*virtualbox #51*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox51.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox51.png?raw=true")

      52. ![*virtualbox #52*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox52.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox52.png?raw=true")

> *Las particiones son divisiones lógicas en el disco duro de tu computadora que permiten organizar y gestionar el espacio de almacenamiento. Estas divisiones son esenciales por varias razones:*

1. **Gestión del sistema de archivos:**

   1. > *Las particiones ayudan a organizar y gestionar el sistema de archivos del sistema operativo. Cada partición puede tener su propio sistema de archivos y configuración.*

2. **Aislamiento de datos:**

   1. > *Si una partición falla, las demás pueden seguir funcionando. Esto significa que, por ejemplo, si tienes tus archivos personales en una partición separada, es menos probable que se vean afectados en caso de problemas en otras áreas del sistema.*

3. **Múltiples sistemas operativos:**

   1. > *Si deseas tener varios sistemas operativos en una misma máquina, necesitarás particiones separadas para cada uno.*

4. **Mejora del rendimiento:**

   1. > *Al separar áreas del disco, es posible mejorar el rendimiento de ciertos aspectos del sistema, como la velocidad de acceso a datos.*

> **Un disco puede tener 4 Particiones Primarias es decir un disco puede almacenar 5 sistemas operativos y los discos puede tener varias particiones logicas**

1. **(raíz):**

   1. > *Contiene los archivos del sistema y directorios principales. Es la partición principal.*

2. **boot:**

   1. > *Almacena los archivos del kernel y otros archivos de inicio del sistema.*

3. **home:**

   1. > *Contiene los directorios personales de los usuarios, incluyendo documentos, música, imágenes, etc.*

4. **swap:**

   1. > *Esta es la partición de intercambio y se utiliza como espacio adicional cuando la memoria RAM está llena. Puede mejorar el rendimiento del sistema en situaciones de baja memoria.*

5. **tmp:**

   1. > *Almacena archivos temporales.*

6. **var:**

   1. > *Contiene datos variables, como registros del sistema y archivos de spool.*

7. **usr:**

   1. > *Almacena programas y archivos de sistema que no cambian con frecuencia.*

8. **opt:**
   1. > *Utilizado para instalar software adicional de terceros.*

> En general, se recomienda crear tres particiones al instalar un sistema operativo, siguiendo una estructura que incluya una partición primaria para el sistema operativo y dos particiones lógicas. Estas dos particiones lógicas suelen ser /Swap y /Home. Veamos el propósito de cada una:

**Partición primaria para el sistema operativo (/):**

1. *Esta partición es donde se instala el sistema operativo. Contiene los archivos del sistema, el kernel y otros componentes esenciales para el funcionamiento del sistema.*

2. *Mantener el sistema operativo en una partición separada facilita la gestión y las actualizaciones sin afectar los datos personales.*

**Partición lógica de intercambio (/Swap):**

1. *La partición de intercambio (Swap) actúa como un espacio adicional cuando la memoria RAM está llena. Permite que el sistema operativo transfiera datos temporales al disco duro para evitar problemas de falta de memoria.*

2. *Mejora el rendimiento del sistema en situaciones de uso intensivo de memoria.*

**Partición lógica para archivos personales (/Home):**

1. *La partición /Home almacena los directorios personales de los usuarios, que incluyen documentos, música, imágenes y configuraciones personales.*

2. *Al tener /Home en una partición separada, los archivos personales están aislados del sistema operativo. Esto significa que si decides reinstalar o actualizar el sistema operativo, los archivos personales permanecerán intactos, facilitando la migración y la protección de tus datos.*

---

# ***Designaciones de Disco en Linux***

> *En sistemas operativos basados en Linux, los discos duros y otros dispositivos de almacenamiento son representados en el sistema de archivos como archivos en el directorio `/dev`. La designación de disco base suele seguir el patrón `/dev/sda`, donde "sda" podría ser reemplazado por otras letras según la cantidad de discos presentes en el sistema (por ejemplo, `/dev/sdb`, `/dev/sdc`, etc.).*

1. **Particiones Primarias y Lógicas**

   *Cuando se crean particiones en un disco, las designaciones de disco cambian para reflejar estas divisiones. A continuación, se describen las convenciones comunes:*

   - **Disco Completo:** *`/dev/sda` representa todo el disco.*

   - **Particiones Primarias:** *Las particiones primarias se numeran secuencialmente, por ejemplo, `/dev/sda1`, `/dev/sda2`, `/dev/sda3`, etc. Cada número indica una partición primaria diferente en el mismo disco.*

   - **Particiones Lógicas:** *Cuando se utilizan particiones lógicas (generalmente dentro de una partición extendida), las designaciones cambian a `/dev/sda5`, `/dev/sda6`, `/dev/sda7`, etc. La numeración comienza desde 5 para indicar particiones lógicas.*

2. **Diferencia entre Particiones Primarias y Lógicas**

   *La principal diferencia entre particiones primarias y lógicas radica en cómo se utilizan y cómo interactúan con la tabla de particiones:*

   - **Particiones Primarias:** *Están limitadas a un máximo de cuatro por disco. Son independientes y pueden contener sistemas de archivos o actuar como contenedores para sistemas de archivos adicionales (por ejemplo, contenedor de una partición extendida).*

   - **Particiones Lógicas:** *Se utilizan cuando se necesitan más de cuatro particiones en un disco. Se crean dentro de una partición extendida, que es una partición primaria especial. La partición extendida actúa como un contenedor para varias particiones lógicas. Esto permite superar la limitación de cuatro particiones primarias.*

3. **Ejemplo Práctico**

   *Supongamos que tenemos un disco `/dev/sda` con tres particiones primarias y una partición extendida con dos particiones lógicas:*

   `/dev/sda1` - *Partición Primaria*
   `/ev/sda2` - *Partición Primaria*
   `/ev/sda3` - *Partición Primaria*
   `/ev/sda4` - *Partición Extendida*
      /dev/sda5` - _Partición Lógica_
      `/ev/sda6` - *Partición Lógica*

   *n este ejemplo, `/dev/sda1`, `/dev/sda2`, y `/dev/sda3` son particiones primarias, mientras que `/dev/sda5` y `/dev/sda6` son particiones lógicas dentro de la partición extendida `/dev/sda4`.*

4. **Guest Additions en VirtualBox**

**¿Qué son las Guest Additions?**

> *Las Guest Additions son controladores y utilidades que mejoran la integración y el rendimiento de una máquina virtual en VirtualBox.*

**Funcionalidades Comunes de Guest Additions:**

- **Mejora de Resolución de Pantalla:** *Ajusta automáticamente la resolución de pantalla de la máquina virtual.*
- **Integración del Ratón:** *Permite una transición más fluida entre el sistema anfitrión y el sistema invitado.*
- **Compartición de Carpetas:** *Facilita la transferencia de archivos entre ambos sistemas.*

**Instalación de Guest Additions:**

1. **Iniciar la Máquina Virtual:** *Asegúrate de que tu máquina virtual esté en ejecución.*

2. **Insertar el CD de Guest Additions:**

   - *Desde el menú de VirtualBox, selecciona "Dispositivos" -> "Insertar imagen de CD de Guest Additions..."*
   - ![*virtualbox #53*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox53.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox53.png?raw=true")

3. **Acceder al Terminal en el Sistema Invitado:**

   - *En la máquina virtual, abre la terminal.*

   - Es posible que necesites tener instalados los "build-essential" y los "linux-headers" antes de ejecutar el script de instalación.

      ```bash
      sudo apt-get install build-essential linux-headers-$(uname -r)
     ```

   - ![*virtualbox #58*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox58.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox58.png?raw=true")

4. **Ejecutar el script de instalacion:**

   1. *Ir al directorio y ejecutarlo*

      1. ![*virtualbox #54*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox54.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox54.png?raw=true")

         ```bash
          cd /media/daniel/VBox_Gas_6.1.38
          ```

      2. *Remplazar daniel por tu usuario y VBox_Gas_6.1.38 con el directorio que te aparece*

         ```bash
         ls
         ```

         1. ![*virtualbox #55*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox55.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox55.png?raw=true")

         2. *Actualizamos el sistema*

              ```bash
              sudo apt-get install update
              ```

         3. *Terminamos de actualizar el sistema*

              ```bash
               sudo apt-get install upgrade
               ```

      3. ![*virtualbox #56*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox56.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox56.png?raw=true")

      4. ![*virtualbox #57*](https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox57.png?raw=true "https://github.com/DanielPerezMoralesDev13/Linux-Debian/blob/master/Linux/Images/PNG/Img_Virtualbox/virtualbox57.png?raw=true")

5. **Reiniciar la Máquina Virtual:**

      ```bash
      sudo reboot
      ```

6. *Desde el menú de VirtualBox, selecciona "Dispositivos" -> "Papeles compartidos...", Seleccionar Bidireccional*

7. *Desde el menú de VirtualBox, selecciona "Dispositivos" -> "Arrastrar y soltar...", Seleccionar Bidireccional*

8. **Estos comandos y pasos son específicos para sistemas basados en Debian o Ubuntu. Si estás utilizando una distribución diferente, es posible que necesites adaptar los comandos según los requisitos del sistema operativo invitado.**

---

# ***Instalacion del sistema operativo en Hardware***

***Recomendacion al hacer las particiones para intalar el sistema operativo en hardware***

**Un solo SSD o HDD:**

> *Solo hay que particionar el disco dejando el espacio que puedas, mi recomendación es mitad para Windows mitad para Linux, aunque si tienes un HDD con mucho espacio puedes dejar 200-300 GB para Linux y el resto para Windows si lo usas para juegos o similar.*

**SSD + HDD:**

> *Tienes que particionar el SSD para instalar ahí el sistema operativo, y tienes que particionar el HDD para montar ahí el /home y almacenar tus archivos. En cuando al SSD recomiendo si es posible mitad para Windows mitad para Linux. El HDD va a tu criterio, deja el espacio que consideres necesario.*

**Un solo disco en el PC (SSD o HDD) pero con disco externo para archivos:**

> *Se tiene que particionar el disco que tienes en el PC, ya sea SSD o HDD, debes hacer espacio para instalar el Sistema, tus archivos los almacenas en el disco externo.*

[Etcher](https://etcher.balena.io/ "https://etcher.balena.io/")

> *Balena Etcher es una herramienta de código abierto que se utiliza para escribir imágenes de sistemas operativos en tarjetas SD, unidades flash USB u otros dispositivos de almacenamiento masivo. Su principal función es facilitar la creación de medios de arranque para sistemas operativos, especialmente en el contexto de sistemas basados en Linux y otras plataformas embebidas.*

**Algunas características clave de Balena Etcher incluyen:**

1. **Interfaz Gráfica de Usuario (GUI):** *Balena Etcher ofrece una interfaz gráfica intuitiva y fácil de usar que simplifica el proceso de escritura de imágenes en dispositivos de almacenamiento.*

2. **Multiplataforma:** *Está disponible para sistemas operativos Windows, macOS y Linux, lo que permite a los usuarios de diferentes plataformas utilizar la herramienta de manera consistente.*

3. **Soporte para Formatos** *de Imagen Comunes: Puede escribir imágenes en varios formatos comunes, como ISO, IMG y ZIP, lo que facilita la creación de medios de instalación para sistemas operativos.*

> **Modo de uso**

1. *Necesitaremos una **USB** de almenos 8 GB para arrancar el ordenador desde la **USB***

   1. *Se recomienda que la **USB** este vacia*

2. *Ejecutar el programa*
   1. *Te pedira que seleccione la iso del sistema operativo*
   2. \*Segunda cosa que te pedira es la unidad extraible osea el **USB\***
   3. *De ultimo simplemente lo finalizaremos*
   4. *Y ya con esa **USB** podremos instalar Linux en cualquier ordenador*

> **Primeramente hay que crear las particiones desde windows por que en la maquina virtual no habia ningun sistema operativo instalado**

**Buscar en la barra de busqueda en windows** *Crear y formatear particiones del disco o administracion de discos*

1. *Seleccionar el disco que queremos particionar y luego darle reducir volumen*

2. *Tendremos un limite de espacio para particionar el disco windows no los dira*

3. *Poner la cantidad de espacio que queremos particionar siempre y cuando no sobre pase el limite establecido por windows y listo*

4. *Luego tenemos que configurar la BIOS para arrancar el ordenador desde la USB*

> *La BIOS, que significa "Basic Input/Output System" (Sistema Básico de Entrada/Salida), es un software esencial almacenado en un chip de memoria flash en la placa base de una computadora. La BIOS es fundamental para el inicio y la operación básica del sistema antes de que el sistema operativo se cargue desde el disco duro o cualquier otro dispositivo de almacenamiento.*

1. *Para entrar ala bios hay muchas formas. Mantener presionada la tecla <kbd>Shift</kbd> y reiniciar el sistema operativo en windows. O apagar el ordenador y presionar las teclas especiales como <kbd>f11</kbd>,<kbd>f12</kbd> para abrir la bios*

2. *Cuando entremos ala Bios ir ala opcion modo avanzado y luego ir a **BOOT** y luego colocar la USB de primero para que arranque el sistema operativo desde el usb de primero*

---

# **Si tenemos problema al particionar el disco se puede deber a muchas razones**

1. [*Guía partition wizard*](https://www.partitionwizard.com/partitionmanager/cannot-shrink-volume-win10.html "https://www.partitionwizard.com/partitionmanager/cannot-shrink-volume-win10.html")
