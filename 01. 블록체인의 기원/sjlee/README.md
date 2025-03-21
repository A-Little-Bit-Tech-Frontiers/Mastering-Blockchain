## 1. 전자시스템과 신뢰

블록체인, 암호화폐와 같은 시스템이 현실로 다가오기 전까지 인터넷은 안정적이고 분산된 방식으로 인터넷을 사용했다. 1960년대 초기에 인터넷은 단순하고 상대적으로 작은 네트워크였으며 주로 대학 연구원이나 미국 정부에서 정보를 디지털 방식으로 공유 하는 도구로 사용됐다.

시간이 지나면서 초기 인터넷 사용자들은 시스템을 더 유용하게 만들었다. 인터넷만 가능하다면 대부분 무료로 정보를 사용할 수 있다. 반면 **온라인 제품이나 서비스 대부분 제3자인 개인 또는 법인이 중개자 역할을 수행**해야 했다. 여기에는 두 가지 유형의 신뢰가 필요하다.

- 중개자 신뢰: 합리적이고 공정한 결정을 내리기 위해 제3자인 개인 또는 법인의 신뢰에 의존
- 신탁 발행: 모든 가치의 안전과 보안을 보장하기 위해 제3자인 개인 또는 법인의 신뢰에 의존

금융 거래는 중개자의 신뢰와 신탁 발행자의 신뢰에 의존해 주요 영역에서 사용됐다. 요즘 사람들은 체크카드나 신용카드와 같은 전자 금융 도구를 사용하기 때문에 법정화폐의 사용이 줄어들고 있다. 돈은 디지털화됐다.

결제를 지원하는 시스템은 디지털로 운영 된지 꽤 오래다. 여전히 현금을 쉽게 구할 수 있으나 많은 사람들이 느끼지 못한 사이에 ‘돈’은 종이화폐와 동전에서 숫자로 변했다.

## 2. 분산화 vs 중앙집중화 vs 탈중앙화

인터넷은 분산 기술로 설계됐지만 중앙집중화 애플리케이션과 분산화 애플리케이션이 혼합된 형태다.   
자전거 바퀴에서는 많은 바퀴살이 단일 허브(축)에 연결된다. 분산 방식을 사용해 바퀴살 일부가 파손돼도 바퀴는 계속 작동하는 설계 방식이다.  **분산은 어떤 단일 장애 지점도 전체 시스템을 무너뜨릴 수 없다는 것을 의미**한다.

컴퓨팅 분야에서 분산화 시스템은 하나의 컴퓨터에서만 처리되지 않는 시스템을 말한다. 계산은 여러 컴퓨팅 자원에 걸쳐 공유된다. 분산화 시스템은 메시지를 사용해 서로 통신한다.

분산 시스템은 다수의 컴퓨터에 책임을 분산시키고 처리 능력을 활용해 공동으로 작업을 수행하는 것이 목표다. 그러나 분산은 공통 목표와 메시징의 개념을 변화시킨다. 완전히 탈중앙화된 시스템에서는 특정 노드가 자신의 목표를 달성하기 위해 반드시 모든 다른 노드와 협력할 필요는 없으며, 결정은 합의를 통해 이뤄지며 단일한 개체에 책임을 맡기지 않는다.

<img width="633" alt="image" src="https://github.com/user-attachments/assets/bc80af7e-2f91-4ffd-a230-5330c58259a7" />


아래 그림들을 통해 위 세 시스템의 차이를 직관적으로 확인해보자. 

1. 중앙집중화 데이터베이스
    
    <img width="375" alt="image" src="https://github.com/user-attachments/assets/6b2fc755-7239-41de-8cab-791c181aa113" />

    
    - 페이팔과 같은 중앙집중화 데이터베이스에서 모든 노드는 하나의 개체에 의해 제어되는 단일 중앙 노드에 연결된다.

1. 분산화 데이터베이스
    
    <img width="636" alt="image" src="https://github.com/user-attachments/assets/567259e1-de9b-4936-9f02-787bd326bbf0" />

    
    - 각 노드는 다른 노드의 ID를 가지고 있으며, 모든 노드는 하나의 개체에 의해 제어된다.

1. 탈중앙화 데이터베이스
    
    <img width="747" alt="image" src="https://github.com/user-attachments/assets/ff9fdb39-22cf-4dbf-8d55-862cf06de82c" />

    
    - 비트코인의 블록체인과 같은 분산화 데이터베이스에서 각 노드는 같은 데이터의 복제된 복사본을 유지할 수 있고, 각 노드는 다른 노드의 식별을 모를 수 있으며, 모든 노드는 익명의 많은 개체에 의해 제어된다.

## 3. 비트코인 실험

2008년까지 세계는 분산된 주체로서 많은 인터넷 서비스에 의존했다. 게다가 사람들은 오프라인 매장보다는 온라인에서 점점 더 많은 상품과 서비스를 구매 하기 시작했다. 신용카드, 체크카드는 페이팔과 같은 서비스와 함께 결제 시스템으로 사용했다. 

