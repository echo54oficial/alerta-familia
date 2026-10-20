# Alerta Familia 🛡️

> Herramienta web de respuesta rápida ante hackeos de WhatsApp, suplantación de identidad y estafas digitales.

[![Privacidad](https://img.shields.io/badge/Privacidad-100%25_Local-emerald?style=flat-square)](#privacidad-y-seguridad)
[![Tecnología](https://img.shields.io/badge/Stack-HTML5_%7C_Vanilla_CSS_%7C_JS-blue?style=flat-square)](#tecnolog%C3%ADa)
[![Autor](https://img.shields.io/badge/Autor-Echo_54-purple?style=flat-square)](https://github.com/echo54oficial)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-amber?style=flat-square)](LICENSE)

---

## 🎯 ¿Qué es Alerta Familia?

**Alerta Familia** es una aplicación web ligera y enfocada en situaciones de tensión, diseñada para actuar en los primeros 15 minutos de un incidente de ciberseguridad (robo de cuenta de WhatsApp, suplantación de perfil o intento de fraude económico).

Permite alertar en segundos tanto en primera persona (*"Me robaron el WhatsApp"*) como en tercera persona (*"Le hackearon la cuenta a mi familiar: elimínenlo de los grupos ya"*), evitando la confusión y frenando transferencias de dinero a cuentas de estafadores.

---

## ✨ ¿Qué permite hacer?

* **Mensajes listos para grupos y redes:** Textos cortos y directos con formato para WhatsApp y Telegram, sin términos confusos ni explicaciones innecesarias.
* **Placas gráficas inmediatas:** Genera imágenes en alta resolución en dos formatos:
  * **Estados (IG / WP):** Proporción 9:16 vertical para Estados de WhatsApp e Historias de Instagram.
  * **Publicación:** Proporción 1:1 cuadrada para enviar como imagen en grupos y chats.
  * Opciones directas para **compartir nativamente** o **descargar la imagen PNG**.
* **SMS de auxilio a contactos de confianza:** Si te sustrajeron la cuenta de WhatsApp o no tenés internet, prepara un SMS masivo a tu círculo de emergencia con un solo toque por red celular.
* **Agenda del celular con 1 toque:** Integración con la *Contact Picker API* para seleccionar contactos directamente desde la libreta de tu teléfono (en Android/Chrome).
* **Lectura OCR de capturas (100% local):** Procesamiento en el navegador con Tesseract.js para extraer números de teléfono, CBU/CVU (22 dígitos) y Alias bancarios desde una captura o pegando con `Ctrl+V`.
* **Formateo telefónico legible:** Formatea los números sospechosos con espacios estándar (`+54 9 11 2345 6789`) para que cualquier persona pueda compararlo fácilmente con su agenda.
* **Guía oficial de denuncia (Argentina):** Acceso rápido al contacto de la **UFECI** (Ministerio Público Fiscal), enlace de correo urgente para desactivar la cuenta en WhatsApp y pasos para solicitar *Stop Debit* bancario.

---

## 🚀 Cómo utilizarla

### Opción 1: En tu navegador local
1. Descargá o cloná este repositorio.
2. Abrí `index.html` (o `alerta-familia.html`) con cualquier navegador moderno (Chrome, Edge, Safari, Firefox).
3. No requiere instalación, base de datos ni servidores externos (`Node.js`, `Python`, etc.).

### Opción 2: Publicar gratis en GitHub Pages
1. Subí este repositorio a tu cuenta de GitHub.
2. Ingresá a **Settings** > **Pages**.
3. En **Source**, seleccioná la rama `main` y la carpeta `/ (root)`.
4. En segundos tendrás una URL pública para usarla y compartirla desde cualquier celular.

---

## 🔒 Privacidad y seguridad

* **Sin servidores:** Toda la lógica, generación de placas Canvas, almacenamiento del círculo de contactos y análisis OCR se ejecutan **100% dentro de tu propio dispositivo**.
* Ningún número de teléfono, nombre ni captura se envía a servidores de terceros.
* Los contactos de confianza se guardan únicamente en el almacenamiento local de tu navegador (`localStorage`).

---

## ⚖️ Precauciones y descargo de responsabilidad

* Esta herramienta está pensada como una ayuda informativa y comunitaria de respuesta rápida.
* **No reemplaza el asesoramiento ni la intervención de organismos oficiales, fuerzas de seguridad ni entidades bancarias.**
* Antes de emitir una alerta, verificá la información y evitá difundir acusaciones o datos que no hayan sido confirmados.
* Los procedimientos y canales de contacto de la guía oficial corresponden a la República Argentina y deben verificarse periódicamente ante posibles actualizaciones institucionales.

---

## 🛠️ Tecnología

* **HTML5 semántico** con diseño responsivo mobile-first.
* **CSS moderno:** Variables HSL/HEX, soporte para modo oscuro y claro automático (`prefers-color-scheme`).
* **Vanilla JavaScript:** Cero dependencias pesadas.
* **Tesseract.js (v5 CDN):** OCR en el navegador para extracción de texto.
* **Web APIs:** Canvas API (renderizado gráfico), Web Share API, Clipboard API y Contact Picker API.

---

## 👤 Autoría y Ética Hacker

Proyecto creado y mantenido por **Echo 54** ([@echo54oficial](https://github.com/echo54oficial)).

> ### 🤝 Nota sobre el uso de este código:
> Este proyecto fue concebido para cuidar a nuestras familias y compartir herramientas útiles con la comunidad.
> Si vas a utilizar este código, hacer un fork, estudiarlo o integrarlo en tus propios desarrollos:
> * **No seas ladrón:** respetá los créditos y la autoría original de **Echo 54**.
> * La ciberseguridad comunitaria y el software libre se construyen sobre la base de la honestidad, el reconocimiento mutuo y la solidaridad.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consultá el archivo [LICENSE](LICENSE) para más detalles.
