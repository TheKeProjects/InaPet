# README - InaPet 🐾

![InaPet Banner](https://via.placeholder.com/1200x400/679aad/ffffff?text=InaPet+-+Tu+mascota+virtual+de+escritorio)

<div align="center">

[![Versión](https://img.shields.io/badge/Versión-1.0.2-success)](https://github.com/TheKeProjects/InaPet/releases/latest/download/InaPet_Setup.exe)
[![Plataforma](https://img.shields.io/badge/Plataforma-Windows-informational)](https://www.microsoft.com/windows)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-blue)](LICENSE)
[![Estado](https://img.shields.io/badge/Estado-Activo-brightgreen)](https://github.com/TheKeProjects/InaPet)

</div>

## ✨ Características Principales

InaPet es una mascota virtual de escritorio que te acompaña mientras trabajas, aportando diversión y compañía a tu espacio digital.

| Funcionalidad | Descripción |
| :--- | :--- |
| 🐾 **Mascota Animada** | Se mueve de forma autónoma por tu pantalla con movimiento natural y encantador |
| 🔄 **Actualizaciones Automáticas** | Verifica automáticamente nuevas versiones y actualiza con un solo clic |
| 🎨 **Personalización Completa** | Cambia la apariencia con diferentes skins y ajusta la velocidad |
| 🖱️ **Interactividad** | Arrastra a InaPet o haz doble clic para que abra archivos aleatorios |
| 🔔 **Soporte para Notificaciones** | Se minimiza a la bandeja del sistema y reaparece cuando la llamas |
| 🖥️ **Siempre Visible** | Siempre está encima de otras ventanas para no perderla de vista |

## 🚀 ¿Cómo empezar?

### Requisitos del sistema
- Windows 10 o superior
- 100 MB de espacio libre en disco
- Resolución de pantalla mínima: 1280x720

### Instalación

1. **Descarga el instalador**
   ```bash
   # Descarga la última versión desde GitHub Releases
   https://github.com/TheKeProjects/InaPet/releases/latest/download/InaPet_Setup.exe
   ```

2. **Ejecuta el instalador**
   - Haz doble clic en `InaPet_Setup.exe`
   - Sigue las instrucciones en pantalla
   - ¡InaPet se iniciará automáticamente!

3. **Personaliza tu experiencia**
   - Haz clic derecho en InaPet para acceder al menú de configuración
   - Selecciona tu skin favorita
   - Ajusta la velocidad de movimiento

## 🎮 Cómo usar InaPet

| Interacción | Resultado |
| :--- | :--- |
| **Clic derecho** | Abre el menú de configuración |
| **Arrastrar** | Mueve a InaPet por la pantalla |
| **Doble clic** | Abre archivos aleatorios de tus carpetas |
| **Minimizar** | Se oculta en la bandeja del sistema |

## 📦 Estructura del proyecto

```
InaPet/
├── assets/          # Recursos multimedia
├── src/             # Código fuente
│   ├── components/  # Componentes de la aplicación
│   ├── utils/       # Utilidades y helpers
│   └── main.py      # Punto de entrada
├── docs/            # Documentación
└── skins/           # Skins personalizadas
```

## 🛠️ Desarrollo

### Prerrequisitos
- Python 3.8+
- PyGame
- PyInstaller

### Compilación
```bash
# Clona el repositorio
git clone https://github.com/TheKeProjects/InaPet.git

# Navega al directorio
cd InaPet

# Instala dependencias
pip install -r requirements.txt

# Ejecuta en modo desarrollo
python src/main.py

# Compila para distribución
pyinstaller --onefile --windowed src/main.py
```

## 🤝 Contribuir

¡Las contribuciones son siempre bienvenidas! Por favor, lee las [guías de contribución](CONTRIBUTING.md) antes de enviar un pull request.

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 🐛 Reportar problemas

Si encuentras algún problema, por favor [crea un issue](https://github.com/TheKeProjects/InaPet/issues) en GitHub con la mayor información posible.

## 🌟 Versiones

| Versión | Características | Estado |
| :--- | :--- | :--- |
| 1.0.2 | Estabilidad mejorada y corrección de errores | ✅ Estable |
| 1.0.1 | Primer lanzamiento público | ✅ Estable |
| 0.9.0 | Versión beta con funciones básicas | 🚫 Obsoleta |

## 📞 Soporte

Si necesitas ayuda o tienes preguntas:
- Revisa la [documentación](docs/)
- Abre un [issue](https://github.com/TheKeProjects/InaPet/issues)
- Envía un correo a: soporte@inapet.com

## 🎨 Skins personalizadas

¿Quieres crear tu propia skin para InaPet? Consulta nuestra [guía de skins](docs/SKINS.md) para aprender cómo hacerlo.

---

<div align="center">

### ¿Te gusta InaPet?

¡Dale una ⭐ al repositorio si este proyecto te ha sido útil!

[![GitHub stars](https://img.shields.io/github/stars/TheKeProjects/InaPet?style=social)](https://github.com/TheKeProjects/InaPet/stargazers)

*Hecho con ❤️ para la comunidad de desarrolladores*

</div>
