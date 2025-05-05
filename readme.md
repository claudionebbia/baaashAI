# BaaashAI

BaaashAI es un script en Bash que utiliza modelos de Ollama para traducir peticiones de texto en comandos de Bash. Este proyecto está diseñado para facilitar la ejecución de tareas comunes en la terminal mediante el uso de inteligencia artificial.

## Características

- Verifica si Ollama está instalado y ofrece instalarlo automáticamente si no lo está.
- Permite configurar el modelo (default) de Ollama a utilizar mediante una variable de entorno (`$BAAASH_MODEL`).
- Traduce peticiones de texto en comandos de Bash utilizando el modelo configurado, (Llama3.2 da muy buenos resultados incluso en TERMUX!)
- Muestra el comando para ser revisado y ejecutarlo de ser correcto.

## Instalación

Puedes clonar este repositorio desde GitHub y comenzar a usar BaaashAI:

```bash
git clone https://github.com/claudionebbia/baaashAI.git
cd baaashAI
chmod +x baaash
./baaash -help
./baaash "Agrega ./baaash al $PATH"
