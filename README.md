# 🧮 Algoritmos de Dijkstra y Euclides - Visualizadores Interactivos

<p align="center">
  <img src="img/Umg.png" alt="Universidad Mariano Gálvez" width="100" height="100">
</p>

<p align="center">
  <strong>Proyecto educativo interactivo para visualizar y comprender los algoritmos de Dijkstra y Euclides</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=black" alt="SVG">
</p>

---

## 📋 Descripción

Este proyecto presenta dos herramientas educativas interactivas desarrolladas como parte del programa de Lógica de la Universidad Mariano Gálvez de Guatemala:

1. **🗺️ Visualizador de Algoritmo de Dijkstra**: Implementación interactiva para encontrar rutas más cortas en grafos ponderados
2. **🔢 Calculadora de Algoritmo de Euclides**: Herramienta visual para calcular el Máximo Común Divisor (MCD) de múltiples números

## ✨ Características Principales

### 🗺️ Algoritmo de Dijkstra

- **Interfaz interactiva** para crear y editar grafos
- **Múltiples modos de transporte**: A pie, bicicleta, automóvil
- **Visualización en tiempo real** de rutas óptimas
- **Animaciones** de avatares siguiendo las rutas calculadas
- **Modo paso a paso** para fines educativos
- **Exportación** de grafos (JSON, SVG, PNG)
- **Zoom y navegación** en el lienzo
- **Sonidos** de confirmación

### 🔢 Algoritmo de Euclides

- **Cálculo visual** del MCD usando divisiones sucesivas
- **Soporte para múltiples números** (más de 2)
- **Representación gráfica** del proceso de división
- **Pasos detallados** del algoritmo
- **Interfaz intuitiva** para agregar/quitar números
- **Funcionalidad de impresión/PDF**

## 🚀 Demo en Vivo

Puedes probar el proyecto directamente desde tu navegador:

1. Clona este repositorio
2. Abre `home.html` en tu navegador web
3. Navega entre las diferentes herramientas

## 🛠️ Instalación y Uso

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación de software adicional

### Pasos para ejecutar

```bash
# Clonar el repositorio
git clone https://github.com/zmenendez/PROYECTO-Algoritmo-de-Euclides-y-Algoritmo-de-Dijkstra.git

# Navegar al directorio
cd PROYECTO-Algoritmo-de-Euclides-y-Algoritmo-de-Dijkstra

# Abrir en navegador
# Opción 1: Doble clic en home.html
# Opción 2: Servir con servidor local (recomendado)
python -m http.server 8000
# Luego abrir http://localhost:8000/home.html
```

## 📁 Estructura del Proyecto

```
PROYECTO-Algoritmo-de-Euclides-y-Algoritmo-de-Dijkstra/
├── home.html                 # Página principal de navegación
├── dijkstra_pro_v6.html     # Visualizador de Dijkstra
├── euclides.html            # Calculadora de Euclides
├── img/
│   └── Umg.png             # Logo de la universidad
├── LICENSE                  # Licencia del proyecto
└── README.md               # Este archivo
```

## 🎯 Características Técnicas

### Algoritmo de Dijkstra
- **Complejidad**: O(E log V) con cola de prioridad
- **Restricciones**: Pesos no negativos
- **Implementación**: JavaScript puro con SVG
- **Características avanzadas**:
  - Grafos dirigidos y no dirigidos
  - Generación aleatoria de grafos
  - Múltiples rutas óptimas
  - Persistencia local de mapas

### Algoritmo de Euclides
- **Complejidad**: O(log min(a,b))
- **Método**: Divisiones sucesivas
- **Visualización**: Tablas de división paso a paso
- **Soporte**: Números enteros de cualquier tamaño

## 🎨 Diseño y UX

- **Paleta de colores consistente**: Oxford Blue, Vista Blue, Amande, Orange
- **Diseño responsivo** para diferentes tamaños de pantalla
- **Tipografía moderna** (Lexend, System UI)
- **Animaciones fluidas** y feedback visual
- **Accesibilidad** con etiquetas ARIA y navegación por teclado

## 🔧 Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Gráficos**: SVG, Canvas API
- **Estilo**: CSS Grid, Flexbox, CSS Custom Properties
- **Interactividad**: Event Listeners, DOM Manipulation
- **Persistencia**: LocalStorage API
- **Audio**: Web Audio API

## 📚 Conceptos Educativos

### Temas Cubiertos
- **Teoría de Grafos**: Nodos, aristas, pesos, conectividad
- **Algoritmos de Caminos Mínimos**: Dijkstra, complejidad computacional
- **Teoría de Números**: MCD, algoritmo de Euclides, aplicaciones
- **Estructuras de Datos**: Colas de prioridad, grafos de adyacencia
- **Análisis de Algoritmos**: Complejidad temporal y espacial

### Aplicaciones Prácticas
- **Navegación GPS**: Cálculo de rutas óptimas
- **Redes de Computadoras**: Enrutamiento de paquetes
- **Criptografía**: Generación de claves RSA
- **Matemáticas**: Simplificación de fracciones

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia especificada en el archivo [LICENSE](LICENSE).

## 👥 Autores

- **Estudiantes de Lógica** - Universidad Mariano Gálvez de Guatemala
- **Año**: 2025, Segundo Semestre

## 🙏 Agradecimientos

- Universidad Mariano Gálvez de Guatemala
- Profesores del curso de Lógica
- Comunidad de desarrolladores web educativos

---

<p align="center">
  <strong>Desarrollado con ❤️ para fines educativos</strong>
</p>

<p align="center">
  © 2025 Universidad Mariano Gálvez de Guatemala
</p>