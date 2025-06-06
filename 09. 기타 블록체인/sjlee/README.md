# 1. 블록체인은 무엇에 좋은가?

비트코인, 이더리움과 같은 오픈 블록체인과 달리, 기업 및 단체에서 관심있어 하는 블록체인의 용도는 조금 다른 경우도 많다.

## 1.1. 블록체인 핵심 기술

- **합의(Consensus)**
    - 새로운 레코드의 유효성을 검증하여 잘못된 데이터의 파손을 방지한다.
- **해시(Hashing)**
    - 레코드를 통해 감사 추적을 유지하고, 데이터 위·변조를 어렵게 만든다.
- **암호화(Encryption)**
    - 디지털 데이터의 안전한 전송을 보장한다.
- **분산화(Distribution)**
    - 퍼블릭 원장 레코드를 여러 참여자가 공유하도록 한다.

## 1.2 블록체인의 주요 기능

위 핵심 기술을 기반으로 파생된 기능들은 아래와 같음

1. **자기조직화(합의)**
    - 블록 생성 간격에 관계없이 일정한 시간 단위로 데이터를 처리한다.
2. **영구적인 레코드(해시)**
    - 한 번 배치된 블록은 수정하기 매우 어려움 → 불변성
3. **자산 이동(암호화)**
    - 중개자 없이 자산 이동 가능 (초기에는 암호화폐 중심으로 시작)
4. **데이터 공유(분산화)**
    - 여러 당사자가 신뢰 없이 데이터를 공유하며 협업 가능

기존 기술이 해결하지 못한 문제를 해결하기 위해 블록체인을 활용할 이유가 많아짐.

오픈 블록체인이 투기 성격을 띄운 것과 달리, 비즈니스의 사용사례를 알아보면 꽤나 많음. 기업이 고려해야할 것은 아래와 같다.

- 블록체인은 거래 상대방이 합의할 수 있는 트랜잭션 메커니즘인가?
- 블록체인으로 작성해야 하는 데이터의 종류에 대해 당사자가 합의할 수 있는가?
- 블록체인 기술로 문제를 해결할 수 있는가?

위 질문에 답할 수 있어야 함.

## 2. 데이터베이스와 원장

원장이란 기록 보관 시스템을 설명하는 데 사용되는 용어다. 무허가 원장은 암호화 기반 블록체인을 묘사할 때 쓴다.
→ 비트코인, 이더리움과 다양한 포크, 대부분의 알트코인이 포함됨
→ 록체인은 허가를 받아야 하는 중앙집중식으로 운영되지 않기 때문에 퍼미션리스(무허가) 블록체인이라고도 불림(누구나 참여 가능)
→ 퍼미션리스 블록체인은 계좌와 결제가 내장된 분산 컴퓨팅 시스템이다. 

분산 원장 기술(DLT, Distributed Ledger Technology)은 블록체인 기반의 원장 데이터베이스를 잘 설명하는 용어로, 특히 **기업(엔터프라이즈) 환경**에서 자주 사용된다.
DLT는 기존 데이터베이스 인프라와 달리, **새로운 스키마를 도입하여 실시간으로 데이터 읽기 및 쿼리가 가능**하다.
다만 이 실시간성이 항상 유지되는 것은 아니고, 합의 기반 시스템의 특성상 일정한 지연(레이터시)이 발생할 수 있으며, 시계열에 따라 달라질 수 있다. 이로써 DLT는 단순한 중앙형 데이터베이스와 다른 **동적이고 개방형 구조**를 가짐

중앙집중식 데이터베이스는 그 자체로 문제가 있는 것은 아니며, 오랫동안 검증된 방식으로 운영되고 있습니다. 그러나 블록체인 기술은 중앙집중식 시스템의 한계를 극복하기 위해 등장했다. 특히 **중앙 집중형 인센티브 모델**(예: SNS의 타겟 광고, 온라인 시장의 수수료 등)과 달리, 블록체인은 참여자들이 **합의된 인센티브를 통해 자율적으로 정보와 가치를 공유**할 수 있는 방식을 제공합니다. 이 점은 블록체인이 단순한 기술적 혁신을 넘어 **새로운 경제적·사회적 시스템**으로 주목받는 이유 중 하나입니다.

