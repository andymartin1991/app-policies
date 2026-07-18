# Política de Privacidad — Psicotécnicos Tropa

**Última actualización:** 18/07/2026

Esta Política de Privacidad describe cómo se gestionan los datos cuando utilizas la aplicación móvil **Psicotécnicos Tropa** (en adelante, la “App”).

## 1. Responsable

**Responsable/Desarrollador:** Andymarcial (autor de la App)  
**Contacto:** psicotecnicostropa@gmail.com

## 2. Datos que se recogen

La App está diseñada para funcionar sin necesidad de cuenta. Aun así, para que algunas funciones técnicas funcionen correctamente, pueden tratarse los siguientes datos:

### 2.1 Identificador anónimo de la instalación (ID interno)
- **Qué es:** un identificador aleatorio generado por la App para reconocer la instalación. No procede de identificadores de hardware, publicidad u otros datos personales.
- **Para qué se usa:**
  - Identificar al usuario de forma anónima en el sistema de suscripciones (RevenueCat).
  - Mantener coherencia del estado de la suscripción/restauración de compras.
- **Dónde se guarda y trata:** se almacena localmente en el dispositivo (SharedPreferences) y se transmite cifrado a RevenueCat como `appUserID`.

### 2.2 Datos de uso y progreso (almacenamiento local)
- **Qué se guarda:** progreso de entrenamiento (bloque/posición) y resultados de simulacros.
- **Para qué se usa:** permitir que el usuario continúe donde lo dejó y ver su evolución.
- **Dónde se guarda:** en el propio dispositivo (SharedPreferences). **No se sincroniza con servidores propios**.

### 2.3 Compras y suscripciones
La App utiliza **Google Play Billing** (Android) y el SDK de **RevenueCat** para gestionar compras y suscripciones.

- RevenueCat puede tratar información relacionada con la compra/suscripción (p. ej. estado de la suscripción, identificadores de producto, eventos de compra) para prestar el servicio.
- Las compras se procesan por **Google Play**. La App no recibe ni almacena datos de pago sensibles (p. ej. número de tarjeta).

## 3. Servicios de terceros

La App usa los siguientes servicios/SDKs de terceros:

### 3.1 RevenueCat
- **Finalidad:** gestión de suscripciones, estado premium, restauración de compras.
- **Datos tratados:** identificador anónimo (appUserID), información de suscripción/compra, diagnósticos técnicos.
- **Más información:** https://www.revenuecat.com/privacy/

### 3.2 Google Play / Google Play Billing
- **Finalidad:** procesamiento de compras y suscripciones.
- **Más información:** https://policies.google.com/privacy

## 4. Publicidad y analítica

- **Publicidad:** la App **no muestra anuncios**.
- **Analítica/Tracking:** la App no integra actualmente un SDK de analítica tipo Firebase Analytics. RevenueCat puede recopilar métricas técnicas de suscripciones necesarias para su funcionamiento.

## 5. Permisos

La App puede solicitar/usar los siguientes permisos:

- **Internet (`android.permission.INTERNET`)**: necesario para comunicarse con Google Play/RevenueCat durante la gestión de compras/suscripciones y para abrir enlaces (por ejemplo, soporte o enlaces a Google Play).
- **Billing (`com.android.vending.BILLING`)**: necesario para compras dentro de la app.

## 6. Base legal

Dependiendo del tipo de datos:
- **Ejecución del servicio (contrato):** para permitir el uso de la App y, si aplica, la verificación/gestión de la suscripción.
- **Interés legítimo:** para mantener el funcionamiento técnico y la seguridad.
- **Cumplimiento legal:** cuando sea necesario por obligaciones relacionadas con compras/suscripciones.

## 7. Conservación

- Los datos de progreso se conservan **en el dispositivo** mientras el usuario no desinstale la App o no borre los datos.
- La información de suscripción se conserva según el funcionamiento de Google Play y RevenueCat.

## 8. Compartición de datos

La App **no vende** datos personales.

Los datos pueden compartirse únicamente con:
- **Google Play** (procesamiento y verificación de compras).
- **RevenueCat** (gestión de suscripciones).

## 9. Derechos del usuario

Puedes:
- Borrar el almacenamiento local desinstalando la App o borrando sus datos desde Ajustes del dispositivo.
- Para cuestiones relacionadas con suscripciones, puedes gestionarlas desde Google Play.

Si deseas ejercer derechos o realizar consultas sobre privacidad, puedes escribir a: **psicotecnicostropa@gmail.com**.

## 10. Menores

La App no está dirigida específicamente a menores. Si eres padre/madre o tutor/a y crees que un menor ha proporcionado información personal, contacta con el desarrollador.

## 11. Cambios en esta política

Esta política puede actualizarse para reflejar cambios funcionales o legales. La fecha de “Última actualización” indicará la versión vigente.
