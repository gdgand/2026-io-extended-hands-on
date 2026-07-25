# 2026 I/O Extended · Android App Functions Hands-on

GDG Korea Android 핸즈온 세션 — Android의 새로운 **App Functions** API로
내 앱의 기능을 AI Agent에게 열어주는 방법을 직접 다뤄봅니다.

## 📽️ 발표 슬라이드

### 👉 **https://gdgand.github.io/2026-io-extended-hands-on**

- ⌨️ **조작**: `←` `→` / Space 이동 · `F` 전체화면 · 화면 좌측 25% 클릭 시 이전 슬라이드

## App Functions 란?

앱의 핵심 기능(메시지 보내기, 할일 추가, 연락처 검색 등)을 Kotlin 함수에
`@AppFunction` 어노테이션을 붙이는 것만으로 **시스템과 AI 에이전트가 호출할 수 있는
함수로 공개**하는 Android API입니다. KDoc이 그대로 에이전트에게 전달되는 함수 명세가 됩니다.

- 공식 문서: https://developer.android.com/ai/appfunctions

## 학습 목표

1. **이해** — App Function의 개념과 동작 원리
2. **구현** — 내 프로젝트에 App Function 추가하기 (의존성 · 서비스 · 어노테이션)
3. **검증** — `adb` 직접 호출과 Testing Agent로 동작 테스트

## 진행 순서

| 섹션 | 내용 |
|------|------|
| **1. 실습 환경 세팅** | Android CLI 설치 · SDK 36 에뮬레이터 생성 |
| **2. App Function 개요** | 정의 · 사용 사례 · 작동 방식 · 주요 어노테이션 · 프로젝트에 추가 |
| **3. 실습** | 공식 샘플 실행 → 내 앱에 구현 → 발표 & 시상 🏆 |

## 실습 준비물

| 항목 | 요구사항 |
|------|----------|
| Android Studio | 최신 안정 버전 |
| compileSdk / 디바이스 | **API 36 이상** (App Functions는 API 36+ 에서만 동작) |
| 공식 샘플 | `git clone https://github.com/android/appfunctions.git` |

## 참고 자료

- [App Functions 개발자 가이드](https://developer.android.com/ai/appfunctions)
- [앱에 App Functions 추가하기](https://developer.android.com/ai/appfunctions/add-appfunctions)
- [공식 샘플 (android/appfunctions)](https://github.com/android/appfunctions)
- [App Functions Skill](https://github.com/android/skills/blob/main/device-ai/appfunctions/SKILL.md)
- [Android CLI](https://developer.android.com/tools/agents/android-cli)

---

발표: 류기민 · GDG Korea Android Organizer · 2026 Google I/O Extended
