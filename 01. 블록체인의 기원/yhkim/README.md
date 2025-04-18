# 1장. 블록체인의 기원

## 전자시스템과 신뢰

---

- 인터넷만 가능하다면 대부분 무료로 정보를 사용할 수 있다.
    - 반면 온라인 제품이나 서비스 대부분 제3자인 개인 또는 법인이 중개자 역할을 수행해야 했다.

- 두 가지 유형의 신뢰
    - 중개자 신뢰: 합리적이고 공정한 결정을 내리기 위해 제3자인 개인 또는 법인의 신뢰에 의존한다.
    - 신탁 발행: 모든 가치의 안전과 보안을 보장하기 위해 제3자인 개인 또는 법인의 신뢰에 의존한다.

- 돈은 디지털화됐으며, 금융 거래는 중개자의 신뢰와 신탁 발행자의 신뢰에 의존해 주요 영역에서 사용됐다.
    - 아날로그에서 디지털로 가치가 이동할 때 관련된 여러 당사자 간에 신뢰 요소가 있어야 한다.
    - 하지만 2008년 금융위기는 사람들을 잠시 멈추게 했고, 금융기관을 바라보는 맹목적인 신뢰와 믿음은 생각했던 것과는 다르다고 생각하기 시작했다.

❗블록체인은 잃어버린 신뢰를 회복하기 위한 노력이다. 여러 기술 중에 암호화 기술로 제3자에 관한 신뢰를 자동화하고 강화한다.

- 블록체인을 사용하는 최초의 작동 시스템은 비트코인이었다.
    - 비트코인이 있기 전에, 선행 연구자들은 비슷한 개념을 만들려고 시도했지만 실패했다.
    - 인터넷 시스템만으로는 진정으로 분산된 신뢰 시스템을 구축할 수 없었기 때문이다.

## 분산화 vs 중앙집중화 vs 탈중앙화

---

- 인터넷: 분산 기술로 설계됐지만 중앙집중화 애플리케이션과 분산화 애플리케이션이 혼합된 형태

- 분산화
    
    ![그림 1-1. 분산된 디자인을 가진 자전거 바퀴](./image/image.png)
    
    그림 1-1. 분산된 디자인을 가진 자전거 바퀴
    
    - 블록체인 기술의 분산 특성: 개별 사용자에게 더 많은 통제권을 줌으로써 소수의 대기업에 의한 웹의 지배력을 완화하는 데 도움이 될 수 있게 하는 것
    - 분산 시스템: 단일 노드(Node) 고장이 전체 네트워크의 고장을 뜻하지 않는다.
        - 목표: 다수의 컴퓨터에 책임을 분산시키고 처리 능력을 활용해 공동으로 작업을 수행하는 것
    - AWS(Amazon Web Services)에 호스팅되는 여러 데이터베이스와 마찬가지로 분산 데이터베이스에서 각 노드는 같은 데이터의 복제된 복사본을 유지할 수 있다. 각 노드는 다른 노드의 id를 알고 있으며, 모든 노드는 하나의 개체에 의해 제어된다.
        
        ![image.png](./image/image%201.png)
        
- 중앙 집중화
    - 기업들: 구글, 페이스북, 애플, 아마존
    - 페이팔과 같은 중앙집중화 데이터베이스에서 모든 노드는 하나의 개체에 의해 제어되는 단일 중앙 노드에 연결된다.
        
        ![image.png](./image/image%202.png)
        
- 탈중앙화
    - 완전히 탈중앙화된 시스템에서는 특정 노드가 자신의 목표를 달성하기 위해 반드시 모든 다른 노드와 협력할 필요는 없으며, 결정은 합의를 통해 이뤄지며 단일한 개체에 책임을 맡기지 않는다.
    - 비트코인의 블록체인과 같은 분산화 데이터베이스에서 각 노드는 같은 데이터의 복제된 복사본을 유지할 수 있고, 각 노드는 다른 노드의 식별을 모를 수 있으며, 모든 노드는 익명의 많은 개체에 의해 제어된다.
        
        ![image.png](./image/image%203.png)
        

![그림 1-2. 중앙집중화, 탈중앙화 및 분산화 네트워크 설계](./image/image%204.png)

