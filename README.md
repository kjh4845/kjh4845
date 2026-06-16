# 김준형 / kjh4845

게임플레이 시스템, 스마트컨트랙트 서비스, 자동화 도구를 만들고 정리하고 있습니다.

학습용 저장소도 공개되어 있지만, 아래 세 프로젝트를 중심으로 봐주시면 됩니다.

## 대표 프로젝트

### Necrocis Gameplay

Unity 기반 2.5D 로그라이크 액션 게임 프로토타입입니다.

플레이어 전투, 성장, 적 AI, 보스 패턴, 바이옴 이동, UI 흐름처럼 게임플레이의 핵심 루프를 직접 구현했습니다. 코드와 문서를 포트폴리오용으로 다시 정리해 둔 저장소입니다.

- Stack: Unity, C#, URP, ScriptableObject
- Focus: gameplay architecture, enemy FSM, boss patterns, runtime pooling, player progression
- Repository: [necrocis-gameplay](https://github.com/kjh4845/necrocis-gameplay)

### WorkBridge Escrow

프리랜서 계약을 마일스톤 단위로 관리하는 에스크로 앱입니다.

클라이언트가 금액을 예치하고, 프리랜서가 작업물을 제출하며, 승인/분쟁/정산 흐름까지 이어지는 구조를 스마트컨트랙트와 프론트엔드로 구현했습니다.

- Stack: Solidity, TypeScript, React
- Focus: escrow contract flow, milestone lifecycle, dispute handling, frontend state flow
- Repository: [workbridge-escrow-app](https://github.com/kjh4845/workbridge-escrow-app)

### Coin Auto Trading

Binance Futures 기반 자동매매 실험 프로젝트입니다.

수익률을 앞세우는 저장소는 아닙니다. 거래소 데이터 수집부터 백테스트, 테스트넷/메인넷 런타임, 리스크 제한, 운영 대시보드까지 자동화 시스템으로 묶어본 작업입니다.

- Stack: Python, Binance Futures API, SQLite, unittest
- Focus: market data pipeline, backtest replay, risk controls, exchange state reconciliation, dashboard
- Repository: [coin-auto-trading](https://github.com/kjh4845/coin-auto-trading)

## 주로 쓰는 것들

- Languages: C#, TypeScript, Solidity, Python, Dart, C
- Game: Unity, URP, Unity UI, TextMesh Pro
- Web / App: React, Flutter, REST APIs
- Backend / Automation: Python CLI, async API integration, local runtime tools
- Blockchain: Solidity, Foundry-style contract testing, escrow flow design

## 작업할 때 신경 쓰는 것

- 기능이 실제 흐름 안에서 끝까지 동작하는지
- 런타임 상태와 실패 상황을 확인할 수 있는지
- 코드 구조가 나중에 다시 읽고 고치기 쉬운지
- README와 문서가 프로젝트 의도를 제대로 설명하는지
