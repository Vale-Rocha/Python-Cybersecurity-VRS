# Python-Cybersecurity-VRS
Hi! Vale Rocha's repository for career-related stuff, part 2 (Python for cybersecurity).

---

## PHASE II (Ej17)

1. **Use of the Have I Been Pwned? API**  
   This script checks whether any email address has been compromised using the [Have I Been Pwned?](https://haveibeenpwned.com/API/v3) API.

### ⚠️ IMPORTANT

To run the Python script correctly, you must include a text file named `apikey.txt` in the same directory. This file should contain your personal API key.

**Example content of `apikey.txt`: 1234567890abcdef1234567890abcdef

> 🔐 **Do not share your API key publicly.**  
> This key is private and should be kept secure to prevent unauthorized use.

---

##  Professional refactoring of the verification script (Ej19)

# 🔐 Verificador de Correos Comprometidos – Have I Been Pwned

Este script permite verificar si una cuenta de correo electrónico ha sido comprometida en brechas de seguridad conocidas, utilizando la API oficial de Have I Been Pwned.

## 📋 Requisitos

- Python 3.8 o superior  
- Clave API válida  
- Conexión a internet

## ⚙️ Instalación

```bash
pip install -r requirements.txt

```

## 🚀 Uso

Ejecuta el script desde la terminal, indicando el correo a verificar y opcionalmente el nombre del archivo CSV de salida:

```bash
python verificar_correo3.py correo@example.com -o salida.csv

```

## 📁 Archivos generados

- `reporte.csv`: contiene los detalles de hasta 3 brechas encontradas para el correo consultado.  
- `registro.log`: archivo de registro con información de cada consulta realizada y errores detectados.  
- `apikey.txt`: almacena localmente la API key ingresada por el usuario (**no debe subirse a GitHub**).  
- `requirements.txt`: generado automáticamente con las dependencias del proyecto.

> ⚠️ **Advertencia:** Protege tu archivo `apikey.txt`. No lo compartas ni lo subas a repositorios públicos.

## 🧱 Estructura del proyecto

```plaintext
verificar_correo3.py
apikey.txt
registro.log
reporte.csv
requirements.txt
README.md

```

## 👩‍💻 Créditos

Desarrollado por **Valeria R.S. (con Orientación de la Dra. Perla Marlene Viera González)**  
Materia: *Programación para Ciberseguridad*  
Grupo: *062*

## 📄 Licencia

Este proyecto se distribuye con fines educativos. El uso de la API de Have I Been Pwned está sujeto a sus [términos de servicio](https://haveibeenpwned.com/API/v3#AcceptableUse).

## 📬 Contacto

Para dudas técnicas o sugerencias, puedes dejar comentarios en el repositorio de GitHub.