그림 1-2. 중앙집중화, 탈중앙화 및 분산화 네트워크 설계

## 비트코인 이전 모델들

---

- 비트코인이 출시되기 전인 2009년 이전까지만 해도 사용자의 화폐 통제는 아날로그(현금 또는 수표)에서 디지털(인터넷뱅킹 등 전자금융)로 전환한 것 외에는 큰 변화가 없었다.
    
    → 여전히 중앙집중식
    
- 비트코인 이전에 많은 디지털 통화 개념의 최종목표: 재정권리를 증가시키거나, 사용자(서비스 사용자)의 돈에 관한 더 나은 통제를 하고자 했다.

- 재정권리(Financial Rights): 개인이나 단체가 경제적 자원을 소유하고 활용할 수 있는 법적 권리
    - 돈이나 자산을 관리하고 사용할 수 있는 권리를 포함한다.
    - 재정권리의 주요 요소
        1. 소유권(Property Rights)
            - 개인이나 기업이 자산(부동산, 금융자산, 지적 재산 등)을 소유하고 이를 자유롭게 처분할 수 있는 권리.
        2. 거래 및 계약 권리(Contract Rights)
            - 재정적 계약(예: 대출, 투자, 보험 등)에 참여하고, 법적으로 보호받을 수 있는 권리.
        3. 임금 및 노동 권리(Wage and Labor Rights)
            - 노동을 통해 정당한 보수를 받을 권리.
            - 근로 계약에 따른 급여를 받을 권리.
        4. 금융 서비스 접근 권리(Access to Financial Services)
            - 은행 계좌 개설, 대출, 보험, 투자 등의 금융 서비스를 이용할 수 있는 권리.
        5. 세금 및 정부 지원 관련 권리(Taxation and Welfare Rights)
            - 합법적인 세금 감면 혜택을 받을 권리.
            - 정부의 복지 프로그램(연금, 보조금 등)을 이용할 권리.
        6. 소비자 금융 보호 권리(Financial Consumer Protection)
            - 금융 상품(예: 대출, 투자, 보험) 이용 시 불공정한 계약이나 사기로부터 보호받을 권리.
    - 재정권리의 중요성
        - 경제적 자유와 독립성을 보장.
        - 금융 사기, 착취, 부당한 경제적 조치로부터 보호.
        - 안정적인 생활을 유지하고 자산을 관리할 수 있도록 지원.

### 디지캐시

---

- 1989년 데이비드 차움이 설립, 온라인에서 익명 디지털 결제를 가능하게 함
    - 자체 통화(사이버벅스)를 가졌으며, 가입한 사용자는 사이버벅스(토큰 or 코인)로 100달러를 받았다.
    - 신용카드와 유사한 방식의 보안 마이크로칩 스마트 카드를 개척했고, 가치를 저장하기 위한 디지털 지갑 개념을 만들어냈다.
    - 일부 은행(도이치 은행 등)과 소수의 상인들이 디지캐시 시스템을 시험 운영했지만, 1990년에 인터넷 상거래는 매우 낯선 개념이었다.
    - 사생활에 민감한 많은 사용자들이 사이버벅스를 사용하기 시작했지만, 시대의 장벽에 부딪혀 1998년에 파산했다.

### E골드

---

- 1996년 설립된 디지털 상점, 실제 귀금속 단위의 지원을 받았다.
    - 2006년까지 350만 개가 넘는 계정과 하루 590만 달러의 물량을 처리하고 있었다.
    - 인터넷에서 소액(1만분의 1그램의 금만큼 작은 액면가) 결제 개념을 도입한 최초 플랫폼
    - 중앙 집중형 시스템인 E골드는 어떤 개인의 신원과 계정을 연결하는 메커니즘이 없었다.
        - 악의적인 목적으로 사용돼 돈세탁, 온라인 사기 및 기타 불법 활동이 쉬워졌다.
    - 2008년 미국 정부가 폐쇄했다.

### 해시캐시

---

