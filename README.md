# Seguridad Informática

## Datos del estudiante
* **Nombre y apellido:** Juan Ignacio Illuminati
* **Curso:** 6A
* **Materia:** desarrollo de soluciones informáticas 

---

## Parte A. Investigación

**1. ¿Qué es la seguridad informática y cuál es su importancia?**
La seguridad informática es el conjunto de prácticas, herramientas y normas destinadas a proteger los sistemas, redes, dispositivos y datos digitales contra accesos no autorizados, daños o robos. Su importancia radica en que resguarda nuestra privacidad, evita pérdidas económicas o de información valiosa y asegura que las plataformas digitales que usamos a diario funcionen sin interrupciones.

**2. ¿Qué significan los principios de confidencialidad, integridad y disponibilidad?**
Son los tres pilares básicos (conocidos como el triángulo CIA) sobre los que se construye la protección de la información. La **confidencialidad** asegura que solo las personas autorizadas puedan ver los datos; la **integridad** garantiza que la información no sea alterada ni borrada sin permiso; y la **disponibilidad** asegura que los sistemas y archivos estén accesibles siempre que un usuario autorizado los necesite.

**3. ¿Cuál es la diferencia entre virus, malware y ransomware?**
El **malware** es el término general que engloba a cualquier programa diseñado con intenciones maliciosas (espiar, robar o dañar). El **virus** es un tipo específico de malware que infecta archivos y se replica para dañar el sistema, mientras que el **ransomware** es otro tipo de malware que cifra o bloquea el acceso a los archivos de la víctima para exigir un pago (rescate) a cambio de liberarlos.

**4. ¿Qué es el phishing? ¿Cómo podemos reconocerlo?**
El phishing es una técnica de engaño digital en la que los atacantes se hacen pasar por entidades confiables (como bancos, redes sociales o servicios de correo) para robar contraseñas o datos bancarios. Se puede reconocer por mensajes con tono de urgencia exagerada, errores de ortografía, remitentes sospechosos y enlaces cuyas direcciones web (URL) no coinciden con las oficiales.

**5. ¿Qué es la ingeniería social?**
Es la manipulación psicológica de las personas para convencerlas de que revelen información confidencial o realicen acciones que comprometan su seguridad (como descargar un archivo infectado o entregar una clave). En lugar de atacar fallas técnicas de un sistema, aprovecha la confianza, el miedo o la distracción del usuario.

**6. ¿Qué características debe tener una contraseña segura?**
Una contraseña segura debe ser larga (preferentemente de 14 caracteres o más) y combinar letras mayúsculas, minúsculas, números y símbolos. Además, debe ser única para cada plataforma, no contener datos personales fáciles de adivinar (como fechas de nacimiento o nombres) y complementarse siempre que sea posible con la autenticación en dos pasos.

**7. ¿Qué diferencia existe entre un hacker White Hat y un Black Hat?**
La diferencia principal está en la autorización y la intención de sus acciones. El hacker **White Hat** (sombrero blanco) trabaja de forma ética y con permiso para encontrar fallas de seguridad y corregirlas, mientras que el **Black Hat** (sombrero negro) vulnera sistemas sin autorización con fines ilegales, como robar datos o causar daños.

**8. ¿Por qué es importante realizar copias de seguridad?**
Realizar copias de seguridad (backups) en lugares seguros es fundamental porque permite recuperar información valiosa ante imprevistos como fallas de hardware, borrados accidentales, robos de dispositivos o ataques de ransomware. De este modo, se garantiza la continuidad y disponibilidad de los archivos importantes sin depender de una única fuente.

---

## Parte B. Análisis de situaciones

### Situación 1: El correo sospechoso
* **a. ¿Qué amenaza informática podría estar presente?**
  Está presente un ataque de **phishing** (apoyado en ingeniería social), ya que intenta generar pánico con la amenaza de eliminar la cuenta para que el estudiante entregue su clave en un sitio falso.
* **b. ¿Qué debería hacer el estudiante?**
  No debe hacer clic en el enlace ni responder el correo. Debe verificar el remitente real, marcar el mensaje como spam o phishing, eliminarlo y, si tiene dudas sobre su cuenta, ingresar directamente desde el navegador escribiendo la dirección oficial de Google.
* **c. ¿Qué podría suceder si ingresa sus datos?**
  Los atacantes obtendrían el control total de su cuenta de Google, lo que les permitiría leer correos privados, robar archivos de Drive, suplantar su identidad y acceder a otras plataformas vinculadas a ese correo.

### Situación 2: La contraseña compartida
* **a. ¿Qué errores de seguridad está cometiendo?**
  Está cometiendo dos errores graves: reutilizar la misma contraseña en múltiples servicios distintos y compartir sus credenciales de acceso con otra persona.
* **b. ¿Qué consecuencias podría tener?**
  Si una sola de esas plataformas sufre una filtración de datos, los atacantes podrán acceder automáticamente a todas sus demás cuentas. Además, al compartirla con un compañero, pierde el control sobre quién accede a su información, exponiéndose a modificaciones no autorizadas, bromas pesadas o suplantación de identidad (incluso si el compañero no tiene mala intención, podría descuidar la clave).
* **c. ¿Qué medidas debería implementar?**
  Debe cambiar inmediatamente todas sus contraseñas por claves largas y diferentes para cada servicio, dejar de compartirlas con terceros y activar la verificación en dos pasos (2FA) en su correo y redes sociales.

### Situación 3: Archivos bloqueados
* **a. ¿Qué tipo de amenaza podría ser?**
  Se trata de una infección por **ransomware**.
