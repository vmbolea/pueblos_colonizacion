# 🏘️ Mapa de Pueblos de Colonización

Mapa interactivo que visualiza los poblados creados por el Instituto Nacional de Colonización (INC) entre 1939 y 1971, con datos extraídos directamente de Wikipedia.

![Vista del mapa](https://i.imgur.com/placeholder.png)

## ✨ Características

- **🗺️ Visualización interactiva** - Mapa con más de 200 pueblos de colonización
- **📊 Datos en tiempo real** - Información extraída directamente de Wikipedia
- **🎨 Codificación por colores** - Gradiente amarillo → rojo según la antigüedad (1943-1971)
- **🔍 Clusters inteligentes** - Agrupación automática de marcadores cercanos
- **📅 Filtro por rango de años** - Selecciona periodos específicos con slider doble
- **🏷️ Filtro por tipo** - Diferencia entre poblados originales y ampliaciones
- **📱 Diseño responsive** - Adaptado para móviles con panel desplegable
- **💾 Caché local** - Los datos se guardan localmente por 24 horas

## 🎨 Paleta de colores

| Año | Color | Significado |
|-----|-------|-------------|
| 1943-1948 | 🟡 Amarillo | Primeros poblados |
| 1949-1953 | 🟠 Amarillo-naranja | Expansión inicial |
| 1954-1958 | 🟠 Naranja | Máxima actividad |
| 1959-1963 | 🔴 Naranja-rojo | Consolidación |
| 1964-1971 | 🔴 Rojo | Últimos poblados |
| Ampliaciones | ⚪ Gris | Ampliaciones de poblados existentes |

## 🛠️ Tecnologías utilizadas

- **Leaflet** - Biblioteca de mapas interactivos
- **OpenStreetMap** - Capas base del mapa
- **Leaflet.markercluster** - Agrupación de marcadores
- **Wikipedia API** - Extracción de datos en tiempo real
- **HTML5 / CSS3 / JavaScript (ES6+)**

## 📁 Estructura del proyecto

```
├── index.html # Página principal
├── css/
│ └── style.css # Estilos y responsive
├── js/
│ ├── wikipedia-loader.js # Conexión con API de Wikipedia
│ └── map.js # Lógica del mapa y filtros
```
## 🚀 Cómo usar

### Opción 1: Ver online (recomendado)
Visita: `https://tu-usuario.github.io/pueblos-colonizacion`

### Opción 2: Ejecutar localmente

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/pueblos-colonizacion.git

# Entrar al directorio
cd pueblos-colonizacion

# Iniciar servidor local con Python
python -m http.server 8000

# O con Node.js
npx http-server

# Abrir en navegador
http://localhost:8000
```
## 📊 Fuente de datos
Los datos se extraen automáticamente de:
Wikipedia - Anexo:Poblados del Instituto Nacional de Colonización

El sistema utiliza caché local (24 horas) para reducir llamadas a la API.

## 📧 Contacto
- Autor: Víctor Martínez Bolea

- GitHub: @vmbolea

- Demo: Enlace a la demo

## 🙏 Agradecimientos
Instituto Nacional de Colonización

Wikipedia por los datos históricos

OpenStreetMap por las capas del mapa

Leaflet y MarkerCluster

⭐ Si te gusta este proyecto, ¡no olvides darle una estrella en GitHub!
