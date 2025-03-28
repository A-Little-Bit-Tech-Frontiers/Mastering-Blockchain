# 3장 포크와 알트체인

### 비트코인 개선안

비트코인 코어는 오픈소스지만 제안과 반영을 위해서는 거버넌스 프로세스를 따라야 한다.

**BIP(Bitcoin Improvement Proposals)** 는 비트코인 코어 코드를 지속적으로 관리하고 업데이트 하는 커뮤니티의 과정이다. 이는 BIP 수명주기에 따라 전체 공동체에 의해 이뤄진다.

### 포크(Fork)

비트코인 커뮤니티가 점점 커지면서, 프로그래머들은 소프트웨어 포크를 통해 개량한 비트코인, 알트코인 등의 코인 등을 만들었다.

일반적인 **소프트웨어 포크** 와 달리, 암호화폐에서 사용되는 포크 들의 의미는 다음과 같다.

- **소프트포크**
    - 블록체인 기술과 관련해 네트워크를 변경하지만 모든 채굴자가 참여할 필요는 없는 채굴 소프트웨어의 업그레이드다. 소프트포크는 이전 소프트웨어와 호환되며, 일반적으로 트랜잭션 기능을 업그레이드하기 위해 수행된다.
- **하드포크**
    - 채굴 소프트웨어를 업그레이드해 네트워크를 바꾸는 것으로, 모든 채굴자가 참여해야 한다. 업그레이드는 이전 소프트웨어와 호환되지 않으며, 일반적으로 주요 보안 또는 기능 변경을 구현한다.
    - 하드포크가 발생한 순간까지 두 블록체인은 동일한 기록을 가지고 있다. 포크 이후에는 각 블록체인이 자체적인 새로운 블록과 새로운 트랜잭션 기록을 만들고, 블록은 서로 다른 마이너가 채굴할 수 있다.

**마이너**

네트워크 실행을 위해 해시파워를 기여하는 사람들이다. 논쟁의 여지가 있는 하드포크가 발생하면, 마이너는 프리포크된 블록체인이 사용하는 소프트웨어 버전을 유지하거나 포크된 블록체인이 사용하는 소프트웨어 버전으로 변경해 어떤 블록체인을 지원할지 결정한다.

논란이 되는 포크가 발생하면 커뮤니티는 2,016개의 블록이 생성된 후 해시레이트가 가장 높은 블록체인을 승리한 블록체인으로 간주하고, 블록체인이 프리포크 이름을 그대로 유지하는 보상을 얻는다. 거래소에서는 블록체인에 프리포크 이름을 붙여 취급하는데 이는 가격에도 지대한 영향을 미친다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/ab2ad8eb-151b-45fd-aadc-ec532f528427" />
</p>

**리플레이 공격**

공격자가 합법적인 거래의 데이터를 포크된 블록체인에서 거래를 복제하거나 미러링할 때 발생한다.

두 블록체인이 모두 트랜잭션 서명을 생성하는 프로세스가 정확히 같을 경우 리플레이 공격에 취약하다.

비트코인 캐시 소프트웨어는 트랜잭션 데이터 구조에 SIHASH_FORKID 라는 새 필드를 추가했다. 이 필드는 비트코인캐시 트랜잭션에서만 유효하다. 이를 통해 네트워크 마다 유효성을 구분할 수 있다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/417e8183-5ac6-4f7a-87d1-e89687ae2732" />
</p>

### 비트코인캐시 포크

비트코인 커뮤니티에서는 비트코인 네트워크의 개선에 대한 의견 불일치가 계속 존재했다. 양측이 비트코인 확장에 대해 합의에 이르지 못하자 결국 하드포크가 마련되었다.

마이닝 하드웨어 제조업체 비트메인(bitmain)은 커뮤니티를 두 개의 다른 블록체인으로 만드는 계획을 개발했다. 마이닝 풀인 ViaBTC 는 블록 크기가 커지면 수수료가 낮아지고 트랜잭션 확인 속도가 빨라져 새로운 암호화폐를 현금처럼 소비할 수 있다는 생각을 반영해 비트코인캐시(BCH)라는 용어를 만들었다.

### 알트코인

비트코인 코어 소프트웨어의 포크를 가리킬 때 사용하는 용어다. 많은 알트코인이 만들어졌고, 많이 알려진 코인은 다음과 같은 것들이 있다.

- 솔리드코인
- **라이트코인**
- 도지코인

