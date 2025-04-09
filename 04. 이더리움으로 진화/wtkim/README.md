# 4장 이더리움으로 진화

### 비트코인의 제한된 기능 개선

비트코인은 스트립트 머니의 개념을 적용한 최초의 탈중앙화 합의 프로토콜이다. 제한된 기능성으로 인해 스크립트된 화폐 정도로만 봤지만, 시간이 지나며 더 많은 가치를 가진 저장 수단으로 보기 시작했다.

**컬러드 코인과 토큰**

**컬러드 코인** 은 새로운 **토큰** 을 생성하고 비트코인 네트워크에서 자산을 이동해야 하는 필요성으로 인해 탄생했다. 이러한 토큰은 주식이나 금과 같은 실제 자산을 비트코인 블록체인에 표현하고 관리할 수 있게 한다.

**마스터코인과 스마트 콘트랙트**

2013년, **마스터코인** 은 비트코인을 확장하여 기초적인 **스마트 콘트랙트** 를 제공하는 **오버레이 프로토콜** 로써 탄생했다. 마스터코인의 개발로 인해 비트코인은 프로그래밍 가능한 돈의 개념으로 발전했다.

**옴니레이어의 이해**

2013년 마스터코인 프로젝트는 옴니레이어로 이름을 변경했다. 옴니레이어는 옴니코어로 알려진 참조 구현체와 함께 진행 중인 프로젝트다.

옴니코어는 스마트 콘트랙트 기능을 제공해 개발자가 화폐 기능을 자동화 할수 있게 했다. 스마트 콘트랙으로 블록체인 상에서 트랜잭션과 합의를 실행해 통화 이외의 기능을 수행할 수 있다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/07062baa-637d-409b-8186-76c1f887fb3d" />
</p>

- **옴니레이어의 기능**
    - 관세
        - 옴니레이어 네트워크에서 관리되는 원장에서 누구나 화폐를 만들 수 있다.
    - 탈중앙화 거래소
        - 교환을 위해 중앙 집중화 거래소를 사용하는 대신, 트레이드 코드를 실행한다.
- **테더(Tether)**
    - 디지털 블록체인 암호화폐와 미 달러화에 고정된 안정적인 통화를 제공하는 목표로 탄생했다. (1 Tether = 1 USD)
    - 미국 달러화에 대한 1:1 고정에 관해 전면적인 감사를 약속했으나 실제로 그만한 천문학적인 달러를 예치하고 있을리가 없기 때문에 신뢰성에 문제가 제기되었다.
    - 옴니레이어의 토큰화를 위한 첫 사용 사례로, 실험적인 성향이 강하다.

옴니레이어는 메타데이터를 포함하는 비트코인 트랜잭션이다. 유일한 차이점은, OP_RETURN 필드의 유무이다. 옴니 트랜잭션은 이 OP_RETURN 의 데이터를 기반으로 USDT 트랜잭션을 해석한다.

- OP_RETURN 속성
    - 비트코인 원장에 Output 중의 하나로 기록되며, 거래로 사용될 수 없기 때문에 금액이 항상 0 이다.
- Tether 트랜잭션 메타데이터 해석
    - `6f6d6e69000000000000001f000000001dcd6500` 16진수를 ASCII / 10진법으로 해석하면
    - `6f6d6e69` - omni (옴니 트랜잭션임을 확인)
    - `00000000` - Simple send (트랜잭션 유형)
    - `0000001f` - 31 (USDT 속성)
    - `000000001dcd6500` - 5.00000000 Amount (옴니 트랜잭션은 소수점 8자리가 항상 있다)

### 이더리움

2013 년 비탈릭 부테린이 마스터코인의 기능을 확장하기 위한 방안을 생각하면서 탄생했다. 비탈릭은 **튜링 완전한 범용 블록체인** 으로써 이더리움을 설명하는 백서를 설명했다.

이더리움에서 계정 단위는 **이더(Ether)** 이고, **가스(Gas)** 라는 계정 단위도 있다.

**이더리움의 특징**

- 비트코인 네트워크보다 컨펌 시간이 훨씬 빠르고, 전송 매커니즘도 빠르다.
- UTXO 방식과 달리, 이더리움은 **계좌 상태의 잔액** 을 추적한다.
- 애플리케이션 기반 트랜잭션을 만들 수 있고, 가스는 개발자들이 이더리움 플랫폼에서 애플리케이션을 실행할 수 있게 한다. 이 앱은 일반적으로 **DApp** 으로 알려져 있다.

**사용 사례: ICO(Initial Coin Offering)**

