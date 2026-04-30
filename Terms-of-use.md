# Privacy Policy — RaceTimer

**Última actualización:** 29 de abril de 2026

## 1. Introducción

RaceTimer ("la app", "nosotros") es una aplicación de cronometraje y análisis de sesiones de deportes acuáticos desarrollada por WindPowered. Esta política de privacidad describe qué datos recopila la app, cómo se usan y cómo se protegen.

---

## 2. Datos que recopila la app

### 2.1 Datos de ubicación (GPS)

- **Qué:** Coordenadas GPS durante sesiones activas de grabación.
- **Para qué:** Registrar la ruta, calcular velocidad, distancia y análisis de maniobras.
- **Dónde se almacena:** Exclusivamente en el dispositivo del usuario. No se transmiten a servidores externos.
- **Cuándo se accede:** Solo mientras la sesión está activa. Se requiere permiso "Mientras se usa la app".

### 2.2 Datos de salud (HealthKit)

- **Qué:** Frecuencia cardíaca durante las sesiones.
- **Para qué:** Mostrar el ritmo cardíaco en tiempo real en el Apple Watch y guardarlo junto a la sesión.
- **Dónde se almacena:** En Apple Health del dispositivo. RaceTimer no envía datos de salud fuera del dispositivo.
- **Permisos:** Lectura y escritura en HealthKit, solicitados explícitamente al usuario.

### 2.3 Datos de movimiento y giroscopio

- **Qué:** Datos del acelerómetro y giroscopio del Apple Watch.
- **Para qué:** Detección automática de maniobras (viradas, trasluchadas) durante la sesión.
- **Dónde se almacena:** Procesados en tiempo real en el dispositivo. No se almacenan datos brutos de movimiento.

### 2.4 Fotos

- **Qué:** Capturas de pantalla de resúmenes de sesión.
- **Para qué:** Guardar imágenes en el álbum de fotos del usuario a petición explícita.
- **Permisos:** Solo escritura en la fototeca. La app no lee fotos existentes.

### 2.5 Nombre del usuario (Sign in with Apple)

- **Qué:** Nombre proporcionado por Apple al iniciar sesión por primera vez.
- **Para qué:** Personalización del perfil dentro de la app.
- **Dónde se almacena:** Localmente en el Keychain del dispositivo. No se envía a servidores externos.
- **Nota:** Apple solo proporciona el nombre en el primer inicio de sesión. El usuario puede modificarlo manualmente desde la app.

### 2.6 Datos de compras (StoreKit / App Store)

- **Qué:** Estado de suscripción activa (RaceTimer Pro).
- **Para qué:** Verificar el acceso a las funciones premium.
- **Cómo:** Gestionado íntegramente por Apple App Store. RaceTimer no almacena ni procesa datos de pago.
- **Sincronización:** El estado de suscripción se sincroniza entre iPhone y Apple Watch de forma local mediante WatchConnectivity, con una validez máxima de 24 horas sin confirmación.

---

## 3. Datos que la app NO recopila

- ❌ No recopila datos de uso ni analíticas de comportamiento.
- ❌ No usa herramientas de terceros como Firebase, Mixpanel, Amplitude ni similares.
- ❌ No muestra publicidad ni comparte datos con redes publicitarias.
- ❌ No transmite datos de sesión, GPS, salud ni movimiento a ningún servidor externo.
- ❌ No crea perfiles de usuario en servidores propios.

---

## 4. Almacenamiento y seguridad

Todos los datos generados por la app (sesiones, rutas GPS, frecuencia cardíaca, configuración) se almacenan **localmente en el dispositivo** del usuario mediante:

- `UserDefaults` para configuración y preferencias.
- `Keychain` para datos de identidad sensibles (nombre de usuario, tokens de sesión).
- Archivos locales en el sandbox de la app para el historial de sesiones.

No existe ningún servidor backend de RaceTimer que almacene datos personales.

---

## 5. Datos de terceros

### Apple App Store / StoreKit

Las compras y suscripciones son procesadas por Apple. Consulta la [Política de Privacidad de Apple](https://www.apple.com/legal/privacy/) para más información sobre cómo Apple gestiona los datos de pago.

### HealthKit

Los datos de salud se almacenan en Apple Health y están sujetos a la política de privacidad de Apple.

---

## 6. Privacidad de menores

RaceTimer no está dirigida a menores de 13 años. No recopilamos conscientemente información de menores.

---

## 7. Tus derechos

Como todos los datos se almacenan localmente en tu dispositivo:

- Puedes **eliminar todos los datos** desinstalando la app.
- Puedes **revocar permisos** (ubicación, salud, movimiento, fotos) en cualquier momento desde **Ajustes → Privacidad** en tu iPhone o Apple Watch.
- Los datos de salud en HealthKit pueden gestionarse desde la app **Salud** de Apple.

---

## 8. Cambios en esta política

Cualquier actualización a esta política se publicará en esta página con la fecha de última actualización. Los cambios significativos se notificarán mediante una actualización de la app en el App Store.

---

## 9. Contacto

Si tienes preguntas sobre esta política de privacidad, puedes contactarnos en:

**Email:** unava001@gmail.com 
**Desarrollador:** Ulises Navarro