2006년 초, 세계 경제는 요동치고 있었다. 경제 성장기였지만 그해 금융 시스템은 균열이 생기기 시작했다. (미국 주택 시장은 처음으로 가치가 하락했는데, 대출에 대한 규칙이 너무 느슨해서 많은 채무자들이 채무를 상환할 수 없었기 때문)

### 3.1 백서

2008년 8월 18일, [bitcoin.org](http://bitcoin.org/) 도메인이 등록됐다. 이후 사토시 나카모토라는 가명을 쓴 개인 또는 그룹이 2008년 10월 31일에 백서를 작성해 수많은 소프트웨어 개발자 메일링 리스트에 공유했다. 금융위기와 같은 사건이 재발하지 않도록 투명한 금융 시스템을 구축하는 것이 백서의 목표

백서에는 다음과 같은 내용을 포함하고 있었다.

- 이중 지출(Double spending)
    - 위조된 복제를 통해 통화 단위가 두 번 이상 지출될 위험.
- 작업 증명(Proof of Work)
    - 계산 능력으로 해결해야 하는 수학적 문제
- 해시 (Hash)
    - 다양한 크기와 시퀀스 데이터를 구성할 수 있도록 고정된 길이의 출력이 생성
- 논스(Nonce)
    - 특정 통신을 한 번만 사용할 수 있는 난수
- 주조 기반 통화 모델의 초월
    - 비트코인 백서는 디지털 전용 네트워크에 모든 거래를 게시함으로써 조폐국 기반의 **중앙 권한을 제거할 것을 제안**했다.
    - 신뢰할 수 있는 당사자 없이 이를 달성하려면 거래를 공개적으로 발표해야 하며, 참가자들이 자신이 받은 순서에 대한 단일 이력을 합의할 수 있는 시스템이 필요하다. **수취인은 각 거래시점에 노드 대다수가 최초 수취인이라는 데 동의했다는 증거가 필요**하다.

 

### 3.2 타임스탬프 서버 소개

트랜잭션을 검증하기 위해 타임스탬프 시스템을 사용할 것을 제안했다. 트랜잭션 중 생성된 정보를 해시 알고리즘을 사용해 실행하면 해시라고 알려진 고정된 숫자와 문자의 문자열이 생성된다. (사토시는 비트코인에 SHA-256을 사용할 것을 제안함)

해시 알고리즘 예)

- keccak256("hello") = Ic8aff950685c2ed4bc3174f3472287b56d9517b9c948127319309a7a36deac8
- keccak256("hellol") = 57c65fl718e8297f4048beff2419el34656b7a856872b27ad77846e395fl3ffe

비트코인 백서는 연쇄 서명 즉, 해시로 거래를 추적하는 개념을 소개한다. 블록들 이 연결돼 시간 순으로 구성된 구조다.

이 방식은 본질적으로 트랜잭션을 추적하기 위해 요구하지 않는 회계의 단위를 어떤 단일 노드에 만든다. 대신, 블록체인은 디지털 시스템에서 트랜잭션을 추적하기 위해 암호 수학적 신뢰를 사용한다. **네트워크는 블록체인을 확인하고 게시하기 위해 Peer-To-Peer 시스템을 사용하기 때문에 복잡한 구조가 필요하지 않다**(기본적으로 저장용 **분산 데이터 구조**와 인터넷상의 **공용 네트워크를 구성하는 메시징 시스템 프로토콜**이 필요함)**.** 블록체인은 여러 트랜잭션 블록으로 구성되며, 트랜잭션 블록은 해시를 통해 서로 연결된다. 인터넷에서 자유롭게 이용할 수 있는 블록체인은 많지만 **공개적이지 않은 것도 있는데** 비즈니스 환경에서 사용되는 블록체인은 더욱 그러하다.

비트코인 블록체인은 비트코인 네트워크의 모든 당사자들이 동의하는 글로벌 원장이다. 결제 네트워크에서 원장은 끊임없이 변화하는 문서다. 누군가가 트랜잭션을 전송하려고 할 때마다 새로운 데이터 행이 원장에 추가된다. 비트코인을 사용하면 약 10분마다 새로운 거래 블록이 원장으로 정의될 수 있는 것에 추가된다. 

**비트코인 블록의 중요한 속성**

- **Block Hash**
    
    블록의 고유 식별자. 블록 해시는 256비트 데이터 안에서 블록체인의 현재 상태에 대한 스냅샷을 제공하는 입력 데이터에서 생성된다. 스냅샷은 전체 비트코인 블록체인에 관한 대차대조표의 기술버전과 같다. **비트코인 블록은 자체 해시를 포함하지 않지만, 블록이 체인으로 연결된 이전 블록의 해시를 포함**한다. Block Hash는 블록 헤더를 통해 해시화해 찾을 수 있다.
    
- **Coinbase Transaction**
    
    네트워크에서 **채굴된 새로운 블록의 첫 번째 트랜잭션**이다. Coinbase Transaction은 블록 공급에 의해 새로운 비트코인을 추가하는데, 체인에 블록을 추가하는 마이너(Miner)에게 보상으로 주며 블록을 공급해주는 방식이다. 이를 채굴이라 함
    
