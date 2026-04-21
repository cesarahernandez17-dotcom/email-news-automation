# Email News Automation

Este repositorio contiene un workflow de **n8n** que automatiza la recopilación y envío diario de noticias por correo electrónico, utilizando **Google News RSS** y **Gemini 2.5 Flash**.

## 🚀 Funcionalidad
- Se ejecuta automáticamente cada día a las 9 AM.
- Obtiene las últimas noticias desde Google News (RSS).
- Filtra y ordena las más relevantes.
- Resume las noticias con IA (Gemini).
- Envía un correo con formato HTML a una lista de destinatarios.

## 📂 Estructura del workflow
- **Schedule Trigger** → dispara la ejecución diaria.
- **RSS Read** → obtiene noticias recientes.
- **Filtros y ordenamiento** → selecciona las más relevantes.
- **Gemini AI** → resume en JSON.
- **HTML Formatter** → convierte a un correo atractivo.
- **Send Email (Gmail/Outlook)** → distribuye el resumen.

## ⚙️ Requisitos
- Instancia de **n8n** funcionando.
- Configurar credenciales de Gmail u Outlook.
- Instalar el nodo de integración con **Gemini**.

## 📧 Ejemplo de salida
El correo incluye:
- Título y resumen de cada noticia.
- Fuente original.
- Enlace directo para leer más.

## 🛡️ Notas
- Este repositorio no incluye credenciales ni IDs internos.
- Personaliza la lista de destinatarios en el nodo de envío de correo.
- Ajusta la hora de ejecución en el **Schedule Trigger**.

---

## 📜 Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

