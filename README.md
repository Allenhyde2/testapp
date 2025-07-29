# TestApp - Flutter 모바일 앱 프로젝트

## 📱 프로젝트 개요

TestApp은 Flutter를 사용하여 개발되는 크로스 플랫폼 모바일 애플리케이션입니다. 안드로이드와 iOS 플랫폼에서 동시에 실행될 수 있습니다.

## 🚀 개발 환경 설정

### 필수 요구사항

- **Flutter SDK**: 3.32.8 ✅ (설치 완료)
- **Dart**: Flutter와 함께 설치됨 ✅
- **Android Studio**: 2025.1 ✅ (설치 완료)
- **Xcode**: 16.4 ✅ (설치 완료)
- **CocoaPods**: 1.16.2 ✅ (설치 완료)
- **VS Code**: 1.95.3 ✅ (설치 완료)

### 설치 완료된 도구들 ✅

#### 1. Android Studio 설치 완료

- 버전: 2025.1
- 설치 경로: `/Applications/Android Studio.app`

#### 2. Xcode 설치 완료

- 버전: 16.4
- 설치 경로: `/Applications/Xcode.app`

#### 3. CocoaPods 설치 완료

- 버전: 1.16.2
- 설치 방법: `gem install cocoapods`

### 환경 설정 완료 후 실행 명령어

```bash
# Android SDK 설정
flutter config --android-sdk <ANDROID_SDK_PATH>

# Xcode 설정
sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
sudo xcodebuild -runFirstLaunch

# 의존성 설치
flutter pub get

# 앱 실행 (웹)
flutter run -d chrome

# 앱 실행 (Android)
flutter run -d android

# 앱 실행 (iOS)
flutter run -d ios
```

## 📋 개발 플랜

### Phase 1: 환경 설정 및 기본 구조 (완료)

- [x] Flutter SDK 설치
- [x] Flutter 프로젝트 생성
- [x] 기본 앱 구조 설정
- [x] Android Studio 설치 및 설정
- [x] Xcode 설치 및 설정
- [x] CocoaPods 설치
- [x] 개발 환경 검증

### Phase 2: 앱 아키텍처 설계 (예정)

- [ ] 상태 관리 솔루션 선택 (Provider/Riverpod/Bloc)
- [ ] 네비게이션 구조 설계
- [ ] API 통신 구조 설계
- [ ] 로컬 데이터베이스 설정 (SQLite/Hive)
- [ ] 테마 및 디자인 시스템 구축

### Phase 3: 핵심 기능 개발 (예정)

- [ ] 사용자 인증 시스템
- [ ] 메인 화면 구현
- [ ] 데이터 관리 기능
- [ ] 설정 화면
- [ ] 프로필 관리

### Phase 4: 고급 기능 및 최적화 (예정)

- [ ] 푸시 알림 구현
- [ ] 오프라인 모드 지원
- [ ] 성능 최적화
- [ ] 보안 강화
- [ ] 접근성 개선

### Phase 5: 테스트 및 배포 (예정)

- [ ] 단위 테스트 작성
- [ ] 위젯 테스트 작성
- [ ] 통합 테스트
- [ ] 앱 스토어 배포 준비
- [ ] Google Play Store 배포 준비

## 🛠 기술 스택

### 프레임워크

- **Flutter**: 크로스 플랫폼 UI 프레임워크
- **Dart**: 프로그래밍 언어

### 상태 관리 (선택 예정)

- Provider / Riverpod / Bloc

### 데이터베이스

- SQLite (로컬 데이터)
- Hive (캐싱)

### 네트워킹

- HTTP/Dio (API 통신)
- WebSocket (실시간 통신)

### 인증

- Firebase Auth (예정)

### 알림

- Firebase Cloud Messaging (예정)

## 📁 프로젝트 구조

```
testapp/
├── android/          # Android 플랫폼 코드
├── ios/             # iOS 플랫폼 코드
├── lib/             # Dart 소스 코드
│   ├── main.dart    # 앱 진입점
│   ├── models/      # 데이터 모델
│   ├── screens/     # 화면 위젯
│   ├── widgets/     # 재사용 가능한 위젯
│   ├── services/    # 비즈니스 로직
│   ├── utils/       # 유틸리티 함수
│   └── constants/   # 상수 정의
├── test/            # 테스트 코드
├── assets/          # 이미지, 폰트 등 리소스
└── pubspec.yaml     # 의존성 관리
```

## 🎯 현재 상태 및 다음 단계

### ✅ 완료된 작업

- **Phase 1 완료**: 모든 개발 환경이 설정되었습니다!
- **지원 플랫폼**: 웹, iOS, macOS, Android (cmdline-tools 설치 후)

### 🚀 다음 단계

1. **앱 스펙 정의**: 구체적인 앱 기능과 요구사항을 정의
2. **UI/UX 디자인**: 앱의 디자인 시스템과 사용자 경험 설계
3. **데이터 모델 설계**: 앱에서 사용할 데이터 구조 정의
4. **API 설계**: 백엔드 API 구조 및 엔드포인트 정의

### 🧪 현재 테스트 가능한 환경

```bash
# 웹에서 테스트
flutter run -d chrome

# iOS 시뮬레이터에서 테스트
flutter run -d ios

# macOS에서 테스트
flutter run -d macos
```

## 📞 문의

프로젝트 관련 문의사항이 있으시면 언제든지 연락주세요.

---

**참고 링크:**

- [Flutter 공식 문서](https://docs.flutter.dev/)
- [Dart 언어 가이드](https://dart.dev/guides)
- [Flutter 패키지 저장소](https://pub.dev/)
