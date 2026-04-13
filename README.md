# TRABAJO PRACTICO N°1 
# Fundamentos y Ecosistemas del Desarrollo Movil
## Carrera : Analisis en Sistemas y Desarrollo Software
## Profesor: Rene Rosales
## Alumnos:  Oña Joel, Marcos Ferreyra y Nelson Calmejane
## Año : 2026

## 1-¿Cuáles son los principales sistemas operativos para dispositivos móviles en la actualidad?
En un mundo en el que los smartphones se han convertido en algo cotidiano, el sistema operativo es el elemento central de cualquier dispositivo. Los principales sistemas son:
*Android: Es conocido por su facilidad de uso y la gran variedad de aplicaciones disponibles en Google Play Store. Android es especialmente popular entre los usuarios que desean personalizar su dispositivo.
*iOS: El sistema operativo de Apple, es conocido por su manejo intuitivo y sus altos estándares de seguridad. Está diseñado específicamente para iPhones.
*Windows Phone: Este sistema operativo se dejó de fabricar oficialmente en 2019. Microsoft ya no ofrece soporte para el sistema y la mayor parte del contenido de la tienda de aplicaciones ha desaparecido.
*KaiOS: Es un sistema operativo para los denominados teléfonos básicos, es decir, teléfonos móviles menos potentes. Ofrece funciones básicas de smartphone, como navegador.
## 2-¿Cuáles son las principales diferencias técnicas entre el desarrollo nativo para iOS y para Android en la actualidad?

## iOS: 
Se desarrolla en Xcode (solo funciona en macOS).

## Android:
 Se usa Android Studio (multiplataforma: Windows, Linux, macOS)
 
|     *Esto hace que iOS requiera sí o sí una computadora Apple.*
  ---

  | Característica                | Desarrollo Nativo                          | Multiplataforma (Flutter / React Native) |
|---------------------------------| -------------------------------------------|------------------------------------------|
| Rendimiento                     |Optimizado al máximo (mejor performance)    | Muy alto, cercano al nativo              |
| Costo / Tiempo                  | Mayor (dos bases de código: iOS y Android) | Menor (una sola base de código)          |
| Acceso a Hardware               | Total e inmediato                          | Depende de plugins o módulos nativos     |
| Lenguajes                       | Swift / Kotlin                             | Dart / JavaScript                        |

## 3 - ¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de 
APP móviles? ¿Qué ventajas ofrece sobre el desarrollo multiplataforma?
Cuando hablamos de desarrollo nativo en programación de aplicaciones móviles, nos referimos a crear apps específicas para un sistema operativo en particular, utilizando sus lenguajes y herramientas oficiales.

---
Ventajas del desarrollo nativo sobre el multiplataforma:
---

a. Mejor rendimiento
---
Las apps nativas están optimizadas para el sistema operativo, por lo que funcionan más rápido y de manera más fluida.

b. Acceso completo al hardware
---
Permite usar sin limitaciones componentes del dispositivo como cámara, GPS, sensores, Bluetooth, etc.

c. Mejor experiencia de usuario 
---
Se adaptan perfectamente a las guías de diseño del sistema (Material Design en Android, Human Interface en iOS), logrando interfaces más naturales.

d. Mayor estabilidad y menor cantidad de errores
---
Al estar desarrolladas específicamente para un sistema, hay menos problemas de compatibilidad.

e. Acceso inmediato a nuevas funciones del sistema
---
Cuando el sistema operativo se actualiza, las apps nativas pueden aprovechar rápidamente las nuevas características.

## 4 - ¿Qué ventaja principal ofrece un Framework Multiplataforma (como Flutter o ReactNative) frente al desarrollo nativo?

| Desarrollo Nativo                               | Framework Multiplataforma                              |
| ----------------------------------------------- | ------------------------------------------------------ |
| Mayor seguridad en la aplicación                | Menor esfuerzo de desarrollo (menos código duplicado)  |
| Mejor integración con el sistema operativo      | Permite lanzar la app en menos tiempo (time-to-market) |
| Acceso inmediato a nuevas funciones del sistema | Ideal para equipos pequeños                            |
| Mejor soporte oficial de cada plataforma        | Comunidad amplia y muchos recursos disponibles         |

## 5 - En el contexto de la arquitectura móvil, ¿cuál es la función de una API REST importa el sistema operativo desde el cuál se consuma la API o es indistinto? 

Una API RES (Interfaz de Programación de Aplicaciones):
--- 
Cumple la función de conectar la aplicación con un servidor, permitiendo enviar y recibir datos.Permite que distintas aplicaciones (sin importar el sistema operativo) puedan comunicarse con el mismo servidor, garantizando compatibilidad y reutilización del backend.

---
Esto se debe a que las APIs REST usan estándares universales como:
---
|Protocolo HTTP/HTTPS
---

|Formato de datos como JSON
---






