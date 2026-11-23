---
title: sak privacy policy
---

# sak privacy policy

*Last updated: 2026-11-18* · [Español](#es)

sak is a digital wellbeing app: it measures how you use your phone, helps you set limits on apps and track habits, and shows a mascot, Sak, that reminds you of them. This policy explains what data sak uses and where it goes.

**In short: everything sak records stays on your phone. sak has no servers, no accounts, no ads and no analytics.** The only exception is downloading content updates.

## Data sak uses on your phone

| Data | Why | Where it stays |
|---|---|---|
| App usage (which app is open, time per app, unlocks), through Android's **usage access** permission | Show your screen time, apply the limits and focus mode you set, and measure app habits | Only on your phone |
| List of installed apps (names and icons) | Let you pick apps to limit or block | Only on your phone |
| Your habits, their daily records, plans, weekly reviews, challenges, points and settings | The app's main features | Only on your phone |
| Your name or nickname and Sak's name, if you type them | Greetings | Only on your phone |

Before it opens Android's usage access screen, sak tells you what it reads and why, and asks you to continue. You can take the permission back at any time in Android's settings.

sak uses **display over other apps** to show Sak and the pause or block screen over other apps, and a **foreground service** to check limits and reminders during the day. Neither sends data anywhere.

Voice: when you tap the microphone, sak opens your phone's speech recognition service (for example Google's), which follows its own privacy policy and gives sak only the text. sak doesn't record audio. Spoken replies use your phone's text-to-speech engine.

QR challenge: the scanner is Google's code scanner, which runs through Google Play services. sak gets only the code's text and has no camera permission.

## Data that leaves your phone

1. **Content updates.** sak downloads a public file of tips and challenges (`catalog.json`) from GitHub over HTTPS. This sends no personal data, but GitHub sees your IP address, as with any web request.

sak doesn't sell or share your data, and doesn't use it for advertising.

## Backups and export