### 2.0 체인

포크가 아닌, 최초부터 구축한 프로젝트들도 있다.

- 넥스트
    - 극초기의 비트코인 2.0 프로젝트로, 좀 더 프로그램적이고 유연한 블록체인을 만드려는 아이디어다.
- 카운터파티
    - 최초의 비트코인 2.0 프로젝트 중 하나로, 비트코인의 블록체인 확장 프로토콜이지만 훨씬 더 많은 프로그래밍 기능을 제공하는 것을 목표로 했다.

### 개인정보 보호에 중점을 둔 암호화폐

암호화폐가 확산되기 시작한 후 많은 사람들은 블록체인에 얼마나 많은 금융 데이터가 보관되고 있는지 우려하여, 프라이버시에 중점을 둔 암호화폐가 등장하기 시작했다.

- 대시
    - 비트코인의 소프트웨어 포크다.
    - X11 이라는 새로운 유형의 ASIC 저항 작업 증명을 구현했다.
- 모네로
    - 작업 증명을 위해 크립토노트 프로토콜을 사용한다. 크립토노트는 키를 소유한 사용자 집단이 특정 정보를 숨길 목적으로 사용가능한 일종의 디지털 서명인 **링 시그니처** 라는 기술을 사용한다.
- 지캐시
    - 영 지식 증명(zk-SNARK5)으로 사용자의 개인정보를 보호한다.

### 리플과 스텔라

- **리플**
    - 비트코인에 영향을 받아 탄생했고 초창기부터 가장 오랫동안 지속되는 대안 암호화폐들 중 하나다. 은행 및 결제 분야의 다양한 기업과 수백 개의 파트너십을 맺고 있다.
    - 기존 서비스에 합의 알고리즘을 적용해 XRP 라는 암호화폐를 만들었다.
    - 트랜잭션에 대한 노드 합의가 필요한 **비잔틴 장애 허용(BFT)** 정책을 사용한다.
- 스텔라
    - 초기에는 리플과 비슷한 합의 매커니즘을 사용했으나, 예기치 않게 포크되면서 별도 네트워크가 생기고 트랜잭션에 문제가 생겨 스텔라 합의 프로토콜(SCP) 로 변경했다.

### 블록체인 확장

- **세그윗** *
    - 비트코인 인프라의 병목 현상이 분명해지고, 블록마다 허용치보다 더 많은 트랜잭션이 쌓이기 시작했다. 이는 허용치 이상의 트랜잭션은 처리되지 못하고 멤풀에 남게 되며, 수수료가 비싸질 수 있다는 의미이다. 이 문제를 해결하기 위해 **세그윗** 기술을 구현하는 제안이 나왔다.
    - 세그윗은 서명(Signature) 부분을 Witness 라는 데이터 영역으로 분리시키는 것이다.
    - 레거시 네트워크에 트랜잭션을 보내기 전, 기존 TXID 에서 Input 의 서명을 변경하는 해킹을 통해 새로운 TXID2 를 만들어 낼 수 있다. **세그윗 거래는 이 가변성을 제거하여 TXID 를 안정적으로 만든다.**

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/831e0393-1744-4b10-bedf-7a6b5261cf3a" />
</p>

- 라이트닝
    - 라이트닝 네트워크는 거래 확인을 위해 채굴자와 블록을 요구하는 대신, 당사자 간의 서명을 사용해 암호화폐 송수신 여부를 디지털로 검증한다. 검증은 양방향 결제 채널을 통해 이뤄진다. 네트워크는 **해시 시간 잠금 계약** 이라는 다중 서명 시스템으로 당사자들이 서로 거래할 수 있도록 한다.

### 이더리움 클래식 포크

2016년 DAO 스마트 콘트랙트 실행 과정에서 취약점을 악용하여 5천만 달러 규모의 해킹에 대한 대응으로 발생했다. 해킹을 역전시킨 새로운 코드로 소프트웨어를 업데이트 했고, 해당 블록체인은 여전히 이더리움으로 본다.

해킹을 되돌리기 위해 새롭게 발급된 업데이트 소프트웨어에는 리플레이 보호 기능이 포함되지 않았고, 소유자들은 별도의 해결책을 찾아야 했다.

<p align="center">
    <img width="600" alt="Image" src="https://github.com/user-attachments/assets/c1a2aad1-40ab-49ed-9ebf-9d9aa77b8564" />
</p>
