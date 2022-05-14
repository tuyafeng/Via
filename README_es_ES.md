# Via Browser - La Mejor Opción del Geek

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | Español | [Türkçe](./README_tr_TR.md)

### Introducción

Via Browser es un poderoso navegador que cuenta con las siguientes características:

- Puro y sin publicidad
- Altamente personalizable
- Veloz como un relámpago
- Pequeño, pero asombroso

Pruébalo y jamás te arrepentirás :)

[Consíguelo en Google Play](https://play.google.com/store/apps/details?id=mark.via.gp)

[Descarga la versión global](https://res.viayoo.com/v1/via-release.apk)

[Descarga la versión china](https://res.viayoo.com/v1/via-release-cn.apk)

### Ayuda con la localización

Alentamos a todo el mundo a ayudarnos con la localización/traducción. A continuación se explica cómo:

1. Crea un fork de este repositorio
2. Copia el archivo `app/src/main/res/values/strings.xml` y cambia su dirección a `app/src/main/res/values-%(lang)/`, reemplaza `%(lang)` con [*el código ISO 639-1 del lenguaje al que traducirás todo*](http://www.loc.gov/standards/iso639-2/php/code_list.php)
3. Traduce el archivo `app/src/main/res/values-%(lang)/strings.xml`
4. Crea una pull request

### Preguntas Frecuentes

**¿Qué motor de renderizado utiliza Via?**

Via utiliza el procesador WebView integrado en la plataforma Android. En dispositivos Android 5.0+, la implementación de WebView usualmente es `Android System WebView (com.google.android.webview)`, puedes actualizarla en la Play Store para una mejor experiencia de navegación. Si quieres saber cuál es la implementación actual de WebView y la versión de tu dispositivo, en Via puedes ir a "Ajustes - Acerca de" y presionar el logo de Via para ver la información de depuración, la cual contiene la información de WebView.

**¿Cómo se desactiva el JavaScript o se ajusta un agente de usuario para un sitio en específico?**

Abre el sitio, presiona la lupa/ícono de escudo a la izquierda de la barra del navegador y en "Configuración del sitio" puedes hacer los ajustes para la página.

O abre "Ajustes - General - Configuración del sitio" para realizar la configuración manualmente.

**No quiero bloquear publicidad en un sitio específico.**

Por favor dirigirse a la pregunta anterior. Puedes desactivar el adblock para el sitio en "Configuración del sitio".

**¿Por qué Via no guardar contraseñas?**

Desafortunadamente, Google removió esta función de WebView en particular. Puedes intentar utilizar aplicaciones con auto-rellenado (Bitwarden, KeePass, etc.) si la versión de Android de tu dispositivo es mayor o igual a 8.0.

**¿Por qué Via no escanea códigos QR?**

Hay muchas aplicaciones que escanean códigos QR y no quiero agregar una función tan repetitiva. Puedes escanear el código QR con la aplicación de cámara de tu teléfono.

**¿Cómo puedo contactarte?**

Puedes contactarme en [Twitter](https://twitter.com/Yafeng78600505) y responderé tan pronto como sea posible.

También puedes [abrir una issue](https://github.com/tuyafeng/Via/issues/new) en GitHub, chequearé y responderé a las issues más o menos una vez a la semana.

Puedes escribirme un correo [aquí](mailto:yafengtu@gmail.com) si lo amerita, pero lamentablemente puede que no responda.

