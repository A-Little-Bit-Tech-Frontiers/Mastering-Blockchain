# 이더리움으로 진화

## 비트코인의 제한된 기능 개선

비트코인의 진화는 개발자 커뮤니티에서 영향력있고 열정적인 지지자들을 구성해 보안과 안정성의 이유로 조심스럽고 제한적인 프로토콜 변경을 주장했다. <br>
블록 크기 증가와 같은 프로토콜 변화는 회의적인 시작으로 바라봤다. <br>
그러나 일부 비트코인 개발자들은 스케일링 솔루션을 향한 움직임을 보였다. <br>
개발자들이 그 위에 새로운 블록체인을 만드는 방법을 고안하기 시작하면서 비트코인은 프로그래밍이 가능한 돈이 될 수 있는 토대가 됐다.

### 컬러드 코인과 토큰

컬러드 코인은 주식이나 금과 같은 실제 자산을 비트코인 블록체인에 표현하고 관리할 수 있게 해준다. (컬러드 코인은 비트코인 블록체인이 아닌 위에 구축된다.) <br>
컬러드 코인을 위해 토큰의 아이디어를 도입했는데, 기존 블록체인 위에 독특한 원장을 프로그래밍해 만든 가치 단위다. <br>
토큰은 다른 블록체인 네트워크에 의해 구동되는 것을 제외하고는 다른 암호화폐처럼 보이고 행동한다. <br>
토큰은 이더리움 생태계의 발전을 기반으로 했으며, 비트코인 컬러드 코인이 등장하며 다른 블록체인의 토큰이 생겨났다.

### 마스터코인과 스마트 콘트랙트

비트코인의 스케일링 솔루션의 진화는 마스터코인의 개발로 발전했다. <br>
이는 비트코인 위에 만들어져 비트코인의 핵심 프로토콜에 원래 포함되지 않은 기능을 추가했다. <br>
마스터코인은 비트코인의 단순한 기능을 넘어 프로그램 가능한 돈 개념으로 이어졌고, 그 중 하나는 스마트 콘트랙트의 개념이였다. <br>
마스터코인은 추가 암호화폐(토큰)의 개념을 도입했다. (이전에는 소프트웨어 포크 밖에서 새 암호화폐를 만들기 어려웠다.)

### 옴니레이어의 이해

옴니레이어는 비트코인의 기반으로 구축된 오픈소스이자 분산 자산 거래 플랫폼이다. <br>
이는 기본적으로 비트코인의 요소를 추가적인 특징으로 강화한다. <br>
또 스마트 콘트랙트 기능을 제공해 개발자가 탈중앙화와 투명한 방식으로 화폐 기능을 자동화할 수 있도록 했다. <br>
스마트 콘트랙트로 트랜잭션과 합의를 블록체인 상에서 실행해 통화 이외의 기능을 수행할 수 있다. <br>
토큰으로 다른 블록체인 프로토콜 위에 구축된 새로운 암호화폐를 만드는 기능이 포함된다.

#### 테더

옴니에서 가장 잘 알려진 프로젝트는 테더다. 테더는 암호화폐의 휘발성 토큰 생태계에서 법정화폐담보인 안정적인 자산을 표현하는 방법이라는 매우 중요한 사례를 만든다. <br>
테더는 디지털 블록체인 암호화폐로, 미국 달러화에 고정된 안정적인 통화를 제공하는 목표가 있다. 백서에 따르면 테더 토큰은 1달러에 고정돼 있다. <br>

#### 옴니레이어의 작동 방식

- 관세: 옴니레이어 네트워크에서 관리되는 원장에서 누구나 화폐를 만들 수 있다.
- 탈중앙화 거래소: 당사자 간의 통화를 쉽게 교환하려면 중앙집중화 거래소를 사용하는 대신, 트레이드 코드를 실행한다.

#### 사용자 정의 논리 추가

비트코인은 블록체인을 유지하는 규칙인 논리적 연산을 수행하며 합의를 이루는 기본 개념이 작동한다는 것을 입증한다. <br>
옴니가 비트코인 블록체인에 맞춤형 논리 연산을 추가한다. <br>
2014년 3월 이후 비트코인은 OP_RETURN 필드를 추가해 비트코인 트랜잭션에 추가 데이터를 첨부할 수 있게 됐다. <br>
그러면서 모든 옴니 트랜잭션은 비트코인의 트랜잭션의 OP_RETURN 필드에 레코드를 저장하기 시작한다.

