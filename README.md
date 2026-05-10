# LorHels CV

### 🚀 1. El Concepto Central

LORHELS CV es una plataforma digital de reclutamiento de nueva generación. Funciona como un ecosistema donde los profesionales crean perfiles digitales seguros y las empresas buscan talento. Todo envuelto en un diseño **Modo Oscuro (Dark Mode)** premium, moderno y responsivo.

---

### 👥 2. Los Tres Perfiles de Usuario

#### 👨‍💻 1. El Candidato (Usuario)

* **Gestión de Perfil:** Puede crear su cuenta y editar su información básica (contacto, redes, biografía, habilidades, idiomas).
* **Subida de Foto Inteligente:** Integración directa con **Cloudinary** para subir fotos de perfil de forma fluida y sin recargar la página.
* **Seguridad Antifraude:** La Experiencia, Educación y Certificados están **bloqueados**. El usuario no puede inventar títulos; debe usar el sistema interno para enviar una solicitud de actualización al Administrador (con enlaces a sus certificados).
* **Código QR:** Tiene un botón para generar su código QR personal, ideal para tarjetas de presentación.
* **Generador de PDF:** Con un clic, su perfil web se convierte en un PDF impecable en alta calidad, manteniendo el diseño elegante para imprimir o enviar.
* **💰 Modelo Freemium (Candidato PRO - $4.99/mes):** Si intenta ver qué empresas han escaneado su QR, choca con un muro de pago (Paywall). Si se hace PRO, desbloquea un panel de métricas con el nombre, correo y fecha de las empresas que vieron su currículum.

#### 🏢 2. La Empresa (Reclutador)

* **Acceso Protegido:** Cuando escanean el QR de un candidato, la plataforma les obliga a iniciar sesión. Esto protege los datos del candidato y registra la visita.
* **💰 Modelo Freemium (Reclutador Premium - $19.99/mes):** * **Plan Gratis:** Solo pueden ver los CVs de los QR que escanean físicamente.
* **Plan Premium:** Se les desbloquea un "Portal Premium" con un **buscador global** para encontrar talentos en toda tu base de datos y un sistema para guardar candidatos en **Favoritos** (con íconos de corazón).

#### 👑 3. El Administrador (Tú)

* **Consola de Mando:** Un panel de control dividido en 3 columnas.
* **Gestión de Usuarios (Proxy):** Puedes ver a todos los registrados, buscar por nombre y entrar a editar sus perfiles simulando ser ellos, saltándote las restricciones para añadirles la experiencia y educación validada.
* **Bandeja de Edición:** Recibes y marcas como "Listas" las solicitudes de los candidatos que quieren añadir cosas a su CV.
* **Gestión de Pagos PRO:** Recibes las peticiones de los que quieren pagar.

---

### ⚡ 3. Funcionalidades "Killer" (La Magia del Sistema)

* **Cobros sin comisiones (Vía WhatsApp):** En lugar de usar pasarelas de pago complejas como Stripe o PayPal, el sistema automatiza un mensaje a tu WhatsApp para que el cliente te mande el comprobante de transferencia. Tú lo apruebas con un clic en tu consola.
* **Caducidad Automática (Lazy Check):** El sistema calcula inteligentemente los 30 días de los planes PRO. Si un usuario se pasa de la fecha, la próxima vez que inicie sesión, el sistema le quita el PRO automáticamente y lo devuelve al plan Gratis.
* **Notificaciones "Toast":** Alertas flotantes y modernas de éxito o error que desaparecen solas, dándole una experiencia de usuario (UX) de primer nivel.

---

### 🛠️ 4. Arquitectura y Tecnología (Stack Serverless)

* **Frontend:** HTML5, Tailwind CSS (diseño y animaciones) y Vanilla JS.
* **Backend & Base de Datos:** Firebase Auth (Seguridad encriptada) y Firebase Firestore (Base de datos NoSQL ultrarrápida en tiempo real).
* **Almacenamiento de Imágenes:** API de Cloudinary.
* **Librerías Extra:** `QRCode.js` (para los QRs), `html2pdf.js` (para los PDFs) y FontAwesome (para los íconos).

---