- 1997년 아담 백이 고안했다.
    - 인터넷에만 존재하는 돈의 개념을 포함해 디지털 자금의 타당성을 확인하기 위해 작업 증명(Proof-of-Work, PoW) 방식을 도입했다.
        - 작업 증명: 컴퓨터가 전자화폐가 어떤 가치를 가지려면 일종의 검증 가능하고 계산 집약적인 출력을 생성해야 한다는 것을 의미
    - 해시캐시는 작업증명을 통하여(SHA-1 해시 알고리즘을 사용) 컴퓨터가 특정 연산을 수행하고 난 뒤 결과를 제출하도록 요구, 이를 통해 스팸 방지 및 이중지불(Double Spending) 문제 해결을 목표로 했다.
    - 마이크로소프트와 아파치의 이메일 시스템에서 테스트했지만 결국 성공하지는 못했다.
        - 인터넷 기반 화폐에 필요한 디지털 희소성을 어떻게 도입하는지를 보여주는 좋은 사례였지만 기술 자체는 디지털 화폐의 좋은 형태가 아니었다.

### 비머니

---

- 1998년 웨이 다이가 제안, 정부 시스템 외부의 화폐 창출을 촉진하기 위해 컴퓨터 과학을 사용하는 개념
    - 해시캐시처럼, 비머니는 디지털 머니가 계산 또는 작업 증명서를 통해 생산될 수 있다고 제안했다.
    - 금 및 기타 상품과 같은 실제 자산 바구니를 기반으로 가격이 책정되며 공급을 제한한다.
        - 인플레이션 또는 시간이 지남에 따라 가치가 손실되는 것 보호
    - 거래 내용을 네트워크 전체로 전파하는 아이디어로 발전시켰다.
        - 거래 내용 메시지가 네트워크에 전송되면, 디지털 계약 시스템에서 실행된다.
        - 결제와 계약상 문제 시행을 위해 암호화로 네트워크 사용자들의 익명성을 보장한다.
    - 비머니는 익명 분산화 시스템에서 실행하는 계약 개념을 적용했으며, 돈을 벌기 위해 작업 증명서를 사용하는 개념을 도입했다.
    - 그러나 대부분 웨이 다이의 이론에 불과했다. 통제된 통화 공급을 통해 인플레이션의 영향을 받을 수 없는 비정부 화폐의 개념을 탐구하는 것이 목적이었다.

### 비트골드

---

- 2005년 닉 재보가 제안, 귀금속의 희소성을 디지털로 영역을 가져오는 것이었다.
    - 금과 같은 재료는 가치가 있지만 위조가 어려움. 금의 가치를 디지털화하고자 했다.
    - 작업 증명 중 '클라이언트 퍼즐 함수' 유형을 활용했다.
        - 컴퓨터에서 생성된 도전 문자열을 사용해 분산된 방식으로 안전하게 타임스탬프를 표시하는 방법이다. 그 후 디지털 방식으로 소유권 증명을 제공하기 위해 분산 소유권 등기처에 제출한다.
    - 신뢰할 수 없는 버전의 E골드를 개념화하고 있었다.

## 비트코인 실험

---

- 2008년까지 사람들은 온라인에서 점점 더 많은 상품과 서비스를 구매하기 시작했다.
    - 많은 사람들은 여전히 인터넷으로 위변조를 방지하고 분산된 방법으로 전송하는 방법을 원했지만 놀랍게도 이때까지 그 방법은 고안되지 않았다.

### 2008년 금융위기

---

- 2006년 초, 세계 경제는 요동치고 있었다. 경제 성장기였지만 금융 시스템은 균열이 생기기 시작했다.
    - 처음으로 미국 주택 시장 가치가 하락했는데, 대출 규제가 느슨해 채무자들이 상환할 수 없었기 때문이다.
- 이로 인해 은행들은 담보 대출과 불안정한 대출을 금융기관 간에 주식이나 채권처럼 거래하면서 금융 시장은 대혼란에 빠졌다. 많은 자산이 가치 없는 것으로 판명됐고, 금융 시스템이 붕괴되면서 전세계 정부들은 세계 정세를 살리기 위해 현금을 투입해야 하는 상황이 벌어졌다.
- 금융 역사가 비트코인과 관련 있는 이유
    - 비트코인의 기초가 되는 개념과 기술이 2008년 이미 존재했지만, 디지털 신뢰와 투명성을 가능하게 하는 시스템은 없었기 때문이다.