# 3. 탈중앙화와 중앙집중화

- **초기 암호화폐 기술**은 탈중앙화를 핵심 가치로 삼았음
- 그러나 기업용 블록체인(특히 조직용 플랫폼)은 훨씬 **중앙집중적**인 성격을 띠고 있다.

## 3.1 참가자

- **비트코인처럼 공개된 블록체인**에서는 누구든 채굴 장비만 있으면 네트워크에 참여하여 블록을 생성할 수 있다.
- 하지만 **기업용(엔터프라이즈) 블록체인**에서는 참여자가 제한됩니다. 단순히 '참여만 하는 것'이 아니라, **승인된 참여자**여야만 한다.
- 이 차이점은 **탈중앙형 블록체인**과 **중앙집중형 블록체인**의 중요한 차별점.

## 3.2 분산 검증 원장의 주요 특성

구글 리서처 벤 로리(Ben Laurie)는 퍼미션리스 블록체인의 핵심 특성을 설명하기 위해 **분산 검증 원장 프레임워크**를 제시했다. 각 블록체인은 기술적 구현 방식이 다르므로, 모든 시스템에서 공통으로 고려해야 할 몇 가지 **핵심 구성 요소를 가짐.**

### 3.2.1 승인 통제 (Admission Control)

- 누가 원장에 데이터를 기록할 수 있는지 **승인 기준**을 정해야 한다.
- 이 승인 통제는 보안의 핵심으로, IT 시스템에서도 매우 중요한 역할을 한다.

### 3.2.2 합의 (Consensus)

- 블록체인 네트워크에서 정보의 유효성을 **모두가 동의**해야만 한다.
- 증명 방식(예: 작업 증명, 지분 증명 등)은 다를 수 있지만, **합의**는 블록체인의 근간이 되는 규칙이다.

### 3.2.3 검증 (Verification)

- 네트워크에서 일어나는 사건(트랜잭션 등)이 **정확히 수행되었는지** 검증하는 절차
- 승인 통제, 합의, 검증은 모두 블록체인 시스템의 **신뢰성을 보장**하는 구성 요소

### 3.2.4 집행 (Enforcement)

- 규칙을 유지하기 위해 '집행'이 필요
- 예를 들어 비트코인은 가장 긴 체인에 따라 네트워크 전체가 동의하게 되는데, 이 방식이 바로 집행의 한 예시다.
- 새로운 블록을 추가할 때 이전 체인의 **체크포인트**를 포함해 모든 체인이 일관되도록 한다.

# 4. 이더리움 기반 프라이버시 구현

퍼블릭 블록체인(예: 이더리움)과 암호화폐 네트워크는 **기업 환경에 바로 적용하기 어려움**이 있다. 왜냐하면, **규제 준수, 경쟁 문제, 개인정보 보호** 때문에 데이터를 쉽게 공개할 수 없기 때문이다. 
→ 이 문제가 해결된다면, 블록체인 기술은 기업에서도 다양한 방식으로 활용될 가능성이 크다.
→ 따라서 기업은 이더리움 같은 블록체인을 포크(변형)해서 **개인정보 보호 기능이 포함된 맞춤형 시스템**을 만들어야 한다.

## 4.1 나이트폴

나이트폴은 회계법인 EY(언스트앤영)가 만든 이더리움 기반 시스템

특징

- 스마트 계약(스마트컨트랙트)에 **개인정보 보호 기능**을 추가.
- **ERC-20 및 ERC-721 토큰**을 프라이빗 블록체인 환경에서 사용 가능하게 함.
- 영 지식 증명(Zero Knowledge Proof)을 사용하여 개인정보를 안전하게 증명.

기술

- 조크라테스(Zokrates)라는 라이브러리를 통해 영 지식 증명을 손쉽게 제공함
- 자바 언어로도 제공되어 사용 편의성을 높임

## 4.2 쿼럼

쿼럼은 투자은행 **JP모건**이 개발한 이더리움 기반 블록체인

특징

- **프라이빗 트랜잭션**과 **프라이빗 스마트 계약**을 지원하여 **익명성**을 강화.
- 이더리움 엔지니어들이 사용하기 편하도록 기존 개발 도구와 **호환**됨.