- **블록 높이 번호(Block high number)**
    
    현재 블록과 체인의 첫 번째 블록(제네시스 블록) 사이에 얼마나 많은 블록이 있는지 식별한다.
    
- **머클루트(Merkle root)**
    
    블록체인의 유효성을 증명할 수 있는 해시 값
    

(참고) 비트코인 조작이 어려운 이유

<img width="619" alt="image" src="https://github.com/user-attachments/assets/79575532-87be-4087-a20b-f60c6a0d00a8" />


- 각 블록에는 이전 블록의 해시값이 들어있어, 한 블록을 변경하면 나머지 블록을 다시 계산해야 한다.
- 과거 블록(74번)을 조작하려면?
    - 한 마이너가 74번 블록에서 거래를 바꾸려면, 74번 이후의 모든 블록(74~90번)을 다시 계산해야 한다.
    - 블록을 다시 계산하는 것은 매우 어렵고 시간이 오래 걸린다. (PoW: 작업 증명)
- 시간 싸움에서 이길 수가 없음
    - 네트워크의 다른 사람들이 91번 블록에서 계산하고 있으므로, 공격자는 91번 블록이 채굴되기 전에 74~90번 블록을 모두 다시 계산해야 함

## 4. 비트코인을 되살리다

비트코인의 구성요소

- 가치
    - BTC라고 하는 계정 단위는 비트코인 블록체인으로도 알려진 원장에 거래를 기록하는데 사용
- 분배
    - 비트코인 네트워크는 거래 기록을 유지하기 위해 탈중앙화된 노드를 사용한다.
- 합의(Consensus)
    - 비트코인 네트워크의 마이너들은 분산된 거래 기록의 보안과 안정성을 유지하기 위해 작업 증명을 함께 사용한다.

제네시스 블록으로 알려진 첫 번째 블록은 금융 위기를 블록체인 네트워크로 되살리기 위해 전달했다. 제네시스 블록에서 코인베이스 트랜잭션 입력 내용은 아래와 같다.

`2009년 1월 3일 더 타임스, 은행들의 두 번째 구제금융을 앞두고 있는 U.K. 재무장관`

사토시는 최초의 비트코인 클라이언트를 만들었다. 클라이언트를 실행하면 사용자가 노드를 실행하고 비트코인 블록을 채굴할 수 있다.

블록체인은 끊임없이 업데이트 되는 문서다. 페이팔과 같은 **중앙 결제 네트워크**의 사용자들은 중앙 당국이 **시간이 지나면서 새로운 거래로 원장을 업데이트할 것이라고 믿는다**. 그러나 비트코인과 같은 **탈중앙화 결제 네트워크에는 중앙 권한이 없다**. 단지 수천 명의 익명의 마이너들이 네트워크에 힘을 실어주고 있을 뿐이다.

비트코인의 블록체인을 새로운 거래 블록으로 업데이트하기 위해 누구를 신뢰해야 할까? → **합의 달성(**네트워크에 전력을 공급하는 모든 마이너가 사용하는 프로세스)

합의 달성의 목적은 다음과 같다.

- 블록 발견
    
    트랜잭션 블록을 추가할 수 있는 권한을 갖는 마이너를 합의한다.
    
- 트랜잭션의 유효성
    
    새 블록에 포함된 트랜잭션이 합법적 이라는 데 동의한다.
    

암호화에 사용되는 대부분의 블록체인은 합의를 달성하기 위한 두 가지 접근법 중 하나를 따른다.

- Proof-of-Work: 작업 증명
- Proof-of-Stake: 지분 증명

### 4.1 공개키 - 개인키 암호화

비트코인은 공개키 암호화와 개인키 암호화를 이용해 거래의 타당성을 증명한다. **개인키는 비트코인 거래에 디지털로 서명하는 데 쓰이고**, 주소 소유자가 정당한 소유자임을 네트워크에 증명한는 데 사용된다. 또한 승인하는 데에도 쓰인다.

**공개키는 비트코인 주소를 생성하는 데만 사용**된다. **주소는 본질적으로 공개키의 압축 버전이므로 읽기가 다소 쉽다**. 

**키 생성**

개인키는 무작위로 선택된 256비트 숫자다. 개인키는 거의 항상 16진수 형식으로 표시 돼있고, **개인키는 컴퓨터에 의해 생성**된다.

개인키는 공개키와 페어링돼 네트워크에서 거래할 수 있다. 아래 그림은 개인키가 공개키와 주소를 생성하는 과정이다.

<img width="721" alt="image" src="https://github.com/user-attachments/assets/53969c98-b5a0-4dbd-8e33-6198f955bdae" />


### 4.2 트랜잭션 생성

UTXO 모델을 따른다. UTXO는 사용되지 않은 거래 산출물을 의미한다. 트랜잭션은 기본적으로 입력 목록과 출력 목록이 존재한다. **각 입력은 과거에 받은 주소와 자금의 원천으로 작용하는 비트코인 주소의 미지출 거래를 식별**한다. 또한 해당 주소의 소유자 트랜잭션을 승인했다는 것을 증명하는 디지털 서명이 포함돼 있다.  **출력은 받는 비트코인 주소와 주소가 받을 금액을 보여준다.**
