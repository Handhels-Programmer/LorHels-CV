# LorHels-CV

1. El Concepto Central
Has creado una plataforma digital de reclutamiento y gestión de currículums. Funciona como un puente seguro y moderno entre profesionales (candidatos) y reclutadores (empresas), con un modelo de negocio integrado.

2. Tecnología Utilizada
Frontend: HTML5 puro y Tailwind CSS (para un diseño moderno y responsivo que se ve bien en móviles y computadoras).

Backend & Base de Datos: Firebase Firestore (base de datos en tiempo real súper rápida).

Seguridad: Firebase Authentication (encriptación de contraseñas y manejo seguro de sesiones).

Herramientas extra: QRCode.js (para generar códigos QR en vivo) y html2pdf.js (para exportar los CVs a PDF con alta resolución).

3. Los Tres Perfiles de Usuario
👨‍💼 El Candidato (Usuario)
Creación de Perfil: Puede registrarse, subir su foto (mediante URL) y llenar sus datos básicos y de contacto.

Integridad de Datos: Para evitar perfiles falsos, el candidato no puede editar su propia experiencia laboral, educación o certificaciones. Debe enviar una solicitud interna al Administrador para que lo haga.

Código QR: Tiene un botón para generar su código QR personal para ponerlo en tarjetas de presentación o compartirlo.

Plan PRO ($4.99/mes): Si paga, desbloquea un panel de métricas donde puede ver qué empresas exactas han escaneado su QR y en qué fecha.

🏢 La Empresa (Reclutador)
Escaneo Seguro: Cuando escanean un QR, la plataforma les exige iniciar sesión. Esto protege los datos del candidato y registra la visita.

Plan Básico (Gratis): Solo pueden ver los currículums de los QRs que escanean físicamente.

Plan Premium ($19.99/mes): Se les desbloquea un "Portal Premium" con un buscador global para encontrar talentos por profesión o habilidad en toda tu base de datos, y pueden guardar candidatos en una lista de Favoritos (con íconos de corazón).

👑 El Administrador (Tú)
Consola Maestra: Tienes un panel de control dividido en tres columnas con buscador integrado.

Control Total: Puedes "Simular y Editar" cualquier perfil, saltándote las restricciones para añadirles la experiencia, habilidades y certificados.

Bandeja de Solicitudes: Recibes y gestionas las peticiones de los candidatos que quieren actualizar su CV.

Aprobación de Pagos: Recibes las solicitudes de los usuarios que quieren ser PRO. Verificas el pago por WhatsApp y con un clic les activas la cuenta por exactamente 30 días.

4. Funcionalidades "Killer" (Lo que hace especial a tu app)
Generación de PDF: Un botón mágico que toma el perfil web y lo convierte en un documento PDF con diseño impecable, listo para descargar o imprimir.

Flujo de Pago por WhatsApp: En lugar de usar pasarelas complejas (y pagar comisiones), el sistema automatiza un mensaje de WhatsApp para que el usuario te envíe el comprobante, manteniendo un toque humano y seguro.

Caducidad Automática (Lazy Check): El sistema calcula inteligentemente los 30 días de los planes PRO. Si un usuario se pasa de la fecha, el sistema lo devuelve al plan Gratis automáticamente la próxima vez que inicie sesión.