스마트 콘트랙트를 활용한 전산 거래 프로토콜의 사용 사례로 ICO 가 있다. ICO 는 주식이 아닌 코인으로 IPO 를 하는 것과 비슷한 개념이다. 이더리움은 ICO 를 통해 42일 만에 31,000 BTC 를 모금했다. ICO 당시 이더리움의 가격은 0.31 달러였는데, 출시 1년 후 10 달러로 오르며 크게 성공했다. 이더리움의 성공은 ICO 를 블록체인 사업의 표준으로 만들었다. 이를 시작으로 암호화폐가 다양한 거래에 사용될 수 있다는 것을 증명한 계기가 되었다.

**탈중앙화된 자율 조직**

이더리움 생태계에서 탈중앙화의 기풍을 한 단계 높이기 위해 중앙집중화된 당국의 거버넌스를 대체할 스마트 콘트랙트를 활용할 방안으로 탈중앙화된 자율 조직(DAO) 개념을 제시했다. DAO 에서 투자자는 구매한 토큰의 오너십에 상응하는 의결권을 갖는다.

DAO 의 출시 후, 스마트 콘트랙트 코드에서 재귀 호출 취약성 문제로 5,000만 달러 이상의 이더를 탈취당했다. 이 피해를 되돌리기 위해 소프트 포크(Soft fork) 방식으로 시행하려 했으나 도중에 DDos 공격으로 인해 취소되었고, 결국 이더리움 블록체인을 하드 포크(Hard fork)하게 되었고 이더리움 클래식이 탄생했다.

**이더리움 생태계의 주요 조직**

- 이더리움 재단
    - 이더리움 플랫폼의 로드맵을 개발하고 추가 변화를 구현하는 리더
- 기업용 이더리움 연합(EEA, Enterprise Ethereum Alliance)
    - 2017년 초 발표된 EEA 는 이더리움 블록체인 솔루션 배치에 관심이 있는 기업을 통합하는 것을 목표로 한다. 대표적으로 IBM, MS 가 있다.
- 패리티(Parity)
    - 이더리움 창립자 중 한명인 개빈 우드(Gavin Wood) 에 의해 설립되었고, 여러 이더리움 개발자 도구를 배포했다.
    - 패리티가 희생자가 된 패리티 해킹은 DAO 이후 두번째로 큰 해킹인데, 두 가지 거래를 한번에 보낼 수 있게 하는 멀티 시그(Multi Sig) 지갑 라이브러리의 취약점을 이용해, 지갑 주소를 변경하는 방식으로 해킹했다.
- 컨센시스(ConsenSys)
    - 이더리움 공동 설립자인 조셉 루빈(Joseph Lubin) 에 의해 설립되었다. 여러 엔터프라이즈 도구, 이더리움 블록체인 교육을 제공하며, DApp 개발에 집중하고 있다.
    - **메타마스크(Metamask)** 의 개발 회사로 잘 알려져 있다.

### 탈중앙화 애플리케이션 (DApp)

DApp 은 기본적으로 스마트 콘트랙트 플랫폼에서 실행되는 모든 컴퓨터 프로그램이며, 일반적인 서버/클라이언트 아키텍처로 구성된다. 서버는 스마트 콘트랙트를 실행하기 위한 블록체인의 일부이다.

**사용사례**

중앙집중화 시스템에 의해 제약이 있는 곳에서 주로 사용된다. 이더리움 플랫폼을 사용하면 개발자들은 허가받지 않고 앱을 배포할 수 있다.

**개발 과제**

스마트 콘트랙트는 한번 배포하면 갱신이 어렵다. 스마트 콘트랙트 플랫폼에서는 같은 주소로 재배치를 허용하지 않고, 어려운 데이터 마이그레이션이 수반되기 때문이다.

개발자는 테스트넷에서 DApp 을 테스트 하고 커뮤니티의 감사를 받게 된다. 이렇게 배포하는 과정을 거칠 때 마다, 반영이 느려 사용자 경험이 저하될 수 있다.

### 이더리움에서 스마트 콘트랙트의 배치 및 실행

옴니코어가 비트코인과 핵심 개발자에게 스케일링과 속도를 의존하는 것에 제한되어 있는 것과 달리, 이더리움은 **이더리움 가상머신 (EVM, Ethereum Virtual Machine)** 을 사용해 쉽게 DApp 을 만들고 네트워크에서 실행할 수 있다.

**EVM 의 목적**

- 개발자가 스마트 콘트랙트를 블록체인에 도입할 수 있도록 한다.
- 마이너에게 자신이 실행하는 소프트웨어에 내장된 EVM 스마트 콘트랙트 코드를 실행하는 방법을 지시한다.

**스마트 콘트랙트 작성**