Android backup. sak allows Android's automatic backup, and its rules exclude only one file: the home-screen widget options (`widgets.xml`).
Everything else in sak's private storage is included, in both the Google backup (cloud) and the transfer to a new phone over cable or Wi-Fi (device-to-device), because the two sets of rules are identical.
That covers your habits and their records, your rules (limits and the apps you chose to limit or block, which are stored by app package name), reviews, the log of blocks you overrode, message budget, challenges, points, tips, and settings (including your name or nickname and Sak's name), plus the last crash report and the downloaded content cache.
Android's own app-usage history stays in Android and isn't part of sak's backup; only what sak itself saved is: for example the daily amount of an app habit, inside your habit records, and the last 28 days of each app's time, number of openings and longest stretch, which sak keeps on the phone for per-app statistics and includes in "Export my data".
The Google backup is stored by Google under your Google account, and Google's terms decide how it is protected and for how long; sak doesn't control it and doesn't see it.
A restore on a new phone brings this data back, but not the widget options, which you set up again.
You can turn Google backup off in Android's settings.
In Settings → "Export my data" you can save a JSON copy of everything sak stores, and "Import my data" reads that same file back from a place you pick (it replaces the data on the phone; nothing is sent anywhere).
If you choose a background picture (Settings → Appearance), sak keeps a small copy of it in its own private storage; it is not part of the exported file and is never sent anywhere, and sak asks for no access to your photos (the system picker hands over only the picture you pick). sak keeps the last crash on the phone (Settings → "Your data") and sends it nowhere unless you choose to share it.

## Deleting your data

Deleting a habit in the Today tab removes its records. Uninstalling sak, or clearing its storage in Android's settings, deletes all of its data from the phone. Since sak has no servers, there is nothing else to delete.

## Children

sak is not directed at children under 13.

## Changes

If this policy changes, the new version will be published at this address with a new date.

## Contact

Questions about privacy: <a href="mailto:miguel--castillo@outlook.es">miguel&#45;&#45;castillo@outlook.es</a>

---

<a id="es"></a>

# Política de privacidad de sak

*Última actualización: 18-11-2026*

sak es una app de bienestar digital: mide cómo usas el teléfono, te ayuda a poner límites a las apps y a seguir hábitos, y muestra una mascota, Sak, que te los recuerda. Esta política explica qué datos usa sak y adónde van.

**En resumen: todo lo que sak registra se queda en tu teléfono. sak no tiene servidores, cuentas, anuncios ni analíticas.** La única excepción es la descarga de actualizaciones de contenido.

## Datos que sak usa en tu teléfono

| Dato | Para qué | Dónde se queda |
|---|---|---|
| Uso de apps (qué app está abierta, tiempo por app, desbloqueos), con el permiso de **acceso al uso** de Android | Mostrar tu tiempo de pantalla, aplicar los límites y el modo foco que configures y medir los hábitos de apps | Solo en tu teléfono |
| Lista de apps instaladas (nombres e iconos) | Elegir qué apps limitar o bloquear | Solo en tu teléfono |
| Tus hábitos, sus registros diarios, planes, revisiones semanales, retos, puntos y ajustes | Las funciones principales de la app | Solo en tu teléfono |
| Tu nombre o apodo y el nombre de Sak, si los escribes | Saludos | Solo en tu teléfono |

Antes de abrir la pantalla de acceso al uso de Android, sak te dice qué lee y para qué, y te pide continuar. Puedes quitar el permiso cuando quieras en los ajustes de Android.

sak usa **mostrar sobre otras apps** para mostrar a Sak y la pantalla de pausa o bloqueo sobre otras apps, y un **servicio en primer plano** para revisar límites y recordatorios durante el día. Ninguno envía datos a ningún sitio.

Voz: al tocar el micrófono, sak abre el servicio de reconocimiento de voz de tu teléfono (por ejemplo, el de Google), que sigue su propia política de privacidad y solo le da el texto a sak. sak no graba audio. Las respuestas habladas usan el motor de texto a voz del teléfono.

Reto QR: el lector es el escáner de códigos de Google, que funciona con los servicios de Google Play. sak solo recibe el texto del código y no tiene permiso de cámara.

## Datos que salen de tu teléfono

1. **Actualizaciones de contenido.** sak descarga de GitHub, por HTTPS, un archivo público de consejos y retos (`catalog.json`). No se envían datos personales, pero GitHub ve tu dirección IP, como en cualquier solicitud web.

sak no vende ni comparte tus datos, y no los usa para publicidad.

## Copias de seguridad y exportación

Copia de seguridad de Android. sak permite la copia de seguridad automática de Android y sus reglas excluyen un solo archivo: las opciones de los widgets de la pantalla de inicio (`widgets.xml`).
Todo lo demás del almacenamiento privado de sak se incluye, tanto en la copia de Google (nube) como en la transferencia a un teléfono nuevo por cable o Wi-Fi (de dispositivo a dispositivo), porque las dos reglas son idénticas.
Eso abarca tus hábitos y sus registros, tus reglas (límites y las apps que elegiste limitar o bloquear, guardadas por nombre de paquete), revisiones, el registro de bloqueos que saltaste, presupuesto de mensajes, retos, puntos, consejos y ajustes (incluidos tu nombre o apodo y el nombre de Sak), además del último informe de fallo y la caché del contenido descargado.
El historial de uso de apps de Android se queda en Android y no forma parte de la copia de sak; solo va lo que sak guardó por su cuenta: por ejemplo la cantidad diaria de un hábito de app, dentro de tus registros de hábitos, y los últimos 28 días de tiempo, aperturas y rato más largo de cada app, que sak guarda en el teléfono para las estadísticas por app y que entra en "Exportar mis datos".
Google guarda la copia en tu cuenta de Google y sus condiciones deciden cómo se protege y durante cuánto tiempo; sak no la controla ni la ve.
Al restaurar en un teléfono nuevo vuelven estos datos, pero no las opciones de los widgets, que configuras de nuevo.
Puedes desactivar la copia de Google en los ajustes de Android.
En Ajustes → "Exportar mis datos" puedes guardar una copia en JSON de todo lo que sak almacena, y "Importar mis datos" lee ese mismo archivo desde un lugar que eliges (reemplaza los datos del teléfono; no se envía nada a ningún sitio). sak guarda el último fallo en el teléfono (Ajustes → "Tus datos") y no lo envía a ningún sitio salvo que tú elijas compartirlo.

## Borrar tus datos

Eliminar un hábito en la pestaña Hoy borra sus registros. Desinstalar sak, o borrar su almacenamiento en los ajustes de Android, elimina todos sus datos del teléfono. Como sak no tiene servidores, no hay nada más que borrar.

## Menores

sak no está dirigida a menores de 13 años.

## Cambios

Si esta política cambia, la nueva versión se publicará en esta dirección con una fecha nueva.

## Contacto

Preguntas sobre privacidad: <a href="mailto:miguel--castillo@outlook.es">miguel&#45;&#45;castillo@outlook.es</a>