기술

- **Zether 프로토콜**을 적용해 영 지식 증명 방식을 사용.
- ERC-20 스마트 계약에 연결되어 **프라이빗 계좌**를 만들 수 있음.

보안

- 대칭키 암호화 방식으로 **엘가말(ElGamal) 암호화**를 사용해 각 계정 잔액을 보호.

## 4.3 GPT에 물어본 프라이빗 계좌 특징

1. **거래 내용 비공개**
    
    프라이빗 계좌에서는 거래 금액, 상대방 주소 등 **거래 내역이 외부에 노출되지 않도록** 설계됩니다.
    
2. **익명성 보장**
    
    거래가 발생해도, 누가 보냈고 얼마를 보냈는지 **제3자가 알 수 없도록** 만듭니다. 이게 바로 '영 지식 증명(Zero Knowledge Proof)' 같은 기술이 쓰이는 이유예요.
    
3. **프라이빗 스마트 계약 연계**
    
    ERC-20(이더리움 토큰 표준) 같은 스마트 계약도 **비밀스럽게 작동**할 수 있게 지원합니다.
    
4. **암호화로 보호**
    
    예를 들어 쿼럼에서는 **엘가말(ElGamal) 암호화** 같은 고급 암호화 기술을 써서 계좌 잔액 자체를 암호화합니다. 이 덕분에 네트워크상에서 계좌 정보가 **완전히 보호**됩니다.
    

# 5. 엔터프라이즈 구현

- 많은 기업들이 **이더리움으로 블록체인을 시작했지만**, 처음부터 자체 솔루션을 구축하기도 함
- 이더리움 외에 **독립 블록체인**을 연구하고 구축하는 사례도 많다.

## 5.1 하이퍼레저

- **리눅스 재단**이 주도하는 오픈소스 블록체인 개발 플랫폼. → 그냥 **오픈소스 블록체인 프로젝트 모음인듯**
- 가장 유명한 프로젝트:
    - **패브릭(Fabric)**: Go 언어로 구현된 원장 기술.
    - **알로하(Iroha)**, **쏘투스(Sawtooth)**: 다양한 환경 지원(C++로 구현).
- 기능: 스마트 컨트랙트, 거래, 합의 등을 지원.
- IBM, 오라클 등 대형 기업들이 이 프레임워크를 기반으로 솔루션을 개발 중.

## 5.2 코다

- 금융업계에 초점을 맞춘 **R3 컨소시엄**의 프로젝트.
- 특징:
    - **JVM(Java Virtual Machine)** 기반으로 작동 → 기존 개발자들이 쉽게 적응.
    - 관계형 데이터베이스와 호환돼 **쿼리가 쉽다**.
    - 스마트 컨트랙트는 코드와 함께 **법률 언어**도 사용.

## 5.3 코다 동작 방식

코다는 **기업 간 거래를 신뢰성 있게 관리**하기 위해 고안되었다.

<img width="590" alt="image" src="https://github.com/user-attachments/assets/ff917453-ecc5-4b83-b5ab-c299cf2f5e0e" />


코다가 없으면, 두 회사의 데이터베이스가 고립된다. → 거래 이력 관리가 복잡해짐

코다를 사용하면, DB가 연결돼 더 쉽고 효율적으로 관히라 수 있게 된다.

예를 들어, 제조업체가 부품을 출하할 때, 공급망 관리에서 추적에 용이할 것이다. 모든 사업은 이런 관계를 갖고 있고, 회사가 파트너십을 맺을수록, 추적하기 위해 더 많은 노력과 자원이 필요하다.

기업이 볼 수 있는 퍼블릭 블록체인의 속성은 크게 두 가지다.

- **트랜잭션 불변성**: 한 번 기록되면 변경·삭제 불가
- **피어 검증**: 다른 참가자들이 거래의 유효성을 판단

기업 입장에서 매력적이지 않은 속성도 있다.