이더리움 스마트 콘트랙트는 솔리디티(Solidity) 를 사용해 작성한다. 시작하기 전에 지갑이 필요한데, 생성 시 **시드 문구** 를 안전하게 저장해야 한다. (물리적 수단이 비교적 안전하다)

스마트 콘트랙트는 가스 형태의 이더리움을 소비하기 때문에, **테스트넷(스테이징 환경)** 에서 사용할 수 있는 화폐를 미리 확보해 두어야 한다. 이는 **수도꼭지(Faucet)** 라는 곳에서 발급받을 수 있다.

**스마트 콘트랙트 배포**

Remix 같은 솔리디티를 지원하는 IDE 를 사용하면 쉽게 DApp 을 디버그, 배포 할 수 있다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/15b41ef5-62aa-44a5-b9d9-b9c35bf3102e" />
</p>

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/1e1d07a3-06a0-4c62-9218-95dc364ca43c" />
</p>

이더리움 네트워크가 트랜잭션을 처리한 후, 솔리디티 코드를 EVM 에서 명령코드로 변환하고, 공간이 작은 바이트 코드 형식으로 이더리움 네트워크에 스마트 콘트랙트를 저장한다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/eba2b1f4-87e1-48db-9ec6-2663cd38eb18" />
</p>

**EVM 의 내부 구조**

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/665915c2-b037-4479-87c7-a3b0c7a2a22a" />
</p>

**스마트 콘트랙트와의 상호작용**

스마트 콘트랙트는 배포된 후 네트워크에 배치되어 데이터를 읽고 쓸 수 있게 된다. 콘트랙트에 데이터를 작성하려면 콘트랙트 주소로 트랜잭션을 전송해야 한다.

스마트 콘트랙트는 모든 상호작용을 위해  **ABI(Application Binary Interface, 스마트 콘트랙트 API)** 에 대한 참조가 필요하다. 

```
**// Contract ABI Example //**

[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"}],"name":"approve","outputs":[{"name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[{"name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_value","type":"uint256"}],"name":"burn","outputs":[{"name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"}],"name":"balanceOf","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_value","type":"uint256"}],"name":"burnFrom","outputs":[{"name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transfer","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"},{"name":"_extraData","type":"bytes"}],"name":"approveAndCall","outputs":[{"name":"success","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"},{"name":"","type":"address"}],"name":"allowance","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"inputs":[{"name":"initialSupply","type":"uint256"},{"name":"tokenName","type":"string"},{"name":"tokenSymbol","type":"string"}],"payable":false,"stateMutability":"nonpayable","type":"constructor"},{"anonymous":false,"inputs":[{"indexed":true,"name":"from","type":"address"},{"indexed":true,"name":"to","type":"address"},{"indexed":false,"name":"value","type":"uint256"}],"name":"Transfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"from","type":"address"},{"indexed":false,"name":"value","type":"uint256"}],"name":"Burn","type":"event"}]
```

**스마트 콘트랙트 작성**

메타마스크 등 지갑 익스텐션을 사용해서 웹에 연결하면 콘트랙트에 데이터를 쓸 수 있다. 연결된 웹에서 데이터 작성 후 컨펌하면,

1. 새 트랜잭션이 생성되어 데이터가 채워지고 지갑으로 전달된다.
2. 지갑은 해당 트랜잭션을 전달할 수 있는 권한을 요청한다.
3. 컨펌하면 트랜잭션이 이더리움 네트워크로 전송된다.

**스마트 콘트랙트 실행**

마이너들은 일반적인 방식으로 블록에 트랜잭션을 추가한다. 트랜잭션이 트리거 할 수 있는 주요 동작은 다음과 같다.

- 지불(Payment) - 주소 A to B 로 ETH 전송
- 실행(Execution) - 스마트 콘트랙트 실행

마이너는 EVM 을 통해 콘트랙트 코드를 실행한다.

- 수신 주소는 스마트 콘트랙트이다.
- 데이터 페이로드에 데이터가 들어있다.

**스마트 콘트랙트 실행 가스 및 가격**

스마트 콘트랙트 실행에 필요한 명령 코드 마다, 필요한 가스가 명시되어 있다. 즉, 명령 코드를 많이 사용할 수록 (함수, 구조체 등) 돈이 많이 필요하다는 의미이다.

**트랜잭션 구성을 위한 가스 필드**

- 가스 가격 (Gas Price)
    - 처리에 필요한 수수료이다. 수수료를 많이 지불할 수록 트랜잭션이 더 우선적으로 처리된다.
- 가스 제한 (Gas Limit)
    - 마이너들에게 트랜잭션 처리를 위해 지불할 수 있는 최대 가스 양이다. 콘트랙트의 명령코드를 실행하기에 충분한 가스양 이어야 한다.