| OP_RETURN에 저장된 값 | ASCII 또는 십진법으로 | 설명                                               |
|-----------------|------------|--------------------------------------------------|
| 6f6d6e69        | omni       | 옴니 플래그로 옴니 트랜잭션임을 확인한다.                          |
| 00000000        | Simple send | 트랜잭션 유형이다.                                       |
| 0000001f        | 31         | 속성 타입은 USDT인 31이다.                               |
|000000001dcd6500| 5.00000000           | 보낼 양은 5.00000000이다. 옴니 트랜잭션에는 모든 소수점 이하 8자리가 있다. |

<br>

## 이더리움: 마스터코인을 한 단계 끌어올리기

이더리움 개념은 2013년 비탈릭 부테린이 처음 제안했다. <br>
마스터코인 재단에 프로토콜을 변경하고 기능을 더 추가하기 위해 활동한 이후, 이더리움 프로토콜을 만들기 위해 노력했다. <br>
이더리움의 목적은 마스터코인을 한 단계 끌어올리는 것이다. (합의로 확보된 탈중앙화 개방형 컴퓨터 시스템을 만드는 것) <br>

### 이더와 가스

이더 암호화폐는 비트코인과 비슷한 방식으로 동작하며, 거래 주소 명명법이 비슷하다. <br>
이더리움 주소는 0x 시퀀스로 시작하고, 블록체인은 주기적인 네트워크 혼밥을 대비한 컨펌 시간이 훨씬 빠르며 비트코인보다 전송 메커니즘이 훨씬 빠르다. <br>
비트코인은 지출하지 않은 거래 출력(UTXO)을 사용해 계좌이 잔액을 추적하고, 이더리움은 계좌 상태의 잔액을 추적한다. <br>
UTXO는 지폐와 동전 등 실제 현금을 가지고 있는 것과 같다. 이더리움의 접근 방식은 모든 자금이 은행 계좌에 있는 것과 같다.

이더리움은 비트코인와 마스터코인의 요소를 더해서 애플리케이션 기반 블록체인 트랜잭션을 만드는데, 단순한 계좌 기반 송수신 이상의 기능을 제공한다. <br>
이더리움에는 가스라는 계정 단위가 있다. 가스는 개발자들이 이더리움 플랫퐁메서 애플리케이션들을 실행할 수 있게 한다. (애플리케이션들은 탈중앙화 응용 프로그램이나 디앱으로 알려짐) <br>
이더리움은 스마트 콘트랙트에서 실행되는 코드의 계산에 가스 사용을 요구해 디앱이 가능한 한 효율적으로 동작하도록 한다.

### 탈중앙화된 자율 조직

이더리움 생태계에서 탈중앙화의 기풍을 한 단계 높이기 위해 중앙집중화된 당국의 거버넌스를 대체할 방안으로 탈중앙화된 자율조직(DAO) 개념을 제시했다. <br>
이는 암호화폐 모금 프로젝트를 활용해 ICO 투자자가 ICO에서 구매한 토큰의 오너십에 상응하는 의결권을 갖는 분산형 거버넌스 시스템을 만든다. <br>

#### 이더리움의 포크로 탄생된 이더리움 클래식

출시 후, DAO의 스마트 콘트랙트 코드에서 취약성 문제가 발생했다. <br>
그 중 하나가 재귀 호출 취약성 문제다. 지갑에서 자급이 빠져나갔을때 잔액은 함수 호출이 끝날때에만 업데이트됐다. <br>
만약 최초 통화가 끝나기 전 같은 기능을 호출할 수 있다면, 동일한 자금을 계속해서 인출할 수 있는 무한 재귀 상황이 발생하는 것이다.

이 사건은 이더리움 블록체인을 포크하는 계기가 됐다. 이후 두 가지 다른 버전의 이더리움이 만들어졌다. <br>
도난당한 자금의 원본 블록체인과 이더리움 클래식으로 알려진 해당 자금을 회수하는 포크 버전이다. <br>
하드포크로 훔친 자금을 정당한 소유자가 되찾을 수 있도록 복구 주소로 옮겼다.

#### 기타 이더리움 포크

이더리움 블록체인은 취약점 등 코드의 변화를 보완하기 위해 여러 차례 포크를 거쳤다. <br>
이더리움 생태계는 블록체인을 포크하고 이러한 변화가 성공할 수 있는 충분한 가치가 있다고 본다. <br>
비트코인의 불변성이 신성불가침한 것으로 여겨지는데 비해 대조적이다.

## 탈중앙화 애플리케이션

