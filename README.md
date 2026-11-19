# Edgar Gaytán — Data Analyst & IT Engineer

Portafolio profesional desarrollado con **Astro** y **Tailwind CSS v4**, enfocado en la presentación de proyectos de análisis de datos, pipelines de extracción automatizada y visualización estratégica.

> 🌐 **Sitio web en desarrollo:** Próximamente publicado en GitHub Pages.  
> ♟️ **Proyecto Estrella en Vivo:** [ajedrez-en-datos.streamlit.app](https://ajedrez-en-datos.streamlit.app/)  
> 💼 **LinkedIn:** [linkedin.com/in/edgar-gaytan12](https://www.linkedin.com/in/edgar-gaytan12)  
> ✉️ **Contacto:** edgaytan7@gmail.com

---

## 🎯 Perfil Profesional

Estudiante de **Ingeniería en Tecnologías de la Información y Comunicación** con certificaciones oficiales de **Google Cloud en Datos y Machine Learning**. Especializado en la ingesta, limpieza y análisis de datos utilizando Python (Pandas, Requests) y SQL avanzado (CTEs, Window Functions), así como en la creación de herramientas interactivas en Streamlit.

---

## ♟️ Proyecto Insignia: Ajedrez en Datos

*Análisis exploratorio de más de 2,900 partidas de Chess.com con Python, Pandas, SQLite y Streamlit.*

* **Repositorio del análisis:** [github.com/edgarrr-45/ajedrez-en-datos](https://github.com/edgarrr-45/ajedrez-en-datos)
* **Aplicación interactiva:** [ajedrez-en-datos.streamlit.app](https://ajedrez-en-datos.streamlit.app/)

### Aspectos Técnicos Destacados:
* **Ingesta por API REST:** Extracción automatizada del historial completo de 2,943 partidas en 38 meses desde los endpoints de Chess.com.
* **Procesamiento y ETL con Pandas:** Limpieza de partidas duplicadas, reclasificación de 6 modos de finalización y conversión horaria de UTC a hora de Ciudad de México.
* **Rigor Estadístico y Refutación de Sesgos:** Detección empírica de cómo una muestra mensual aislada (octubre 2026) sugería un rendimiento opuesto al del dataset global, confirmando una ventaja real de **+8.8% con piezas blancas en Blitz** en la población completa.
* **Dualidad SQL & SQLite:** Replicación cruzada de cada métrica mediante consultas analíticas (`LAG`, `LEAD`, promedios móviles) para contrastar resultados entre Pandas y un motor relacional.

---

## 🛠️ Stack Tecnológico de la Web

La arquitectura del portafolio fue diseñada siguiendo buenas prácticas de ingeniería de software:

* **Framework Web:** [Astro](https://astro.build/) — Renderizado estático de alto rendimiento, cero JavaScript innecesario en el cliente y arquitectura basada en componentes modulares.
* **Estilos:** [Tailwind CSS v4](https://tailwindcss.com/) — Sistema de diseño personalizado con enfoque editorial de alta gama (*Cream `#F3EEE3`*, *Ink Black `#111111`*, *Burnt Orange `#D9541E`*).
* **Control de Versiones y Despliegue:** Git, GitHub y GitHub Pages mediante GitHub Actions (CI/CD).

### Arquitectura de Componentes (`src/components/`):
* `Navbar.astro`: Barra de navegación fija con efecto de vidrio esmerilado (*frosted glass*) y enlaces ancla directos.
* `Hero.astro`: Propuesta de valor, llamadas a la acción principales y cinta modular del ecosistema técnico.
* `ChessStudy.astro`: Caso de estudio interactivo con grid de KPIs, bloques Bento de metodología y gráfica real de Matplotlib enmarcada.
* `Certifications.astro`: Credenciales oficiales de Google Cloud (Data, ML & AI) y botón de verificación a LinkedIn.
* `BaseLayout.astro`: Plantilla maestra (`src/layouts/`) con inyección dinámica de títulos (`Astro.props`) y estilos globales.

---

## 🚀 Ejecución en Entorno Local

Si deseas clonar y correr este portafolio en tu máquina:

```bash
# 1. Clonar el repositorio
git clone https://github.com/edgarrr-45/mi-portfolio.git
cd mi-portfolio

# 2. Instalar dependencias
npm install

# 3. Iniciar el servidor de desarrollo
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321) en tu navegador para ver el resultado.

---

## 📬 Contacto y Redes

* **LinkedIn:** [Edgar Gerardo Gaytán Díaz](https://www.linkedin.com/in/edgar-gaytan12)
* **GitHub:** [@edgarrr-45](https://github.com/edgarrr-45)
* **Correo electrónico:** edgaytan7@gmail.com