- **트랜잭션 투명성**: 모든 참가자가 거래 내용을 열람 가능 → 기업에 불리.
- **제한된 확장성**: 초당 거래 수가 제한됨.
- **새로운 언어와 개념 필요**: 솔리디티 등 익혀야 함 (러닝커브)
- **퍼미션리스**: 퍼블릭 블록체인은 누구나 네트워크에 참여할 수 있지만,  회사는 거래 대상을 통제하고 싶어 함
- **숨겨진 정체성**: 익명성이 높아 기업은 거래 상대를 알기 어려움.

## 5.4 코다 네트워크

코다 네트워크는 **노드의 피어 투 피어 네트워크**다. 각 노드는 법적 주체를 대표하며, 노드마다 하나 이상의 코다 응용 프로그램으로 코다의 인스턴스를 실행한다.

<img width="618" alt="image" src="https://github.com/user-attachments/assets/2ec9f18f-1b36-46a7-ae68-09133e42d779" />


참여 조건:

- 운영자 승인 필요
- 모든 노드가 TLS(보안 연결)로 직접 통신 → TLS 통신을 사용한 비공개 통신

네트워크의 각 노드는 **자체 중앙집중형 데이터베이스**를 가지고, 모든 거래는 피어 투 피어로 수행된다. 각 노드가 거래를 자신의 DB에 저장하는 방식임.
아래 그림과 같이, 트랜잭션에 관련된 노드 또는 액세스가 주어진 노드만 트랜잭션에 대한 가시성이 있음.
→ 밥은 엘리스와 1,7 번 트랜잭션을 실행했고, 칼과 5, 6 트랜잭션 수행함
→ 밥은 4개 다 볼 수 있지만, 엘리스는 1번과 7번만 볼 수 있음
→ **변조 방지 기능**과 **디지털 서명**으로 신뢰 확보.

<img width="576" alt="image" src="https://github.com/user-attachments/assets/7d134b65-5f03-4e8f-92be-80209b241daa" />


거래가 원장에 포함되려면 다음 두 가지 검사를 통과해야 한다.

1. **타당성 합의**
    - 트랜잭션에 필요한 모든 서명이 유효하다.
    - 트랜잭션은 관련된 스마트 콘트랙트에 정의된 모든 제약을 충족한다.
2. **고유성 합의**
    
    코다는 비트코인과 유사한 UTXO 모델을 따른다. 고유성 검사를 통해 UTXO를 확인하고, 이중 지출을 방지한다.
    

+) 코다 디앱은 자바로 작성되었음. 

# 6. 서비스로서의 블록체인

공급업체가 맞춤형으로 구현이 쉬운 솔루션을 제공하는 ‘서비스로서의 블록체인(BaaS)’이라는 블록체인 개념은 기술 활용 사례가 늘어나면서 성장 가능성이 크다.

## 6.1 아마존 퀀텀 레저

아마존 웹 서비스의 일부인 퀀텀 레저 데이터베이스(QLDB)는 암호화로 보호되며, 이더리움과 하이퍼레저 패브릭 프레임워크를 사용하는 원장이다.

## 6.2 애저

애저 클라우드 플랫폼은 개발자들이 쿼럼과 코다와 같은 다양한 블록체인을 배치할 수 있도록 분산 모델을 제공한다. 스마트 계약 개발과 배포도 지원하며, **데이터베이스와 연동된 쿼리**를 쉽게 처리할 수 있게 한다.

## 6.3 VM 웨어

- EVM, DAML, 하이퍼레저 등 **멀티 블록체인 플랫폼**을 지원.
- 탈중앙화 기능을 높이는 다양한 옵션도 선택할 수 있음

## 6.3 오라클

- 하이퍼레저 패브릭 기반의 블록체인 환경을 제공합니다. → 하이브리드, 온프레미스 또는 두 가지 혼합해 유연성을 높임
- 기존 DB와 연계해 블록체인 테이블을 지원한다. → 이 테이블은 데이터 보호 및 감시 기능까지 포함

이외에 IBM, SAP도 각각 스마트 컨트랙트 개발 툴, 이더리움 메인넷 지원 등을 하며 다양한 솔루션을 제공한다.

# 7. 뱅킹

대형 금융기관과 중앙은행들은 현재의 시스템이 **비효율적이며 비용이 많이 드는 문제**를 겪고있다. 이를 개선하기 위해 블록체인 도입을 실험하고 있지만, 아직 완전히 적용된 것은 아니며 **시범 단계**에 머물고 있다. 

