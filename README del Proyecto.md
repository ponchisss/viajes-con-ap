# **Planificador de Viajes con IA ✈️🌎**

Esta es una aplicación web interactiva que genera itinerarios de viaje altamente personalizados. Utiliza una arquitectura basada en la combinación de tres APIs diferentes para ofrecer una experiencia única al usuario, adaptándose a su destino, sus intereses y las condiciones meteorológicas reales.

## **Arquitectura de Datos y APIs Utilizadas**

El flujo de información del sistema se basa en la integración armoniosa de las siguientes APIs:

1. **OpenWeatherMap API:** Se encarga de obtener el pronóstico del clima en tiempo real de la ciudad destino. Esto permite a la aplicación saber si debe priorizar actividades al aire libre o en interiores.  
2. **Google Places API:** Proporciona un listado de lugares de interés turístico, restaurantes y parques cercanos al destino elegido, categorizados según las preferencias del usuario (cultura, naturaleza, gastronomía, aventura).  
3. **Google Gemini API (IA Generativa):** Funciona como el "cerebro" del sistema. Recibe los datos crudos del clima y de los lugares, y genera un itinerario estructurado en formato JSON, con recomendaciones lógicas y coherentes separadas por bloques de tiempo (Mañana, Tarde, Noche).

## **Checklist de Progreso e Hitos de Laboratorio**

A continuación, se detalla el progreso del flujo de trabajo de laboratorio:

* \[x\] **Fase 1: Idea de Negocio Definida:** He planteado un problema interactivo original y elegí el tema libre de mi web.  
* \[x\] **Fase 2: Consumo de API 1 Completado:** La primera API pública (Clima) responde correctamente en mi Frontend.  
* \[x\] **Fase 2: Consumo de API 2 Completado:** La segunda API pública (Lugares) responde de manera interactiva en la interfaz.  
* \[x\] **Fase 2: Consumo de API 3 Completado:** Las 3 APIs (incluyendo la de IA) funcionan al mismo tiempo en armonía visual y lógica.  
* \[x\] **Fase 3: Repositorio Creado en GitHub:** Mi proyecto está respaldado en una rama pública con control de versiones.  
* \[x\] **Fase 3: README.md ESTRUCTURADO:** Incluí la descripción técnica de las APIs y la arquitectura de datos del sistema.  
* \[x\] **Fase 4: Configuración de Hosting Completa:** Desplegué el sitio web mediante GitHub Pages, Vercel o Netlify.  
* \[x\] **Fase 4: Verificación Consola en Producción:** He comprobado que la web carga perfectamente en vivo sin lanzar errores de CSP.

## **Estructura del Proyecto**

* index.html: Archivo principal que contiene la estructura visual (frontend), estilizado con Tailwind CSS. Incluye la lógica de JavaScript para capturar los datos del usuario, simular el estado de carga y renderizar el itinerario dinámicamente.  
* README.md: Documentación técnica y seguimiento de hitos del proyecto.