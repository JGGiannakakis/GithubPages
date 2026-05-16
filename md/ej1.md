#  Gestión de carpetas en Linux 

Crea un documento e incluye los resultados que te muestre el terminal en cada paso.

# Parte 1: Creación de carpetas

### Pasos previos

Crea una carpeta llamada **ejercicio 1**

### Ejercicio 1

Crea las siguientes carpetas dentro de ejercicio 1:

```bash
practica_linux
documentos
imagenes
```

Luego verifica que se han creado:

```bash
ls
```

### Ejercicio 2

Dentro de `practica_linux`, crea esta estructura:

    practica_linux/
     ├── proyectos/
     ├── notas/
     └── backups/

<div style="page-break-after: always;"></div>


# Parte 2: Ver permisos

### Ejercicio 3

Visualiza los permisos de todas las carpetas creadas:

```bash
ls -l
```

Responde a las siguientes preguntas:

*   ¿Qué permisos tiene cada carpeta?
*   ¿Quién es el propietario?

---

# Parte 3: Modificar permisos

### Ejercicio 4

Cambia los permisos de la carpeta `notas` para que:

*   El usuario tenga todos los permisos
*   El grupo pueda leer y ejecutar
*   Otros no tengan acceso


### Ejercicio 5

Haz que la carpeta `backups` tenga permisos completos para todos:


Responde a la siguiente pregunta:

*   ¿Es seguro que todo el mundo tenga acceso a la carpeta? ¿Por qué?


### Ejercicio 6

Quita el permiso de escritura a "otros" en la carpeta `documentos`:

---

# Parte 4: Permisos recursivos

### Ejercicio 7

Aplica permisos `755` a toda la carpeta `practica_linux` y su contenido:

Para aplicar permisos de forma recursiva incluye -R antes de dar los permisos

Ejemplo:

```bash
chmod -R 223 practica_linux
```

---

# Parte 5: Preguntas teóricas

Responde a las siguientes preguntas:

### Preguntas sobre permisos de carpetas

1.  ¿Para qué sirve el permiso **x** en una carpeta?
2.  ¿Qué diferencia hay entre `755` y `777`?
3.  ¿Qué significa `chmod 644 archivo`?
4.  ¿Qué pasaría si una carpeta tiene permiso `000`?

### Preguntas sobre sistemas operativos

5. ¿Qué es un sistema operativo?
    - a) Un programa para escribir documentos
    - b) Un conjunto de programas que gestionan el hardware y las aplicaciones
    - c) Un dispositivo físico del ordenador
    - d) Un tipo de archivo

6. ¿Cuál de estos recursos gestiona el sistema operativo?
    - a) Solo la pantalla
    - b) Solo el teclado
    - c) CPU, memoria y dispositivos de entrada/salida
    - d) Solo los programas

7. ¿Cuál es la función de la interfaz de usuario?
    - a) Gestionar archivos
    - b) Permitir que el usuario interactúe con el sistema
    - c) Controlar la CPU
    - d) Ejecutar procesos

8. ¿Qué componente gestiona los archivos?
    - a) Gestor de procesos
    - b) Sistema de archivos
    - c) Interfaz gráfica
    - d) BIOS

9. Un sistema multitarea:
    - a) Solo ejecuta un programa
    - b) Ejecuta varios programas a la vez
    - c) No ejecuta programas
    - d) Solo sirve para móviles

10. Un sistema multiusuario permite:
    - a) Solo un usuario
    - b) Dos usuarios
    - c) Varios usuarios trabajando
    - d) Ningún usuario

11. ¿Qué tipo de interfaz utiliza comandos en el terminal?
    - a) GUI
    - b) CLI
    - c) BIOS
    - d) Kernel

12. ¿Qué tipo de sistema usa ventanas, iconos y menús?
    - a) CLI
    - b) GUI
    - c) Texto plano
    - d) Consola

13. ¿Cuál de estos sistemas operativos es de código abierto?
    - a) Windows
    - b) macOS
    - c) Linux
    - d) iOS

14.  ¿Qué es una distribución Linux?
    - a) Un hardware
    - b) Una versión completa del sistema con herramientas y software
    - c) Un archivo
    - d) Un programa simple