## 7.1 로열 민트

- **영국의 로열 민트**는 시카고 상업 거래소(CME)와 협력해 금 기반의 **블록체인 자산**을 개발했습니다.
- 암호화폐 기업인 비트고(BitGo)가 **지갑 및 KYC(본인인증) 시스템**을 제공하려고 했으나, 2018년 말 프로젝트가 중단되면서 실현되지 못했습니다.

## 7.2 프랑스 중앙은행

- 프랑스 중앙은행은 2016년부터 **블록체인을 활용한 디지털 정책 실험**을 시작.
- 특히 하이퍼레저, 코다, 쿼럼 등 다양한 플랫폼을 테스트하며 규제 프레임워크 마련에 집중.
- 최근에는 블록체인 전문가를 채용하며 전문성을 강화하고 있음.

## 7.3 중국

- **2019년**, 중국 정부는 **블록체인 발전 가속화 정책**을 발표.
- 중앙은행이 **암호화폐와 유사한 디지털 화폐**를 준비 중이며, 현금과 유사한 오프라인 결제 기능까지 포함할 계획임.

## 7.4 연방준비제도 (FRB)

- 미국 연방준비제도는 2019년 보스턴 연방준비제도이사회는 이더리움과 하이퍼레저 기반 블록체인 테스트를 기술한 논문을 발표함
- 다양한 은행과 스마트 계약을 대표하는 월렛을 사용하며, FRB에 대한 지급을 조정함
    
    <img width="602" alt="image" src="https://github.com/user-attachments/assets/d595991c-ce9c-43da-8ccc-9802f192005e" />

    
    - 좌측: 전통적인 IT 환경, 블록체인과 상호작용하는 톰켓 웹 서버
    - 우측: 하이퍼레저 패브릭 블록체인 네트워크, 여러 노드(Peer 1 ~ 4)와 멤버십 서비스로 구성
    → 멤버십 서비스는 네트워크에 참여할 자격을 검증하는 역할을 한다.

## 7.5 JP모건

- JP모건은 이더리움 기반으로 **쿼럼(Quorum)**을 개발했고, 자체 스테이블코인인 **JPM코인**을 발행.
- 이 시스템은 **국제 송금**에도 사용할 수 있으며, 은행 간 피어 투 피어 지불을 구현하는 모델입니다.

# 8. 퍼미션드 원장 사용

퍼미션드 시스템은 개방형 블록체인의 사례와 매우 다르다. 개방형 블록체인은 **투기, 토큰화, 디지털 자산 저장** 등에 유리하지만, 퍼미션드 블록체인은 **속도, 개인정보 보호, 인증, 보안**면에서 기업에 더 적합하다.

기업들은 테스트 및 검증을 거친 **맞춤형 허가형 플랫폼**을 통해 자신들의 요구사항을 만족시킨다.

## 8.1 IT

- **보안**은 모든 엔터프라이즈 IT 시스템에서 필수적인 요소
- **DAML SDK**(디지털자산사의 스마트 계약 도구)는 비주얼 스튜디오 등 친숙한 개발 환경에서 쉽게 개발 가능하도록 지원
- 원장과 관련된 **스마트 컨트랙트는** 시스템 내 중요 데이터를 검증하는 데 큰 역할을 한다.
가령 컨트랙트를 활용해 소프트웨어 패키지나 도커 이미지를 검증할 수 있음

## 8.2 뱅킹

증권화, 현금화, 결제 시스템에 이르기까지 은행들과 중앙은행 모두 블록체인 기술을 연구하고 있다.

은행은 여러 다른 조직과 함께 운영해야 하기 때문에, **블록체인은 서로 다른 단체들이 모두 동의하고 신뢰할 수 있는 중개자 역할을 할 수 있다**. 산탄데르 은행이 발행한 디지털 채권이 대표적인 예시임

<img width="654" alt="image" src="https://github.com/user-attachments/assets/69b7b194-c778-4d32-9016-bf330ad710a0" />


- 관리인, 발행인 및 투자자들이 이 과정에서 토큰을 사용함

## 8.3 중앙은행 디지털 통화

