# Navegador Via - A Melhor Escolha Geek

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | Português | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md)

### Introdução

O Navegador Via é um navegador poderoso com vários recursos, como ser

- Puro e sem anúncios;
- Altamente personalizável;
- Rápido como um raio;
- Pequeno, porém incrível 

Experimente-o e você não vai se arrepender nunca :)

[Baixar no Google Play (recomendado)](https://play.google.com/store/apps/details?id=mark.via.gp)

[Baixar a versão global](https://res.viayoo.com/v1/via-release.apk)

[Baixar a versão chinesa](https://www.coolapk.com/apk/mark.via)

### Nós ajude com as traduções!

Incentivamos todos a ajudar na tradução do navegador. Para fazer isso é bem simples:

1. Faça uma fork (burificação) deste repositório.
2. Copie o caminho `app/src/main/res/values/strings.xml` para `app/src/main/res/values-%(idioma)/`, substitua `%(idioma)` com [*o código de idioma ISO 639-1*](http://www.loc.gov/standards/iso639-2/php/code_list.php).
3. Traduza `app/src/main/res/values-%(idioma)/strings.xml`.
4. Faça uma Pull Request.


### FAQ

**Qual mecanismo de renderização que o Via usa?**

Via usa o renderizador WebView integrado e incluído na plataforma Android. Em dispositivos Android 5.0+ a implementação do WebView é geralmente chamada de `Android System WebView (com.google.android.webview)`, você pode atualizá-lo na Play Store para uma melhor experiência de navegação na web. Se você deseja saber a implementação e a versão atual do WebView do seu dispositivo, você ir em "Configurações > Sobre > Versão" no Via para ver as informações de depuração aonde contém as informações sobre o WebView.

**Como desativar o Javascript ou definir um agente de usuário (user-agent) especial para um site?**

Abra o site, clique na lupa ou ícone de escudo no lado esquerdo da barra de endereço e então você pode configurá-lo separadamente.

Ou vá em  "Configurações > Geral > Configurações do site" para mudar manualmente essa configuração.

**Eu não quero bloquear anúncios em um determinado site.**

Consulte a resposta anterior, você pode desativar o bloqueio de anúncios para o site desejado nas configurações do site.

**Por que o Via não salva senhas?**

Infelizmente, o Google removeu esse recurso específico do Webview. Você pode tentar usar o aplicativo de preenchimento automático (Bitwarden, Keepass, etc) se a versão Android do seu dispositivo for maior ou igual a versão 8 (Android Oreo).

**Por que o Via não consegue escanear códigos QR (QR Code)?**

Desde a versão 4.3.4, o navegador possui um _scanner_ de QR Code nativo. É so clicar no canto superior direito na página inicial.

**Como posso entrar em contato com você?**

Você pode entrar em contato comigo no [Twitter](https://twitter.com/Yafeng78600505) e eu responderei o mais rápido possível.

Você tambem pode [abrir um problema](https://github.com/tuyafeng/Via/issues/new) no GitHub, e eu irei verificar e responder às questões cerca de uma vez por semana.

Você tambem pode me enviar um email [aqui](mailto:yafengtu@gmail.com) se necessário, mas me desculpe se eu demorar para responder.