* **b. ¿Qué daños podría provocar?**
  Provoca la pérdida de disponibilidad e integridad de toda la información almacenada en esa computadora (trabajos, planillas, registros). Si la computadora está conectada a la red escolar, el malware podría propagarse e infectar otros equipos compartidos, paralizando actividades administrativas o educativas y generando pérdidas económicas.
* **c. ¿Qué medidas permitirían prevenir esta situación?**
  Realizar copias de seguridad periódicas en unidades externas desconectadas o en la nube, mantener el sistema operativo y el antivirus actualizados, restringir permisos de administrador a los usuarios comunes y capacitar a docentes y alumnos para evitar descargar archivos de origen dudoso o abrir enlaces sospechosos.

---

## Parte C. Caso práctico: Seguridad en una escuela

### 1 y 2. Cinco riesgos institucionales y sus medidas preventivas

| Riesgo identificado | Medida preventiva propuesta |
| :--- | :--- |
| **1. Acceso no autorizado a la red Wi-Fi institucional** (alumnos o externos saturando la red o interceptando tráfico). | Configurar cifrado robusto (WPA2/WPA3), ocultar o segmentar la red (una red para administración/docentes y otra limitada para estudiantes) y cambiar la clave periódicamente. |
| **2. Infección por malware/ransomware mediante pendrives o descargas** en las computadoras compartidas. | Instalar y actualizar software antivirus en todos los equipos, bloquear la ejecución automática de dispositivos USB y limitar los permisos de instalación de programas. |
| **3. Robo de cuentas en la plataforma educativa** por contraseñas débiles o sesiones abiertas en aulas. | Exigir políticas de contraseñas seguras, habilitar la autenticación en dos factores para docentes/administrativos y configurar el cierre automático de sesión por inactividad. |
| **4. Pérdida o alteración de archivos administrativos** (notas, actas, legajos) por fallas técnicas o ataques. | Automatizar copias de seguridad (backups) diarias en servidores aislados o en la nube, y aplicar control de acceso basado en roles (cada usuario solo ve y edita lo que le corresponde). |
| **5. Ataques de phishing o ingeniería social** dirigidos al personal administrativo para obtener datos de la escuela. | Realizar charlas periódicas de concientización digital para todo el personal y establecer protocolos claros de verificación antes de entregar información o abrir adjuntos. |

### 3. Protección de la información personal de los estudiantes
Para proteger los datos sensibles de los alumnos (documentos, domicilios, contactos de emergencia y calificaciones) implementaría tres capas de protección:
* **Control de acceso estricto:** Solo el personal directivo y administrativo autorizado tendría permisos para consultar o modificar legajos, utilizando cuentas individuales y auditables.
* **Cifrado y almacenamiento seguro:** Guardar las bases de datos y planillas en sistemas con cifrado y conexiones seguras (HTTPS), evitando dejar archivos sueltos en computadoras de uso público.
* **Respaldo y minimización:** Realizar copias de seguridad cifradas de forma regular y evitar pedir o compartir datos personales de los estudiantes por canales informales (como grupos abiertos o correos sin protección).

### 4. Cinco reglas de seguridad informática para la institución
1. **Usar cuentas individuales y cerrar siempre la sesión** al terminar de utilizar una computadora compartida en el laboratorio o sala de profesores.
2. **No compartir contraseñas ni anotarlas en lugares visibles** (como papeles pegados en monitores o cuadernos de uso común).
3. **No descargar archivos, programas ni juegos de sitios desconocidos** ni conectar dispositivos USB sin analizarlos previamente con el antivirus.
4. **No divulgar datos personales propios ni de terceros** (fotos, teléfonos, direcciones o calificaciones) sin autorización expresa.
5. **Reportar de inmediato cualquier actividad sospechosa**, correo extraño o falla en los equipos al responsable técnico de la institución.

---

## Parte D. Producción propia: Campaña de concientización

### Navegar seguros también depende de nosotros
> *"Pensar antes de hacer clic es la mejor forma de proteger lo que es tuyo."*

#### Cinco recomendaciones para navegar de forma segura
1. **Usá contraseñas largas y distintas:** Mezclá letras, números y símbolos, y no repitas la misma clave en todas tus cuentas.
2. **Activá la verificación en dos pasos:** Agregá un código extra al iniciar sesión para que nadie entre a tus redes o correo aunque descubra tu contraseña.
3. **Desconfiá de los mensajes apurados o raros:** Antes de tocar un enlace, mirá bien la dirección de la página y fijate si es real.
4. **Cuidá lo que subís a internet:** Revisá la privacidad de tus redes sociales y no publiques datos personales como tu dirección, teléfono o escuela.
5. **Actualizá el celular y la compu:** Las actualizaciones arreglan fallas que otros pueden aprovechar para entrar a tus dispositivos.

#### Advertencia sobre una amenaza: Cuidado con el Phishing
El **phishing** es un engaño muy común en internet. Consiste en mandar mensajes o correos falsos haciéndose pasar por un banco, una red social o una plataforma conocida para asustarte o apurarte (por ejemplo, diciéndote que te van a cerrar la cuenta). Lo que buscan es que entres a un enlace trucho y escribas tu contraseña. Acordate que ninguna página oficial te va a pedir tus claves por mensaje.

#### Reflexión
Hoy usamos internet para estudiar, hablar con amigos y guardar cosas importantes. Por eso, cuidar nuestros datos no es solo tarea de los técnicos, sino algo que tenemos que hacer todos los días con sentido común. Si somos responsables con lo que compartimos y respetamos la privacidad de los demás, internet se vuelve un lugar mucho más seguro para todos.
