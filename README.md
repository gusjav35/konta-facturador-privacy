# Política de Privacidad – Konta Facturador                                                                   
                                                            
  **Última actualización:** 16 de mayo de 2026

  Esta Política de Privacidad describe cómo **Konta Facturador** ("nosotros", "la App") recopila, usa y protege
  la información de sus usuarios. Al usar la App aceptas las prácticas descritas en este documento.

  ## 1. Información que recopilamos

  ### 1.1 Datos de cuenta (siempre almacenados en la nube)
  - **Correo electrónico** y **contraseña** (la contraseña se almacena cifrada con hashing seguro, nunca en
  texto plano).
  - **Nombre** (opcional).

  Estos datos se almacenan en servidores administrados por Supabase y son necesarios para autenticarte y
  gestionar tu cuenta.

  ### 1.2 Datos comerciales (almacenados localmente por defecto)
  La información que cargas en la App —datos de tu empresa, productos, clientes, comprobantes e inventario— se
  almacena **exclusivamente en tu dispositivo** y no se transmite a nuestros servidores, salvo en los siguientes
   casos:

  - **Función de Backup en la Nube (opcional):** si decides crear un backup, el contenido seleccionado
  (productos y comprobantes) se sube cifrado a Supabase para que puedas restaurarlo desde otro dispositivo o
  tras una reinstalación. Esta acción es siempre iniciada por ti. Se conservan como máximo 5 backups por
  usuario; los más antiguos se eliminan automáticamente al superar ese límite. Puedes eliminar tus backups
  manualmente en cualquier momento desde la App.

  - **Compartir comprobantes:** cuando decides enviar un PDF por WhatsApp u otra app, el archivo se transfiere
  directamente desde tu dispositivo a la app de destino, sin pasar por nuestros servidores.

  ### 1.3 Datos de suscripción (recopilados automáticamente)
  - **Estado de tu suscripción**, fechas de inicio y vencimiento, plan contratado e historial de compras.
  - **Identificador anónimo de instalación** que asocia tu cuenta con tus compras.

  Esta información se gestiona mediante **RevenueCat** y **Google Play Billing**.

  ### 1.4 Información que NO recopilamos
  No recopilamos ubicación, contactos, historial de navegación fuera de la App, ni accedemos a archivos de tu
  dispositivo más allá de los que tú selecciones (por ejemplo, una imagen de logo).

  ## 2. Cómo usamos la información

  Usamos los datos recopilados exclusivamente para:
  - Crear y mantener tu cuenta.
  - Permitirte usar las funciones de facturación, inventario y reportes.
  - Almacenar tus backups cuando los solicites.
  - Procesar y validar tu suscripción.
  - Enviarte correos de recuperación de contraseña cuando los solicites.
  - Brindarte soporte técnico cuando nos contactes.
  - Cumplir con obligaciones legales.

  **No usamos tus datos para publicidad, ni los vendemos a terceros.**

  ## 3. Servicios de terceros

  La App utiliza los siguientes servicios:

  | Servicio | Propósito | Datos compartidos |
  |---|---|---|
  | **Supabase** | Autenticación, almacenamiento de cuenta y backups opcionales | Email, contraseña cifrada,
  nombre y contenido de los backups que crees voluntariamente |
  | **RevenueCat** | Gestión de suscripciones | Identificador de usuario, estado de compras |
  | **Google Play Billing** | Procesamiento de pagos | Información de pago gestionada exclusivamente por Google
  |
  | **WhatsApp** | Compartir comprobantes (solo si lo iniciás) | El archivo PDF que decidas enviar |

  Estos servicios tienen sus propias políticas de privacidad que te recomendamos revisar.

  ## 4. Almacenamiento y seguridad

  - Tus datos en la nube se almacenan en servidores administrados por Supabase con cifrado en tránsito
  (HTTPS/TLS) y en reposo.
  - Las contraseñas se almacenan con hashing seguro y nunca son visibles para nosotros.
  - Tus datos comerciales locales se almacenan en el almacenamiento privado de la App en tu dispositivo y se
  eliminan al desinstalar la App.
  - A pesar de estas medidas, ningún sistema es 100% seguro. No podemos garantizar seguridad absoluta.

  ## 5. Conservación de datos

  Conservamos tus datos de cuenta mientras tu cuenta esté activa. Los backups en la nube se conservan hasta que
  los elimines o hasta que el límite de 5 backups por usuario los desplace automáticamente.

  Si eliminas tu cuenta desde la App, tus datos personales y todos tus backups asociados se eliminan
  permanentemente de nuestros sistemas. Los registros de transacciones pueden conservarse por el tiempo que
  exija la legislación fiscal aplicable.

  ## 6. Tus derechos

  De acuerdo con la **Ley 1581 de 2012** de Colombia (Protección de Datos Personales), tienes derecho a:
  - **Acceder** a tus datos personales.
  - **Rectificar** datos inexactos o incompletos.
  - **Eliminar** tus datos (mediante la opción "Eliminar cuenta" dentro de la App o contactándonos).
  - **Revocar** la autorización para tratar tus datos.
  - **Presentar quejas** ante la Superintendencia de Industria y Comercio.

  Para ejercer cualquiera de estos derechos, escribinos a **appsdevlabs@gmail.com**.

  ## 7. Menores de edad

  La App no está dirigida a menores de 18 años. No recopilamos intencionalmente datos de menores. Si detectamos
  que un menor ha creado una cuenta sin autorización, procederemos a eliminarla.

  ## 8. Cambios en esta política

  Podemos actualizar esta Política de Privacidad ocasionalmente. Las actualizaciones se publicarán en esta misma
   dirección con una nueva fecha de "Última actualización". El uso continuado de la App tras una actualización
  implica aceptación de los cambios.

  ## 9. Contacto

  Para consultas sobre esta política o sobre el tratamiento de tus datos:
  **appsdevlabs@gmail.com**

  Cambios clave vs. la versión anterior:

  1. Sección 1.2 — explícito que los datos comerciales están solo en el dispositivo por defecto, y se suben SOLO
   si el usuario crea un backup
  2. Tabla de Supabase — ahora dice "y backups opcionales"
  3. Sección 4 — mención del almacenamiento local
  4. Sección 5 — política de retención de backups (límite de 5, eliminación al borrar cuenta)

  Cuando lo subas, andá al Data Safety form de Play Console y declará:
  - ✅ Email y contraseña (encriptados, autenticación, requeridos)
  - ✅ Nombre (autenticación, opcional)
  - ✅ Compras en la app (gestión de cuenta, automático)
  - ✅ Identificadores de dispositivo (gestión de cuenta, automático)
  - ✅ Otros archivos de la app: PDFs/datos comerciales (gestión de cuenta, opcional — solo si crea backup)
  - ❌ Sin anuncios, sin compartir con terceros para marketing, sin analytics de comportamiento
