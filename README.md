# GA1-220501092-AA1-EV01. Informe de despliegue de servidores
## Afiliación
- **Institución:** SENA, Centro de Electricidad, Electrónica y Telecomunicaciones - Regional Distrito Capital
- **Presentado por:** José Roberto Pérez Cano et al. , 2026
- **Programa de formación:** Tecnólogo en Gestión e Implementación de Bases de Datos
- **Ficha:** 3466363
## Instrucciones de Uso
### Opción 1 Web (Overleaf)
Esta opción no requiere descarga de programas pero para documentos muy largos puede presentar limitaciones en la versión gratuita

[Ir al sitio Oficial de Overleaf](https://es.overleaf.com/)
#### 1. Registrarse en la plataforma
![Inicio de overleaf](/images/overleaf_home.png)
#### 2. Crear proyecto nuevo (Blank project)
![Proyectos de overleaf](/images/overleaf_projects.png)
#### 3. Renderización de documento
Al crear un proyecto nuevo se genera automáticamente código de ejemplo, seleccionar todo ese contenido y pegar el código del fichero con extensión `.tex`, en la barra superior en "File/Settings/Compiler elegir opción de XeLateX \
![Overleaf bar](/images/overleaf_bar.png)
Barra Superior de Overleaf
![Overleaf settings](/images/overleaf_settings.png)
Sección de Settings
![Overleaf document](/images/overleaf_document.png)
Ya con el contenido reemplazado y el compilador correcto oprimir "Recompile"

### Opción 2 Local (Editor de LaTeX)
Se recomienda esta opción si se quiere total control y menores limitaciones a Overleaf
#### 1. Instalar motor LaTeX (MiKTeX)
[Ir al sitio Oficial de MiKTeX](https://miktex.org/download)

#### 2. Instalar Editor TeX (TeXstudio)
[Ir al sitio oficial de TeXstudio](https://www.texstudio.org/)

#### 3. Clonar Repositorio
```bash
git clone https://github.com/jota2209/GA2-220501106-AA2-EV03.git
```
#### 4. Abrir fichero .tex
Estando en Texstudio en la barra superior "Archivo/Abrir..." seleccionar la ruta donde se descargó el contenido del repositorio y abrir el fichero `.tex` correspondiente, en la misma barra superior en "Opciones/Configurar TeXstudio.../Compilar" cambiar el compilador por defecto a XeLaTeX y oprimir "Aceptar"

![textstudio bar](/images/texstudio_bar.png) Barra Superior de TeXstudio
![textstudio settings](/images/texstudio_settings.png) Barra de opciones TeXstudio \
Finalmente con el botón ![textstudio botón compilar y ver](/images/texstudio_buttoncv.png) (Compilar & Ver) se puede visualizar el documento y además renderizar y producir pdf.