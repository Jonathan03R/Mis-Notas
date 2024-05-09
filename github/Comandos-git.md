# Guía Rápida de Git

¡Bienvenido a la Guía Rápida de Git! Esta guía te ayudará a comenzar a usar Git para administrar tus proyectos de manera eficiente.

## Comandos Básicos

1. Inicializa un nuevo repositorio de Git en tu proyecto:

    ```bash
    git init
2. Clona un repositorio existente en tu máquina:

    ```bash
    git clone URL_DEL_REPOSITORIO
3. Agrega cambios al área de preparación para ser confirmados:

    ```bash
    git add
4. uarda los cambios confirmados en el repositorio:

    ```bash
    git commit -m "Mensaje del commit"
5. Muestra el estado actual de los archivos en tu repositorio:

    ```bash
    git status
6. Lista las ramas en tu repositorio y muestra la rama actual:

    ```bash
    git branch
7. Combina los cambios de una rama con otra:

    ```bash
    git merge NOMBRE_DE_LA_RAMA
8. Actualiza tu repositorio local con los cambios del repositorio remoto:

    ```bash
    git pull
9. Envía tus cambios locales al repositorio remoto:

    ```bash
    git push



# Consejos Importantes
- Siempre escribe mensajes de commit descriptivos para que otros puedan entender tus cambios.
- Antes de confirmar, verifica qué cambios has realizado utilizando git status.
- Usa ramas para trabajar en nuevas características o solucionar problemas sin afectar la rama principal.
- Actualiza tu repositorio local con git pull antes de enviar cambios con git push para evitar conflictos.
