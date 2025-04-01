# registro-estudiantes-python-1.0
# 🎓 Gestor de Estudiantes ITSQMET

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green?logo=tkinter)
![SQLite](https://img.shields.io/badge/Database-SQLite-red?logo=sqlite)
![Pandas](https://img.shields.io/badge/Export-Pandas-yellow?logo=pandas)

Aplicación CRUD para gestionar registros de estudiantes del ITSQMET, con interfaz gráfica (Tkinter), base de datos SQLite y exportación a CSV/Excel.

## 📦 Características
- **Registro completo**: Nombre, CI, celular, email, ubicación y carrera.
- **Operaciones CRUD**: Crear, Leer, Actualizar y Eliminar estudiantes.
- **Búsqueda rápida**: Filtra estudiantes por cédula (CI).
- **Exportación**: Genera reportes en Excel, CSV, PDF.
- **Interfaz intuitiva**: Diseño responsive con Tkinter.

## 🛠️ Tecnologías
| Herramienta   | Función                              |
|---------------|--------------------------------------|
| Python 3.x    | Lenguaje principal                  |
| Tkinter       | Interfaz gráfica                    |
| SQLite        | Base de datos local                 |
| Pandas        | Exportación a Excel/CSV             |

## 🚀 Instalación
1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/itsqmet-gestor-estudiantes.git
   cd itsqmet-gestor-estudiantes


# Registro-Estudiantes-1.0 - Instrucciones de uso

## 📦 Descargar la versión ejecutable
1. Ve a la sección [Releases](https://github.com/tuusuario/ProyectoFinal3.0/releases).
2. Descarga el archivo `Registro-Estudiantes-v1.0.zip`.

## 🚀 Cómo ejecutar el programa
1. **Extrae el ZIP** en una carpeta de tu elección.
2. **Asegúrate de tener**:
   - Windows 10/11 (o Windows 7/8 con [Visual C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe) instalado).
   - El archivo `itsqmet.db` en la misma carpeta que `main.exe`.
3. **Ejecuta** `main.exe` (haz clic derecho → "Ejecutar como administrador" si hay errores de permisos).

## ⚠️ Solución de problemas
- **Si tu antivirus bloquea el .exe**: Añade la carpeta a exclusiones.
- **Error de DLL faltante**: Instala [Visual C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe).
- **Base de datos no encontrada**: Verifica que `itsqmet.db` esté junto al ejecutable.

## 📝 Requisitos
- Sistema operativo: Windows 7/10/11 (64 bits recomendado).
- Espacio en disco: ~50 MB (incluyendo la base de datos).

---

> ✨ **Nota**: Este proyecto usa Python + SQLite3. [Ver código fuente](main.py).