### 백서

---

- 2008년 8월 18일, bitcoin.org 도메인이 등록되었고, 10월 31일에 사토시 나카모토(가명)가 백서를 작성하여 개발자 메일링 리스트에 공유했다. "비트코인: 피어 투 피어 전자 현금 시스템" 논문은 인터넷에만 존재하는 가치 시스템을 만들기 위한 구체적인 방안을 제시했다.
    - 은행이나 중앙 정부와 연결 없이 운영될 수 있는 디지털 화폐를 만들고, 금융위기 같은 사건이 반복되지 않도록 투명한 금융 시스템을 구축하는 것이 목표였다.
- 비트코인이 이전 시스템에서 가져온 아이디어
    - 스마트 콘트랙트와 같은 안전한 디지털 거래 (닉 재보)
    - 거래를 확보하기 위해 암호를 사용 (디지캐시)
    - 적은 양의 안전한 가치를 보낼 수 있는 이론적인 능력 (E골드)
    - 정부 시스템 밖에서 돈을 창출 (비머니)
    - 디지털 자금의 유효성을 검증하기 위해 작업 증명 사용 (해시캐시)
- 비트코인 백서의 개념
    - 이중 지출(Double spending): 위조된 복제를 통한 통화 단위의 두 번 이상 지출 위험
    - 작업 증명(Proof of Work): 계산 능력으로 해결해야 하는 수학적 문제
    - 해시(Hash): 다양한 크기와 시퀀스 데이터를 구성할 수 있도록 고정된 길이의 출력이 생성
    - 논스(Nonce): 특정 통신을 한 번만 사용할 수 있는 난수

❗비트코인 백서는 디지털 전용 네트워크에 모든 거래를 게시함으로써 조폐국 기반 중앙 권한을 제거할 것을 제안했다.

- 신뢰할 수 있는 당사자 없이 이를 달성하려면 거래를 공개적으로 발표해야 하며, 참가자들이 자신이 받은 순서에 대한 단일 이력을 합의하는 시스템이 필요하다.
- 수취인은 각 거래의 시점에 노드 대다수가 최초 수취인이라는 데 동의했다는 증거가 필요하다.

### 타임스탬프 서버 소개

---

- 사토시는 비트코인 네트워크 보호를 위해 작업 증명서와 타임스탬프 시스템을 사용할 것을 제안했다.
    - SHA-256을 해시 알고리즘으로 사용하며, 트랜잭션 중에 생성된 정보를 해시 알고리즘을 사용해 실행하면 해시(고정된 숫자와 문자의 문자열)가 생성된다.
        - ex> `keccak256("hello") = Ic8aff950685c2ed4bc3174f3472287b56d9517b9c948127319309a7a36deac8`
- 비트코인 백서는 해시로 거래를 추적하는 개념(연쇄 서명)을 소개한다.
    - 조폐국 기반 모델에서 정부나 중앙 당국은 거래를 추적하기 위해 표준 회계 관행을 사용한다.
    - 블록체인은 저장용 분산 데이터 구조와 인터넷상의 공용 네트워크를 구성하는 메시징 시스템 프로토콜을 사용하여 네트워크를 구성하며, 피어 투 피어(Peer-to-Peer) 시스템으로 복잡한 구조 없이 신뢰를 유지한다.
    - 블록체인은 여러 트랜잭션 블록으로 구성되며(시간 순), 트랜잭션 블록은 해시를 통해 서로 연결된다.