블록체인에서 스마트 콘트랙트를 통해 실행되는 애플리케이션을 탈중앙화 애플리케이션(Dapps)이라고 한다. <br>
디앱은 일반적으로 블록체인에서 실행되는 스마트 콘트랙트와 상호작용하는 백엔드 및 프론트엔드 UI로 구성된다. <br>

### 사용 사례

디앱의 주요 특징은 불변성이다. 불변성이란 블록체인에 게시된 후 중앙집중화 권한으로 코드를 변경할 수 없다는 것을 의미한다. <br>
디앱은 보통 중앙집중화 시스템에서 병목 현상이 있는 곳에서 많이 사용된다. <br>
예를 들어, 많은 중앙집중화 애플리케이션은 어떤 콘텐츠나 정보가 제3자나 중앙 기관에 의해 검열되지 않는다. <br>
단 결정할때 주관적이고 임의적이며 사용자의 의견을 반영하지 않는 경우가 많다. <br>
디앱의 블록체인은 디지털 자산의 효율적이고 안전한 이전이 가능하다는 특징이 있다. 

## 이더리움에서 스마트 콘트랙트의 배치 및 실행

옴니레이어는 블록체인 위세 디앱을 실행할 수 있다는 것을 증명했지만 한계도 많았다. <br>
가장 큰 한계로는 디앱을 작성하고 배포하는 권한이 있는 사람이 누구인지에 관한 것이다. <br>
만약 누군가가 디앱을 배포하려 한다면, 플랫폼의 개발자를 설득해 옴니코어 코드에 추가해야 했다. 옴니코어는 모든 코드가 배치된 디앱이었다. <br>
코드 개발이 중앙집중화됐고 옴니코어 개발자만 코드를 업데이트할 수 있었다.

### 이더리움 가상머신

이더리움 가상머신(EVM)을 사용하면 개발자가 쉽게 디앱을 만들고 네트워크에서 실행할 수 있다. <br>
EVM의 목적은 두 가지다.

1. 개발자가 스마트 콘트랙트를 블록체인에 도입할 수 있게 한다.
2. 마이너에게 자신이 실행한 소프트웨어에 내장된 EVM 스마트 콘트랙트 코드를 실행하는 방법을 지시한다.

#### 스마트 콘트랙트 작성

개발자는 스마트 콘트랙트를 작성하기 위해 다른 언어를 사용할 수 있다. (솔리디티) <br>
스마트 콘트랙트와 상호작용 하려면 이더리움 지갑이 필요한데, 가장 인기있는 지갑은 메타마스크다. <br>

#### 스마트 콘트랙트 배포

개발자는 스마트 콘트랙트를 작성한 후 메인넷 또는 프로덕션 환경이나 테스트넷에 게시할 수 있다. <br>
퍼블리싱은 스마트 콘트랙트 트랜잭션을 이더리움 네트워크에 전송해 이뤄진다. (이더리움 리믹스 도구를 사용) <br>
리믹스는 스마트 콘트랙트 개발을 위한 IDE이고, 솔리디티와 바이퍼 언어를 지원한다.

### 가스 및 가격

가스는 이더리움 생태계에서 트랜잭션 처리에 이더리움 마이너가 얼마를 지불하는지 계산하기 위해 사용되는 계정 단위다. <br>
마이너가 EVM을 통해 스마트 콘트랙트 거래를 실행할 때, 마이너는 스마트 콘트랙트에 작성된 명령코드를 실행한다. <br>
스마트 콘트랙트를 통해 트랜잭션 처리에 대한 마이너들에게 보상을 해주기 때문에 가스가 필요하다. <br>
또한 스팸 및 서비스 거부 공격으로부터 네트워크를 방어한다. <br>
트랜잭션을 구성할때 입력해야 하는 두 가지 가스 관련 필드가 있다.

- 가스 가격: ETH의 양은 가스 단위로 지불됐다. 사용자가 즉시 트랜잭션을 처리하기를 원하면 마이너가 처리 대기중인 다른 트랜잭션보다 더 높은 가스 가격을 지불할 수 있다.
- 가스 제한: 마이너들에게 트랜잭션 처리를 위해 지불할 수 있는 최대 가스 양이다.

> Wei는 이더리움의 가장 작은 단위로, 10e-18이다. <br>
> 다음은 다른 종류의 웨이다.
> - 1 wei = 1wei
> - 1 kewi = 1,000 wei
> - 1 mwei = 1,000,000 wek
> - 1 gwei = 1,000,000,000 wei




















