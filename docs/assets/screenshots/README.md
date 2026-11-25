# 와글와글 화면 캡처

포트폴리오·README·발표 자료에서 재사용할 수 있도록 목업 API 기준의 주요 사용자 흐름을 390×844 모바일 화면으로 개별 캡처한 자료.

## 1. 로그인·온보딩

| 로그인 | 기본 정보 | 닉네임 |
|---|---|---|
| <img src="01-login.png" width="240" alt="로그인"> | <img src="02-onboarding-profile.png" width="240" alt="연령대와 성별 선택"> | <img src="03-onboarding-nickname.png" width="240" alt="닉네임 입력"> |

| 닉네임 중복 확인 | 선호 장소 선택 | 선호 순위 선택 완료 |
|---|---|---|
| <img src="04-onboarding-nickname-checked.png" width="240" alt="닉네임 중복 확인 완료"> | <img src="05-onboarding-preferences.png" width="240" alt="선호 장소 선택"> | <img src="06-onboarding-preferences-selected.png" width="240" alt="선호 장소 선택 완료"> |

## 2. 홈·검색·장소

| 지도 홈 | 최근 검색 | 검색 결과 |
|---|---|---|
| <img src="07-home.png" width="240" alt="지도 홈과 주변 장소"> | <img src="08-search-recent.png" width="240" alt="최근 검색"> | <img src="09-search-results.png" width="240" alt="태그와 장소 검색 결과"> |

| 장소 상세·요일별 혼잡도 |
|---|
| <img src="10-place-detail.png" width="240" alt="장소 상세와 실시간 영상핀"> |

## 3. 영상핀 열람

| 결제 전 잠금 | 영상 열기 준비 | 결제 확인 |
|---|---|---|
| <img src="11-pin-locked.png" width="240" alt="결제 전 블러 영상핀"> | <img src="12-pin-unlock-loading.png" width="240" alt="영상 열기 로딩"> | <img src="13-pin-payment-confirmation.png" width="240" alt="와글 포인트 결제 확인"> |

| 결제 후 영상·평가·채팅 |
|---|
| <img src="14-pin-unlocked.png" width="240" alt="영상핀 잠금 해제와 평가"> |

## 4. 추천·제보

| 여유로운 장소 추천 | 북적이는 장소 추천 | 핀 제보 작성 |
|---|---|---|
| <img src="15-recommend-relaxed.png" width="240" alt="여유로운 장소 추천"> | <img src="16-recommend-busy.png" width="240" alt="북적이는 장소 추천"> | <img src="19-write-entry.png" width="240" alt="영상핀 제보 작성"> |

## 5. 실시간 채팅·AI 위험 감지

| 요청한 대화 | 요청받은 대화 | 핀별 채팅 요청 |
|---|---|---|
| <img src="17-chat-sent.png" width="240" alt="요청한 채팅 목록"> | <img src="18-chat-received.png" width="240" alt="요청받은 채팅 목록"> | <img src="21-chat-pin-requests.png" width="240" alt="핀별 채팅 요청 수락과 거절"> |

| 채팅방·누적 안전 경고 |
|---|
| <img src="22-chat-room-warning.png" width="240" alt="AI 위험 감지 누적 경고가 있는 채팅방"> |

## 6. 마이페이지

| 신뢰도·활동 대시보드 | 오늘 작성한 핀 | 와글 포인트 내역 |
|---|---|---|
| <img src="20-mypage.png" width="240" alt="마이페이지 활동 대시보드"> | <img src="23-my-today-pins.png" width="240" alt="오늘 작성한 핀 목록"> | <img src="24-my-credits.png" width="240" alt="와글 포인트 사용과 적립 내역"> |

| 닉네임·선호 지역 수정 |
|---|
| <img src="25-profile-edit.png" width="240" alt="내 정보 수정"> |

## 캡처 기준

- 해상도: 390×844
- 데이터: `EXPO_PUBLIC_USE_MOCK_API=true`의 고정 목업 시나리오
- 캡처 범위: 로그인 → 온보딩 → 지도 탐색 → 영상핀 결제 → 추천·채팅·제보 → 마이페이지
- 캡처일: 2026-11-25
