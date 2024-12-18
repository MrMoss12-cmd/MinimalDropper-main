# Dropper Minimal (Python)

## Descripción

Este es un ejemplo educativo de un *dropper* minimalista en Python, diseñado con fines educativos en el campo de la ciberseguridad. El programa recibe un payload de una API, lo descarga y ejecuta el código de forma remota en la máquina objetivo.

Este dropper utiliza **ngrok** para exponer la API local a través de un túnel seguro, permitiendo que el servidor reciba las solicitudes externas de manera efectiva.

**Advertencia: Este código está destinado únicamente a fines educativos. El uso indebido de este software está estrictamente prohibido y puede ser ilegal. Asegúrese de tener el consentimiento explícito para realizar pruebas de seguridad.**

## Requisitos

- Python 3.6 o superior
- ngrok (para exponer la API)
- Librerías de Python:
  - `requests`
  - `subprocess`
  - `os`
  - `platform`
  - `time`

Puedes instalar las dependencias de Python con el siguiente comando:

```bash
pip install requests