- CBDC(Central Bank Digital Currencies)는 한 나라의 법정화폐를 디지털화한 형태.
- 특징:
    - **중개자(은행)** 없이 당사자 간에 실시간 결제 및 지불 가능.
    - 기존 데이터베이스도 사용되지만, **블록체인이나 분산원장 기술**도 고려됨.
- 주요 테스트 국가: **중국, 미국, 스웨덴, 영국 등.**

## 8.4 법률 분야

- 법률 절차는 **복잡하고 중립적**인 검증이 필요.
- 블록체인은 불법 방지와 **법적 정보 검증**에 활용될 수 있다.
- 사례:
    - 미국 법무법인 **베이커호스틀러**가 화물 계약에 **스마트 계약**을 도입.

## 8.5 게임 분야

- 게임에서 **가상 아이템(무기, 의류 등)**은 가치가 크지만 특정 게임에만 국한됨.
- 이더리움 기반의 **크립토키티** 등 디지털 자산의 거래가 인기를 끌고 있음.
- 부정 행위 방지:
    - 예: **베를린 공과대학**의 체스 프로젝트는 이더리움 스마트 계약을 활용해 공정성을 확보.

## 8.6 헬스 케어

- 의료계는 **많은 데이터**를 생성하지만, 대부분 흩어져 있음.
- 구글은 데이터 기록을 암호화해 **원장 기반 시스템으로 검증**하는 방식을 연구 중.

## 8.7 결제 분야

### 법인 결제

- 대기업의 결제 과정은 **복잡하고 비용이 큼**.
- 블록체인은 청구서 관리 및 검증을 **자동화**할 수 있음.
- 사례:
    - **비자카드**: 2016년부터 관련 프로젝트 진행.
    - 2019년: 하이퍼레저 기반 **B2B 커넥트 서비스** 시작.

### 은행 간 결제

- 글로벌 송금 시 지불 정보 부족 문제가 있음.
- **JP모건**은 IIN(Interbank Information Network)을 개발해 은행 간 결제 정보를 안전하게 공유.

### 개인 간 결제

- 개인 간 송금의 **빠르고 저렴한 결제** 수단으로 블록체인이 주목.
- **페이팔**은 2019년 **컨브리지 블록체인**에 투자하며 이 문제 해결을 시도.

# 9. 리브라

대부분의 엔터프라이즈 블록체인 실험은 비즈니스 프로세스에 초점을 맞춤. 아직 초반이지만 페이스북과 같은 소비자 중심의 기업들은 특.히.나. 인터넷 결제 측면에서 모두에게 블록체인을 제공하고자 하는 낌새가 보이기 시작함..
→ **리브라는 페이스북이 주도하는 프로젝트의 이름**

## 9.1 리브라 협회

페이스북은 한동안 수십억 명의 사용자에 대한 블록체인 구현을 탐색했다. **리브라 협회**는 리브라는 완전히 새로운 블록체인 시스템을 구현하기 위해 **함께 모인 조직의 컨소시엄이다.**

다음은 역할 및 관련 회사다.

- 결제: PayU
- 기술: Facebook, FarFetch, Lyft, Spotify, Uber
- 통신: Iliad
- 블록체인: Anchorage, BisonTrails, Coinbase, Xapo
- 벤처 캐피탈: Andreessen Horowitz, Breakthrough Initiatives, Union Square
Ventures, Ribbit Capital, Thrive Capital
- 비영리 단체: Creative Destruction Lab, Kiva, Mercy Corps, Women’s World
Banking

## 9.2 기존 블록체인에서 빌려오다

**리브라 협회는 비잔틴 장애 허용 알고리즘을 활용해 새로운 결제 시스템을 만들려고 한다. 협회 회원들이 시스템의 validator가 됨**.

- 유효성 검사기로 클라이언트의 트랜잭션을 받아들이고 검증을 위해 투표 메커니즘을 사용한다.
    - 오류 또는 다운타임이 발생할 경우 다른 검증자가 선두를 차지할 수 있기 때문에 장애 허용성을 갖추고 있음
    
    <img width="555" alt="image" src="https://github.com/user-attachments/assets/40e2e66a-f105-4164-8416-5be5a65eb30a" />

    
