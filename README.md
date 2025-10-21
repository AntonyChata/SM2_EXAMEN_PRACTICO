# SM2_EXAMEN_PRACTICO

# 🐾 SOS Mascotas – Proyecto Flutter

## 📘 Datos del proyecto
- **Curso:** Soluciones Móviles 2  
- **Alumno:** Brant Antony Chata Choque  
- **Fecha:** 21/10/2025  
- **Repositorio GitHub:** [https://github.com/AntonyChata/SM2_EXAMEN_PRACTICO.git](https://github.com/AntonyChata/SM2_EXAMEN_PRACTICO.git)

---

## 📱 Descripción del Proyecto

**SOS Mascotas** es una aplicación móvil desarrollada con **Flutter** que tiene como objetivo facilitar la **búsqueda, rescate y adopción de mascotas** perdidas en la comunidad.  
La app integra **Firebase** para autenticación, almacenamiento de datos e integración de notificaciones push, lo que permite una experiencia en tiempo real para los usuarios.

El proyecto forma parte del curso **Soluciones Móviles 2**, orientado al desarrollo de aplicaciones multiplataforma modernas con integración de servicios en la nube.

---

## 🧩 Historia de Usuario

**Como usuario**, quiero poder:
1. **Registrarme e iniciar sesión** en la app para acceder a las funciones.  
2. **Publicar mascotas perdidas o encontradas**, incluyendo nombre, descripción, ubicación e imagen.  
3. **Recibir notificaciones** cuando alguien publique una mascota cerca de mi zona.  
4. **Consultar publicaciones existentes** y contactar al dueño o rescatista.  
5. **Editar o eliminar mis publicaciones** cuando ya se haya encontrado a la mascota.

---

## ⚙️ Funcionalidades Implementadas

| Funcionalidad | Descripción |
|----------------|-------------|
| 🔐 **Autenticación Firebase** | Registro e inicio de sesión con correo y contraseña. |
| 📲 **Notificaciones Push (FCM)** | Envío y recepción de notificaciones en tiempo real usando Firebase Messaging. |
| 🐕 **Gestión de Mascotas** | Creación, listado y actualización de mascotas perdidas/encontradas. |
| 📸 **Subida de Imágenes** | Carga de fotos a Firebase Storage. |
| 📍 **Ubicación** | Posibilidad de registrar ubicación del hallazgo o pérdida. |
| 💾 **Firestore Database** | Almacenamiento en tiempo real de usuarios y mascotas. |

---

## 🧠 Tecnologías Utilizadas
- **Flutter SDK** 3.8.x  
- **Dart SDK** 3.8.x  
- **Firebase Authentication**  
- **Firebase Cloud Firestore**  
- **Firebase Cloud Messaging (FCM)**  
- **Firebase Storage**  
- **Android Studio / Visual Studio Code**

---

## 🖼️ Capturas de Pantalla

| Pantalla | Descripción |
|-----------|--------------|
| ![Login](docs/images/login.png) | Pantalla de inicio de sesión y registro de usuario. |
| ![Inicio](docs/images/home.png) | Listado de publicaciones de mascotas perdidas/encontradas. |
| ![Detalle](docs/images/detail.png) | Detalle de una mascota con datos y botón de contacto. |
| ![Notificación](docs/images/notification.png) | Ejemplo de notificación push recibida. |

*(Guarda tus capturas en la carpeta `/docs/images/` para que se visualicen correctamente.)*

---

## 🚀 Ejecución del Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/AntonyChata/SM2_EXAMEN_PRACTICO.git
   cd SM2_EXAMEN_PRACTICO
