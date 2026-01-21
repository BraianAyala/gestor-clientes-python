# Gestor de Clientes en Python

Aplicación de escritorio desarrollada en Python para la gestión de clientes, que permite realizar altas, bajas, modificaciones y consultas, utilizando persistencia de datos en archivos CSV.

El proyecto fue realizado como trabajo final de un curso de Python, con el objetivo de aplicar conceptos fundamentales del lenguaje y buenas prácticas de organización del código.

---

## 🧩 Funcionalidades

- Alta, baja y modificación de clientes
- Listado de clientes en interfaz gráfica
- Validaciones de datos (DNI, nombre y apellido)
- Persistencia de información mediante archivos CSV
- Interfaz gráfica desarrollada con Tkinter
- Opción de ejecución en modo consola o modo gráfico

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Tkinter (interfaz gráfica)
- CSV (persistencia de datos)
- Programación orientada a objetos
- Validaciones y manejo de eventos

---


## ▶️ Ejecución del proyecto

Clonar el repositorio:

```bash
git clone https://github.com/BraianAyala/gestor-clientes-python.git
cd gestor-clientes-python

# Ejecutar interfaz gráfica
python run.py

# Ejecutar en modo consola
python run.py -t


#📁 Estructura del proyecto
gestor-clientes-python/
│
├── run.py              # Punto de entrada del programa
├── ui.py               # Interfaz gráfica (Tkinter)
├── menu.py             # Menú en modo consola
├── database.py         # Lógica y persistencia de datos
├── helpers.py          # Funciones auxiliares
├── config.py           # Configuración del proyecto
├── clientes.csv        # Archivo de datos
├── requirements.txt
└── README.md
