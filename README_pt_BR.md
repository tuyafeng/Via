# Via Browser - A Melhor Escolha do Geek

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | Português | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | [日本語](./README_ja_JP.md) | [Русский](./README_ru_RU.md) | [العربية](./README_ar_AR.md) | [বাংলা](./README_bn_IN.md) | [한국어](./README_ko_KR.md)

### Introdução

Via Browser é um navegador poderoso com os seguintes recursos:

- Puro e sem anúncios
- Altamente personalizável
- Rápido como um raio
- Pequeno, mas incrível

Teste e você nunca se arrependera :)

[Baixar do Google Play](https://play.google.com/store/apps/details?id=mark.via.gp)

[Baixar Versão Global](https://res.viayoo.com/v1/via-release.apk)

[Baixar Versão Chinesa](https://res.viayoo.com/v1/via-release-cn.apk)

### Ajude com a localização

Encorajamos todos a ajudar com a localização. A seguir está como fazer isso.

1. Faça um fork deste repositório
2. Copie `app/src/main/res/values/strings.xml` para um caminho como `app/src/main/res/values-%(lang)/`, substitua `%(lang)` pelo [*código de idioma ISO 639-1*](http://www.loc.gov/standards/iso639-2/php/code_list.php)
3. Traduza `app/src/main/res/values-%(lang)/strings.xml`
4. Faça um Pull Request

### FAQ

**Qual mecanismo de renderização o Via usa?**

Via usa o renderizador WebView integrado incluído na plataforma Android. Em dispositivos com Android 5.0+, a implementação do WebView geralmente é `Android System WebView (com.google.android.webview)`, você pode atualizá-lo na Play Store para uma melhor experiência de navegação. Se você quiser saber a implementação atual do WebView e versão do seu dispositivo, você pode clicar em "Configurações - Sobre" no Via e tocar no logotipo do Via para obter informações de depuração que contêm as informações do WebView.

**Como desativar JavaScript ou definir um agente de usuário especial para um site?**

Abra o site, clique no ícone da lupa ou escudo no lado esquerdo da barra de endereços, e então você pode configurá-lo separadamente.

Ou abra "Configurações-Geral-Configuração do Site" para adicionar configuração manualmente.

**Não quero bloquear anúncios em um determinado site.**

Consulte a pergunta anterior, você pode desativar o bloqueio de anúncios do site na configuração do site.

**Por que o Via não consegue salvar a senha?**

Infelizmente, o Google removeu este recurso específico do WebView. Você pode tentar usar o aplicativo de preenchimento automático (Bitwarden, KeePass, etc.) se a versão do Android do seu dispositivo for maior ou igual a 8.0.

**Por que o Via não consegue escanear o código QR?**

~~Existem muitos aplicativos que conseguem escanear códigos QR, e eu não quero adicionar uma função tão repetitiva. Você pode escanear o código QR com o aplicativo de câmera do seu telefone.~~

A partir da versão 4.3.4, Via adicionou um scanner de código QR integrado.

**Como entrar em contato com você?**

Você pode entrar em contato comigo no [Twitter](https://twitter.com/Yafeng78600505) e responderei o mais rápido possível.

Você também pode [abrir um problema](https://github.com/tuyafeng/Via/issues/new) no GitHub, e verificarei e responderei aos problemas aproximadamente uma vez por semana.

Você pode me enviar um e-mail [aqui](mailto:yafengtu@gmail.com) se necessário, mas peço desculpas por não poder responder.
