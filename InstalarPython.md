# 1. Creación de Entornos Python

### **Paso 1: Verificar la Instalación de Python**

Antes que nada, verifica si tienes Python instalado en tu sistema ejecutando el siguiente comando:
```bash
python --version
```
En caso de no tenerlo lo instalaremos desde este enlace [Python](https://www.python.org/downloads/).

![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/51938c6f-0abb-4390-9de6-6c057df78687)

   
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/9423a87e-1ca8-42c8-922a-6e92710b62be)

### Paso 2: Crear una Carpeta de Entorno
   Dirígete a la ubicación en la que desees crear tu entorno de Python.

![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/a908ff90-67f8-4bc8-97b6-deb10d13c5ad)

### Paso 3: Crear el Primer Entorno

En la carpeta de tu elección, crea el primer entorno de Python utilizando el siguiente comando: 
```bash
python -m venv entorno1
```
   
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/9181c750-37d0-432b-810f-bf79f20033a3)

### Paso 4: Activar el Entorno

Ahora que tienes el entorno creado, actívalo ejecutando:

```bash
envtorno1\Scripts\activate
```
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/b5c718b8-e1bb-4387-9042-787bce2a439c)

![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/16f4e5ca-b1db-4b0a-ab87-8b509a9f6b3e)

![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/e59d652d-cd55-4bb0-a3d1-851c53ba9127)

### Paso 5: Listar los Paquetes Instalados

```bash
pip list
```
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/003c3e84-c60a-417e-b250-4b8031c57397)

### Paso 6: Desactivar el Entorno
Para salir del entorno, simplemente ejecuta:
```bash
deactivate
```
    
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/e97a71b2-269e-4ab4-a8a2-1cf1c83f4f7e)

### Paso 7: Crear el Segundo Entorno
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/8d684cea-ad09-4194-8b6e-f520ab44e2f2)

### Paso 8: Instalar un Paquete en el Entorno
Para instalar un paquete en un entorno específico, primero actívalo como se explicó en el Paso 6. 
Luego, utiliza el siguiente comando para instalar el paquete deseado:
```bash
pip install nombre_paquete
```
![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/2c895dc2-cf79-4ca2-86e4-cb882bc413a6)

### Paso 9: Verificar los Paquetes Instalados

![image](https://github.com/Danielforondapastor/sistemas-expertos/assets/95243114/f6068c2b-f983-4bf8-83b0-9f48e29dbaab)



# 2. Instala Anaconda en tu PC

### Paso 1: Descargar e Instalar Anaconda[https://www.anaconda.com/download]

![image](https://github.com/Danielforondapastor/IABD/assets/95243114/8239687f-c41f-424e-b9b5-5224dbe2a374)

### Paso 2: Crear Notebook de Jupyter
Debemos abrir el prompt de Anaconda introducimos en directorio que queramos y introducir en siguiente comando:
```bash
jupyter notebook
```
![image](https://github.com/Danielforondapastor/IABD/assets/95243114/9b91b1f5-952e-4e5c-8e75-46a7c525ce61)

![image](https://github.com/Danielforondapastor/IABD/assets/95243114/4ebaf743-9d6c-495d-af9c-7e2b98d6d2db)


### Paso 3: Crear un nuevo Notebook
Haz clic en el botón "New" en la esquina superior derecha.
Selecciona "Python" para crear un nuevo notebook de Python.

![image](https://github.com/Danielforondapastor/IABD/assets/95243114/42aa6467-7339-45e3-80e8-3f7913989fc5)

Una vez creado ya podremos introducir codigo y cambiar el titulo.

![image](https://github.com/Danielforondapastor/IABD/assets/95243114/f472885d-e283-41c6-b79f-b5d1e5c1a460)



# 3. Diferencias entre Enviroment, Anaconda y Colab

### Entorno
Un entorno de desarrollo se refiere a la configuración de software y hardware en la que se ejecuta un programa.

##### Pros:
- Flexibilidad completa para personalizar el entorno según las necesidades.
- Puede funcionar en cualquier sistema operativo.
- Control total sobre las versiones de bibliotecas y paquetes.
##### Contras:
- Requiere tiempo y esfuerzo para configurar y mantener.
- Puede ser complicado para principiantes.
- No ofrece recursos de cómputo escalables.

### Anaconda
Anaconda es una plataforma de código abierto que se especializa en la gestión de entornos de Python y R para la ciencia de datos y el análisis.
##### Pros:
- Facilita la gestión de entornos virtuales y paquetes con conda.
- Viene con un amplio conjunto de bibliotecas preinstaladas para ciencia de datos.
- Es compatible con múltiples sistemas operativos.
##### Contras:
- Ocupa más espacio en disco que un entorno personalizado.
- Puede ser abrumador para usuarios novatos debido a la cantidad de herramientas incluidas.

### Google Colab
Google Colab es un entorno de desarrollo en la nube gratuito basado en Jupyter Notebook que permite ejecutar código de Python en servidores de Google.

##### Pros:
- Acceso a recursos de cómputo poderosos sin la necesidad de hardware costoso.
- Integración con Google Drive para almacenar y compartir proyectos.
- Ideal para la colaboración en línea.
##### Contras:
- Requiere conexión a internet para su uso.
- La disponibilidad de recursos puede ser variable dependiendo de la demanda.
- Limitaciones en el tiempo de ejecución y acceso a GPU gratuitos.

#### Eleccion

- Si necesitas un control total y tienes experiencia en configurar entornos, usar tu propio entorno puede ser la mejor opción.
- Si buscas una forma fácil de gestionar paquetes y entornos en tu máquina local, Anaconda es una elección sólida.
- Si buscas recursos de cómputo poderosos y no te importa trabajar en la nube, Colab es una excelente opción, especialmente para proyectos colaborativos y educativos.
