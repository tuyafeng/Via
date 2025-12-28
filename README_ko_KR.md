# Via 브라우저 - 긱(Geek)을 위한 최고의 선택

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

English | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | [日本語](./README_ja_JP.md) | [Русский](./README_ru_RU.md) | [العربية](./README_ar_AR.md) | [한국어](./README_ko_KR.md)

### 소개

Via 브라우저는 다음과 같은 특징을 가진 강력한 브라우저입니다:

- 광고 없는 깔끔함
- 높은 자유도의 커스터마이징
- 번개처럼 빠른 속도
- 작지만 강력한 성능

한번 사용해보시면 절대 후회하지 않으실 겁니다 :)

[Google Play에서 다운로드하기](https://play.google.com/store/apps/details?id=mark.via.gp)

[글로벌 버전 다운로드](https://res.viayoo.com/v1/via-release.apk)

[중국 버전 다운로드](https://res.viayoo.com/v1/via-release-cn.apk)

### 현지화에 참여하기

누구나 현지화 작업에 참여하는 것을 환영합니다. 참여 방법은 다음과 같습니다.

1. 이 저장소를 포크(Fork)하세요.
2. `app/src/main/res/values/strings.xml` 파일을 `app/src/main/res/values-%(lang)/` 와 같은 경로에 복사하세요. `%(lang)` 부분은 [*ISO 639-1 언어 코드*](http://www.loc.gov/standards/iso639-2/php/code_list.php)로 변경해주세요.
3. `app/src/main/res/values-%(lang)/strings.xml` 파일의 내용을 번역하세요.
4. 풀 리퀘스트(Pull Request)를 보내주세요.

### 자주 묻는 질문 (FAQ)

**Via는 어떤 렌더링 엔진을 사용하나요?**

Via는 안드로이드 플랫폼에 내장된 WebView 렌더러를 사용합니다. 안드로이드 5.0 이상 기기에서는 보통 `Android System WebView (com.google.android.webview)` 가 WebView 구현체이며, 더 나은 브라우징 경험을 위해 Play 스토어에서 업데이트할 수 있습니다. 사용 중인 기기의 현재 WebView 구현체와 버전을 알고 싶다면, Via 브라우저의 "설정 - 정보"에서 Via 로고를 탭하여 디버깅 정보를 확인하세요. 여기에 WebView 정보가 포함되어 있습니다.

**특정 웹사이트에서 자바스크립트를 비활성화하거나 특별한 사용자 에이전트(User Agent)를 설정하려면 어떻게 하나요?**

해당 사이트를 연 후, 주소창 왼쪽에 있는 돋보기 또는 방패 모양 아이콘을 클릭하여 개별적으로 설정할 수 있습니다.

또는 "설정 - 일반 - 사이트 설정"을 열어 수동으로 설정을 추가할 수도 있습니다.

**특정 사이트에서는 광고를 차단하고 싶지 않아요.**

이전 질문을 참고하여 사이트 설정에서 해당 사이트의 광고 차단 기능을 끌 수 있습니다.

**Via는 왜 비밀번호를 저장할 수 없나요?**

안타깝게도 구글이 WebView에서 이 특정 기능을 제거했습니다. 기기의 안드로이드 버전이 8.0 이상이라면 자동 완성 앱(Bitwarden, KeePass 등)을 사용하는 것을 시도해볼 수 있습니다.

**Via는 왜 QR 코드를 스캔할 수 없나요?**

~~이미 QR 코드를 스캔할 수 있는 애플리케이션이 너무 많아서 중복되는 기능을 추가하고 싶지 않았습니다. 휴대폰의 카메라 앱으로 QR 코드를 스캔할 수 있습니다.~~

버전 4.3.4부터 Via에 내장 QR 코드 스캐너가 추가되었습니다.

**어떻게 연락할 수 있나요?**

[Twitter](https://twitter.com/Yafeng78600505) 로 연락 주시면 가능한 한 빨리 답변해 드리겠습니다.

GitHub에서 [이슈를 등록](https://github.com/tuyafeng/Via/issues/new)할 수도 있습니다. 이슈는 일주일에 한 번 정도 확인하고 답변합니다.

꼭 필요한 경우 [이곳](mailto:yafengtu@gmail.com)으로 이메일을 보낼 수 있지만, 답장을 못 드릴 수도 있는 점 양해 바랍니다.

