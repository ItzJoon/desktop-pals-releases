# Desktop Pals 배포

친구들끼리 맥 화면 아래를 같이 돌아다니는 픽셀 캐릭터 앱의 **배포 전용** 저장소예요. 소스 코드는 여기 없어요.

## 처음 설치

1. [최신 릴리스](https://github.com/ItzJoon/desktop-pals-releases/releases/latest)에서 `DesktopPals.dmg`를 받아 열어요.
2. 창에 보이는 `DesktopPals` 앱을 옆의 **응용 프로그램** 폴더로 끌어다 놓아요.
3. 한 번 열어 보고, 막히면 **시스템 설정 → 개인정보 보호 및 보안**에서 **그래도 열기**를 눌러요.
   - 터미널이 편하면: `xattr -dr com.apple.quarantine /Applications/DesktopPals.app`

macOS 26 이상, Apple Silicon 맥이 필요해요.

## 업데이트

한 번 설치하면 새 버전은 **자동으로** 받아서 설치하고 다시 켜져요. 다시 받을 필요 없어요.
업데이트 파일은 만든 사람의 서명 키로 서명돼 있고, 앱이 서명을 확인한 뒤에만 설치해요.