- 리브라는 스마트 컨트랙트를 지원하고,  이를 통해 애플리케이션을 직접 만들 수 있게 설계됨.
- **Move**라는 자체 프로그래밍 언어로 스마트 계약을 작성

## 9.3 노비(Novi)

- **페이스북**이 거래를 쉽게 하도록 만든 **지갑 서비스** 이름이 **노비(Novi)**
- 노비는:
    - **메신저, 인스타그램, 왓츠앱 등** 다양한 플랫폼에서 사용할 수 있도록 설계.
    - KYC/AML(신원확인 및 자금세탁 방지) 기능이 필수.
- 노비 덕분에 리브라의 지갑 서비스는 쉽게 대중화될 수 있다는 장점이 있었음.

## 9.4 리브라 프로토콜의 동작 방식

리브라의 네트워크는 두 가지 유형으로 **유효성 검사기 노드**와 **풀 노드**가 있음. 

- **검증자 노드**
    - 역할: 트랜잭션을 **검증하고 처리**하는 주체.
    - 구성: **허가된 노드**만 가능, 리브라 협회의 멤버들이 이 노드를 운영
    - 메커니즘: **LBFT 합의 프로토콜**을 통해 블록 생성과 네트워크의 거버넌스를 관리

- **풀 노드**
    - **누구나 실행 가능**한 노드로, 주로 다음 두 가지 기능:
        - 리브라 블록체인의 **현재 상태를 실시간으로 브로드캐스트하는 역할.**
        풀노드는 블록체인의 전체 사본을 유지하고, 블록체인에서 읽어야 하는 클라이언트 요청에 응답.
        - 검증자가 처리한 트랜잭션을 **재확인**
    - 이 풀 노드는 **검증자 노드의 부하를 줄여주고**, DDoS 공격 등에서 검증자 노드를 **보호**하는 역할도 한다.
    → 예시: 리브라 **모바일 지갑**이 트랜잭션 요청을 검증자 노드에 보내기 전에 풀 노드에서 데이터를 읽고 요청을 처리한다.

### 9.4.1 LBFT 합의 프로토콜

- 트랜잭션 처리와 블록체인의 거버넌스를 정의하는 **규칙 집합.**
- 모든 검증자 노드들이 서로를 식별하고 신뢰할 수 있도록 설계됨.
    - 네트워크상의 모든 검증기 노드가 식별돼 서로 신뢰하고 있어도, 어느 시점에서 한 개 이상의 노드가 악의적인 행위자가 돼 네트워크상의 비활성 트랜잭션을 포함시킬 수 있는 위험이 있다.

### 9.4.2 블록

- 비트코인의 **PoW(Proof-of-Work)**처럼 복잡한 블록 생성 권한 경쟁이 없고 **빠른 합의**가 특징.
- 초당 **약 1000건**의 트랜잭션 처리 속도를 목표로 함.
    - 비트코인의 초당 7건의 트랜잭션과 비교됨..
- 리더가 새로운 트랜잭션을 제안하면 모든 네트워크 검증자가 해당 블록이 유효한지 투표를 진행한다.
    - 2f+1개 이상의 검증자가 블록이 유효하다고 동의하면 쿼럼 인증서가 생성됨
        - 이때, f는 비잔틴 장애를 일으킬 수 있는 최대 노드 수
    - 쿼럼 인증서는 다음 블록에 연결되며 모든 블록을 상위 블록에 암호화해 연결
    - 블록이 완전히 확정되려면, **3개 연속 QC 증명서**가 있어야 한다.
    
    <img width="585" alt="image" src="https://github.com/user-attachments/assets/a1445e4b-4b6e-49f4-b312-681ba6256aad" />

    
    - 블록 #102의 쿼럼 증명서가 포함돼 있는 경우 블록 #103이 네트워크에 제안될 때까지 블록 #100은 블록체인에 커밋되지 않음

### 9.4.3 트랜잭션

리브라의 트랜잭션은 이더리움과 유사한 방식으로 구성. 또한, 계좌 모델을 따르기 때문에 입력과 출력이 없다.

<img width="757" alt="image" src="https://github.com/user-attachments/assets/d23e17f9-d374-4059-ba27-2e884463f3c7" />