- 비트코인은 '서로를 알지 못하고, 신뢰하지 않는 여러 당사자가 어떻게 협력할 수 있을까?' 문제를, 모두가 동의하는 글로벌 원장을 유지하는 방법으로 해결했다.
- 비트코인 블록의 주요 속성
    
    ![그림 1-7. 사토시 나카모토가 개발자이자 초기 블록체인 개척자인 할 피니에게 보낸 10BTC의 거래를 기록한 비트코인 블록 #170](./image/image%205.png)
    
    그림 1-7. 사토시 나카모토가 개발자이자 초기 블록체인 개척자인 할 피니에게 보낸 10BTC의 거래를 기록한 비트코인 블록 #170
    
    - Block hash: 블록의 고유 식별자
        - 256비트 데이터 안에서 블록체인의 현재 상태에 대한 스냅샷을 제공하는 입력 데이터에서 생성된다. 스냅샷은 전체 비트코인 블록체인에 관한 대차대조표의 기술 버전과 같다.
        - 비트코인 블록은 자체 블록 해시를 포함하지 않지만, 블록이 체인으로 연결된 이전 블록의 해시를 포함한다. Block hash는 블록 헤더를 해시화해 찾을 수 있다.
    - Coinbase transaction: 네트워크에서 채굴된 새로운 블록의 첫 번째 트랜잭션
        - 블록 공급에 의해 새로운 비트코인을 추가하는데, 체인에 블록을 추가하는 마이너에게 보상으로 주며 블록을 공급해주는 방식이다.(채굴)
    - 블록 높이 번호(Block hight number): 현재 블록과 첫 번째 블록(제네시스 블록) 사이에 얼마나 많은 블록이 있는지 식별한다.
    - 머클루트(Merkle root): 블록체인의 유효성을 증명할 수 있는 해시 값

- 비트코인을 속일 수 없는 이유
    
    ![그림 1-8. 비트코인 거래를 되돌리기 어려운 이유](./image/image%206.png)
    
    그림 1-8. 비트코인 거래를 되돌리기 어려운 이유
    
    - 과거 블록을 변경하려면 이후 모든 블록의 연산을 다시 수행해야 하므로 비용이 많이 듦
    - 다른 사람들이 계속해서 작업을 수행하기 때문에 변경이 현실적으로 어려움

- 사토시 나카모토의 실종
    - 비트코인 백서 발표 후 사토시는 2012년까지 활동하면서 기능 체계를 만들었으며, 이후 실종되었다.
    - 2010년 12월, 비트코인을 위키리크스의 기부 메커니즘으로 사용하자는 제안이 나왔으나, 사토시는 논란이 될 것이며 기술적 진보에 집중하는 것이 더 중요하다고 생각한다고 글을 게시했다.
    - 2010년 12월 13일, 사토시는 마지막 메시지를 남기고 사라졌으며, 당시 1 비트코인은 20센트의 가치가 있었다.

## 비트코인을 되살리다

---

- 2008년 백서에서 설명된 비트코인 개념은 금융 플랫폼을 재고하기 위해 암호화, 개인정보 보호 및 분산 컴퓨팅 기술을 결합했다.
    - 하지만 실현을 위해 많은 일들이 남아 있었으며, 많은 개발자들이 네트워크를 되살리기 위해 노력했다.

### 매력적인 구성요소

---

- 가치(Value): BTC라는 계정 단위는 비트코인 블록체인 원장에 거래를 기록하는 데 사용된다.
- 분배(Distribution): 비트코인 네트워크는 거래 기록을 유지하기 위해 탈중앙화된 노드를 사용한다.
- 합의(Consensus): 비트코인 네트워크의 마이너들은 분산된 거래 기록의 보안과 안정성을 유지하기 위해 작업 증명을 함께 사용한다.

### 합의를 이루다

---

- 2009년 1월 3일, 사토시 나카모토는 50 비트코인을 채굴해 최초의 비트코인 블록(제네시스 블록)을 만들었다.
    - 블록에서 코인베이스 트랜잭션 입력 내용: `2009년 1월 3일 더 타임스, 은행들의 두 번째 구제금융을 앞두고 있는 U.K. 재무장관`
    - 금융 위기를 블록체인 네트워크로 되살리는 목적을 전달했다.
- 비트코인은 분산된 네트워크로, 사용자가 노드를 실행하고 블록을 채굴할 수 있도록 비트코인 클라이언트(비트코인 v0.1)를 출시했다.
- 블록체인은 시간이 지남에 따라 끊임없이 업데이트되는 문서. 비트코인과 같은 탈중앙화 결제 네트워크에는 새로운 거래로 원장을 업데이트하는 중앙 권한(중앙 당국)이 없으며, 익명의 마이너들이 네트워크를 유지한다.

- 사용자들은 비트코인의 블록체인을 새로운 거래 블록으로 업데이트하기 위해 누구를 신뢰해야 하는가?
→ 합의 달성: 신뢰를 얻는 것
    - 블록 발견: 트랜잭션 블록을 추가할 수 있는 권한을 갖는 마이너를 합의한다.
    - 트랜잭션의 유효성: 새 블록에 포함된 트랜잭션이 합법적이라는 데 동의한다.
    - 합의를 달성하기 위한 두 가지 접근법
        - Proof-of-work: 작업 증명
        - Proof-of-stake: 지분 증명

- 공개키 암호학과 개인키 암호학
    - 비트코인은 공개키 암호화와 개인키 암호화를 이용해 거래의 타당성을 증명한다.
        - 개인키(비밀키)는 비트코인 거래에 디지털로 서명하는 데 쓰이고, 비트코인 주소의 소유자가 해당 주소의 정당한 소유자임을 네트워크에 증명하는 데, 거래를 승인하는 데 쓰인다.
        - 공개키는 비트코인 주소를 생성하는 데만 사용된다. 주소는 누구와도 공개적으로 공유할 수 있다.

- 키 생성
    - 개인키: 무작위로 선택된 256비트 숫자. 거의 항상 16진수 형식으로 표시돼 있다.
        - 컴퓨터에 의해 생성된다. 공개키와 페어링(한 쌍으로 묶인)돼 비트코인 네트워크에서 거래할 수 있다.
        - 개인키가 없으면 설계상 거래를 할 수 없다.
    
    ![그림 1-9. 개인키에서 비트코인 주소를 생성하는 과정](./image/image%207.png)
    
    그림 1-9. 개인키에서 비트코인 주소를 생성하는 과정
    

- 트랜잭션 생성
    - 비트코인의 거래는 UTXO(미사용 거래 산출물) 회계를 따른다.
    - 트랜잭션은 기본적으로 입력 목록과 출력 목록으로 존재한다.
        - 입력
            - 과거에 받은 주소와 자금의 원천으로 작용하는 비트코인 주소의 미지출 거래를 식별한다.
            - 해당 주소의 소유자가 트랜잭션을 승인했다는 것을 증명하는 디지털 서명이 포함돼 있다.
        - 출력
            - 받는 비트코인 주소와 주소가 받을 금액을 보여준다.

### 조기 취약성

---

- 초기에는 사용자 수가 적어 프로토콜 문제가 크지 않았으나, 2010년 8월 6일, 커뮤니티 회원이 비정상적으로 많은 양의 출력 거래를 발견했다.
    - 제프 가르지크 개발자가 #74638 블록이 매우 이상하다고 알렸다.
        
        ![1-1. 비정상으로 큰 비트코인 거래](./image/image%208.png)
        
        1-1. 비정상으로 큰 비트코인 거래
        
- 이후 취약점이 패치됐고 블록체인은 체인을 분산시키기 위해 포크됐다.
    - 포크: 잘못된 거래를 반영하지 않도록 함

### 채택

---

- 사토시의 실종은 비트코인을 완전히 탈중앙화된 실체로 만드는 데 기인한다.
    - 창조자가 시스템의 일부가 아니게 됐기 때문이다.
- 2010년 5월 22일 프로그래머 라즐로 하네츠는 비트코인을 사용해 재화나 서비스를 위한 첫 거래를 한 공로를 인정받았다.
    - 두 개의 피자를 배달하는 대가로 10,000 BTC를 지불했다.
- 2010년 7월, 암호화폐 거래소인 마운트곡스는 비트코인 교환 서비스를 제공하기 시작했다.
    - 전통적인 통화로 교환하는 개념은 투기와 그에 따른 가격 상승을 부채질했다.

## 요약

---

- 비트코인은 블록체인 기술의 탄생에 중요한 역할을 했으며, 기술적 기반을 두고 성장한 것은 갑자기 일어난 것이 아니다.
- 현재 성숙도는 수십 년이 걸린 기술에 의존하고 있으며, 집단적인 노력으로 블록체인 기술이 현재 위치에 도달했다.
    - 비트코인의 오픈소스 성격과 이를 중심으로 성장한 커뮤니티가 초기 도입을 뒷받침했다.
    - 암호화폐의 근본적인 측면은 비트코인에서 비롯되었다.
