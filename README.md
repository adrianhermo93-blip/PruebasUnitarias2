Validador de Registro - Tests con JUnit

Este proyecto contiene pruebas unitarias para validar el correcto funcionamiento de una clase ValidadorRegistro, encargada de verificar datos de usuario en un sistema de registro.

Tecnologías utilizadas

Java

JUnit 5

📂 Estructura del proyecto
src/
 ├── main/
 │    └── instituto/
 │         └── ValidadorRegistro.java
 │
 └── test/
      └── instituto/
           └── ValidadorRegistroTest.java
✅ Funcionalidades probadas

La clase de test ValidadorRegistroTest verifica las siguientes validaciones:

🔤 Validación de nombre

✔️ Nombre válido ("Carlos") → Aceptado

❌ Nombre vacío ("") → Rechazado

🔒 Validación de contraseña

✔️ Contraseña de 8 caracteres → Aceptada

❌ Contraseña corta → Rechazada

📧 Validación de email

❌ Email sin "@" → Rechazado

🎂 Validación de edad

✔️ Edad mínima (16 años) → Aceptada

▶️ Cómo ejecutar los tests

Asegúrate de tener instalado Java y un IDE (IntelliJ, Eclipse, VS Code).

Importa el proyecto como proyecto Java.

Ejecuta la clase:

ValidadorRegistroTest

O usa tu herramienta de build si tienes configurado Maven/Gradle:

mvn test
🧠 Objetivo del proyecto

Este ejercicio está diseñado para:

Practicar testing con JUnit 5

Entender la importancia de validar datos de entrada

Aplicar buenas prácticas en pruebas unitarias

✍️ Autor

Proyecto educativo para aprendizaje de testing en Java.
<img width="1919" height="1037" alt="image" src="https://github.com/user-attachments/assets/9fb67bb2-4916-4e41-b571-7fab933bca02" />
