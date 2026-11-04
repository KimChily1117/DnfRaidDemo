# DnfRaidDemo

던전앤파이터의 레이드를 소재로 만든 Unity 2인 협동 액션 데모입니다. 개인 학습 프로젝트로 판매하거나 배포하지 않습니다.

호스트 권한 방식의 UDP 통신을 사용하며, 기본 3타, 스킬, 회피와 점프, 보스 패턴 6종, 페이즈와 무력화를 구현했습니다. 이후 [ProjectDawn](https://github.com/KimChily1117/ProjectDawn)의 1~4인 서버 검증 구조로 확장했습니다.

## 구성

| 파일 | 내용 |
|---|---|
| `RaidSimulation` | 전투 규칙 |
| `RaidNetwork` | 2인 UDP 통신 |
| `RaidMotion` | 모션 상태 전환 |
| `RaidDemoApp` | 입력, 표시, 게임 흐름 |
| `RaidShowcase` | 보스 패턴 시연 |

## 참고

- 소스 코드만 공개합니다. 리소스, 도구, 테스트는 포함하지 않아 이 저장소만으로는 빌드되지 않습니다.
