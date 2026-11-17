# Desktop Pals 배포

친구들끼리 화면 아래를 같이 돌아다니는 픽셀 캐릭터 앱의 **배포 전용** 저장소예요. 소스 코드는 여기 없어요.

**받기:** [맥 (DesktopPals.dmg)](https://github.com/ItzJoon/desktop-pals-releases/releases/latest/download/DesktopPals.dmg) · [윈도우 (DesktopPals-Windows.exe)](https://github.com/ItzJoon/desktop-pals-releases/releases/download/win-latest/DesktopPals-Windows.exe)

> 위쪽 **Tags** 목록에는 버전 이름과 소스 코드 압축 파일만 있어요(앱이 들어 있지 않아요). 앱은 위 링크나 **Releases**에서 받아요.

## 처음 설치 (맥)

1. [최신 릴리스](https://github.com/ItzJoon/desktop-pals-releases/releases/latest)에서 `DesktopPals.dmg`를 받아 열어요.
2. 창에 보이는 `DesktopPals` 앱을 옆의 **응용 프로그램** 폴더로 끌어다 놓아요.
3. 한 번 열어 보고, 막히면 **시스템 설정 → 개인정보 보호 및 보안**에서 **그래도 열기**를 눌러요.
   - 터미널이 편하면: `xattr -dr com.apple.quarantine /Applications/DesktopPals.app`

macOS 26 이상, Apple Silicon 맥이 필요해요.

## 처음 설치 (윈도우)

1. [DesktopPals-Windows.exe](https://github.com/ItzJoon/desktop-pals-releases/releases/download/win-latest/DesktopPals-Windows.exe)를 받아 실행해요.
2. "Windows의 PC 보호" 파란 창이 뜨면 **추가 정보 → 실행**을 눌러요(서명 없이 배포하는 앱이라 떠요).
3. 처음 한 번 스스로 설치되고, 시작 메뉴·바탕 화면에 **Desktop Pals** 바로 가기가 생겨요. 로그인할 때 자동으로 켜져요.

윈도우 10·11(64비트)에서 돌아가요. 아직 캐릭터 그리기·방 목록 같은 일부 기능은 맥에만 있어요.

## 업데이트

한 번 설치하면 새 버전은 **자동으로** 받아서 설치하고 다시 켜져요. 다시 받을 필요 없어요.
업데이트 파일은 만든 사람의 서명 키로 서명돼 있고, 앱이 서명을 확인한 뒤에만 설치해요.
