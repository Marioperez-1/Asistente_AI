# Humanth Chatbot 

![Humanth Logo](ruta-del-logo.png)

Esto es un chatbot virtual diseñado para la marca española de ropa de ciclismo **Humanth**. Su objetivo es guiar a los usuarios a través de catálogos, tallas, personalización de equipaciones, pedidos y devoluciones, ofreciendo información clara y asistencia inmediata en un entorno conversacional.

---

## 🚴 Características principales

- **Catálogo interactivo:** consulta maillots, culottes y colecciones cápsula.
- **Guía de tallas:** recomendaciones según medidas y tipo de prenda.
- **Personalización para clubs y eventos:** logos, colores, nombres y números en maillots y culottes.
- **Pedidos y devoluciones:** seguimiento, información de envíos y políticas de devolución.
- **Información general de la marca:** historia, misión, valores y tecnologías de sus prendas.
- **FAQs:** más de 100 preguntas frecuentes integradas para resolver dudas comunes.
- **Fallback inteligente:** mensajes alternativos y reprompts para guiar al usuario cuando no se entiende su mensaje.
- **Tono cercano y motivador:** diseñado para mejorar la experiencia de los ciclistas al interactuar con el bot.
- **Contacto humano:** integración con correo y formulario de contacto para soporte adicional.

---

## 🛠 Estructura del proyecto

- `/flows` – Contiene los flujos de conversación para Voiceflow.
- `/faqs` – Base de datos de preguntas frecuentes (JSON o CSV).
- `/assets` – Imágenes, logos y recursos multimedia para el bot.
- `/docs` – Documentación adicional y guías de integración.

---

## ⚡ Flujo principal

1. **Bienvenida** – Saludo y presentación de opciones: catálogo, tallas, personalización, pedidos, información general, contacto humano.  
2. **Catálogo** – Subcategorías: maillots, culottes, colecciones cápsula, ropa conmemorativa.  
3. **Guía de tallas** – Sugerencias y tablas de medidas.  
4. **Personalización** – Recolección de datos, logos, colores y confirmación de pedido.  
5. **Pedidos y devoluciones** – Seguimiento de pedidos, plazos de envío, política de devoluciones.  
6. **Información general** – Historia, misión, valores, tecnologías, eventos.  
7. **Contacto humano** – Email y formulario de contacto.  
8. **Fallback / No Match** – Mensajes alternativos y reprompts.  

---

## 📂 Tecnologías

- **Voiceflow** – Plataforma principal para la creación del chatbot conversacional.
- **JSON / CSV** – Para la integración de FAQ y flujos de datos.
- **HTML / CSS / JS** – Para integraciones web opcionales.
- **API/Webhooks** – Para seguimiento de pedidos y personalización avanzada .

---

## 📌 Cómo usar

1. Importar los flujos del chatbot en **Voiceflow**.
2. Subir la base de datos de FAQ (`/faqs/faqs.json`) para respuestas automáticas.
3. Configurar assets y enlaces web según las colecciones de Humanth.
4. Personalizar los mensajes de bienvenida y fallback según la personalidad de la IA.
5. Publicar el bot en el canal deseado (web, WhatsApp, Messenger).

---


## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más información.

---

**¡Gracias por usar el asistente virtual de Humanth! 🚴‍♂️**
