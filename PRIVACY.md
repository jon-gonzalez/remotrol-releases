[Español](#es) · [English](#en)

<a id="es"></a>

# Política de privacidad de Remotrol

Última actualización: 16 de noviembre de 2026

Esta política explica qué hacen con tus datos Remotrol, la app del iPhone y el iPad, y Remotrol Mac, la app del Mac (juntas, «Remotrol»). El responsable es Jon González, el autor de Remotrol.

## En resumen

Remotrol no recoge datos personales. No tiene servidores, ni cuentas, ni publicidad, ni analítica, ni seguimiento. Todo lo que maneja se queda en tus dispositivos o viaja, cifrado, entre tu iPhone o iPad y tu Mac por tu red local. El autor no recibe nada.

## Qué se guarda en tus dispositivos

En el iPhone o el iPad:

- tus ajustes y la configuración de los botones, incluidas las imágenes que les pongas;
- la clave de vinculación con el Mac, en el llavero;
- si activas el desbloqueo del Mac, una llave creada dentro del Secure Enclave, que solo se usa tras pasar Face ID o Touch ID y no sale nunca del dispositivo;
- los iconos de las apps del Mac que te enseña la app.

En el Mac:

- tus ajustes, los scripts que añadas al lanzador y la clave de vinculación (en el llavero);
- un registro de los últimos pasos de tus sesiones de Claude Code, para la vista de actividad del iPhone (`~/Library/Application Support/Remotrol`);
- si activas el desbloqueo con Face ID o Touch ID, la contraseña de tu usuario y la llave pública del iPhone o el iPad, en el llavero del Mac. La contraseña la escribes en el Mac y nunca sale de él;
- si conectas Claude Code, unos hooks en `~/.claude/settings.json` (con una copia de seguridad del archivo anterior).

## Qué viaja entre el iPhone o el iPad y el Mac

Para que funcione, tu iPhone o iPad y tu Mac se mandan, solo por tu red local y cifrado con la clave del código QR: las teclas y los gestos que pulsas, el texto que dictas o escribes, los nombres de las apps, ventanas y sesiones abiertas en el Mac, lo que piden tus sesiones de Claude Code (por ejemplo, un comando o un archivo) y tus respuestas, palabras de tu proyecto para mejorar el dictado, y las firmas del desbloqueo. Nada de eso pasa por internet ni llega al autor.

## Permisos

- **Micrófono y reconocimiento de voz:** para dictar. La voz se convierte en texto con el reconocimiento de voz de Apple: en el propio iPhone o iPad siempre que el dispositivo y el idioma lo permiten y, si no, en los servidores de Apple, según su política de privacidad. Remotrol no guarda el audio. Si activas «Repasar el texto», se hace con el modelo de Apple que funciona en el dispositivo.
- **Cámara:** solo para leer el código QR del Mac. No se guarda ninguna imagen.
- **Face ID o Touch ID:** para usar la llave que desbloquea el Mac. Lo gestiona iOS; Remotrol nunca ve tu cara ni tu huella.
- **Red local:** para encontrar el Mac y hablar con él.
- **Accesibilidad y Automatización (Mac):** para pulsar teclas, escribir y poner delante la ventana o la pestaña adecuada.

## Servicios de terceros

- **Apple:** distribuye la app del iPhone y el iPad por la App Store. Si en tu dispositivo has aceptado compartir datos de análisis con los desarrolladores, Apple puede pasar al autor informes de fallos y estadísticas de uso agregadas y anónimas. Se rige por la política de privacidad de Apple.
- **GitHub:** Remotrol Mac se descarga de GitHub y busca actualizaciones allí una vez al día. GitHub recibe, como en cualquier visita, la dirección IP y los datos técnicos de la petición; Remotrol no le manda nada más. Se rige por la política de privacidad de GitHub.

## Menores

Remotrol no está dirigida a menores de 14 años y no recoge datos de nadie.

## Borrar tus datos

Como el autor no tiene datos tuyos, no hay nada que pedirle que borre. Para borrar lo que hay en tus dispositivos: desinstala la app del iPhone o el iPad; en el Mac, desactiva el desbloqueo (menú de Remotrol) y desvincula el dispositivo (Ajustes de Remotrol Mac), quita de `~/.claude/settings.json` los hooks de Remotrol, y borra la app y la carpeta `~/Library/Application Support/Remotrol`.

## Cambios

Si esta política cambia, la versión nueva se publicará en esta misma dirección, con la fecha de la última actualización, y llegará también con la siguiente versión de las apps.

## Contacto

Para cualquier pregunta sobre esta política o tus datos: https://github.com/jon-gonzalez/remotrol-releases/issues

---

<a id="en"></a>

# Remotrol Privacy Policy

Last updated: November 16, 2026

This policy explains what Remotrol, the iPhone and iPad app, and Remotrol Mac, the Mac app (together, "Remotrol"), do with your data. The controller is Jon González, Remotrol's author.

## In short

Remotrol doesn't collect personal data. It has no servers, accounts, ads, analytics or tracking. Everything it handles stays on your devices or travels, encrypted, between your iPhone or iPad and your Mac over your local network. The author receives nothing.

## What's stored on your devices

On the iPhone or iPad:

- your settings and button setup, including any images you add to them;
- the pairing key for the Mac, in the keychain;
- if you turn on unlocking the Mac, a key created inside the Secure Enclave, which is only used after passing Face ID or Touch ID and never leaves the device;
- the icons of the Mac apps the app shows you.

On the Mac:

- your settings, the scripts you add to the launcher and the pairing key (in the keychain);
- a log of the latest steps of your Claude Code sessions, for the iPhone's activity view (`~/Library/Application Support/Remotrol`);
- if you turn on unlocking with Face ID or Touch ID, your user password and the iPhone's or iPad's public key, in the Mac's keychain. You type the password on the Mac and it never leaves it;
- if you connect Claude Code, a few hooks in `~/.claude/settings.json` (with a backup of the previous file).

## What travels between the iPhone or iPad and the Mac

To work, your iPhone or iPad and your Mac send each other, only over your local network and encrypted with the key in the QR code: the keys and gestures you press, the text you dictate or type, the names of the apps, windows and sessions open on the Mac, what your Claude Code sessions request (for example, a command or a file) and your answers, words from your project to improve dictation, and the unlock signatures. None of it goes over the internet or reaches the author.

## Permissions

- **Microphone and speech recognition:** to dictate. Speech is turned into text with Apple's speech recognition: on the iPhone or iPad itself whenever the device and language allow it and, otherwise, on Apple's servers, under Apple's privacy policy. Remotrol doesn't store the audio. If you turn on "Polish the text", it uses Apple's on-device model.
- **Camera:** only to read the Mac's QR code. No image is stored.
- **Face ID or Touch ID:** to use the key that unlocks the Mac. iOS handles it; Remotrol never sees your face or fingerprint.
- **Local network:** to find the Mac and talk to it.
- **Accessibility and Automation (Mac):** to press keys, type and bring the right window or tab to the front.

## Third-party services

- **Apple:** distributes the iPhone and iPad app through the App Store. If you've agreed on your device to share analytics with developers, Apple may give the author crash reports and aggregated, anonymous usage statistics. Apple's privacy policy applies.
- **GitHub:** Remotrol Mac is downloaded from GitHub and checks there for updates once a day. As with any visit, GitHub receives the IP address and the request's technical data; Remotrol sends it nothing else. GitHub's privacy policy applies.

## Children

Remotrol isn't directed at children under 14 and doesn't collect anyone's data.

## Deleting your data

Since the author has no data of yours, there's nothing to ask them to delete. To delete what's on your devices: uninstall the iPhone or iPad app; on the Mac, turn off unlocking (Remotrol menu) and unpair the device (Remotrol Mac Settings), remove Remotrol's hooks from `~/.claude/settings.json`, and delete the app and the `~/Library/Application Support/Remotrol` folder.

## Changes

If this policy changes, the new version will be published at this same address, with the last-updated date, and will also come with the next version of the apps.

## Contact

For any question about this policy or your data: https://github.com/jon-gonzalez/remotrol-releases/issues
