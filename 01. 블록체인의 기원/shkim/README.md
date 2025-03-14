# 블록체인의 기원

블록체인은 정보를 블록에 담아 체인으로 엮은 형태를 의미한다. <br>
블록체인도 인터넷과 비슷한 목표로 정보를 유통하는 방식을 개선하기 위해 탄생했다.

## 분산화 vs 중앙집중화 vs 탈중앙화

인터넷은 분산 기술로 설계됐지만 중앙집중화 애플리케이션과 분산화 애플리케이션이 혼합된 형태다. <br>
초기 인터넷 설계자들은 하나의 장애 지점이 있는 중앙집중화 구조를 구축하기보다는 더 탄력적인 시스템을 지향했다. <br>
분산 방식은 자전거 바퀴살 일부가 파손돼도 바퀴는 계속 작동하는 설계 방식이다. <br>
어떤 단일 장애 지점도 전체 시스템을 무너뜨릴 수 없다는 것을 의미한다.

분산화 시스템은 하나의 컴퓨터에서만 처리되지 않는 시스템을 말한다. <br>
계산은 여러 컴퓨팅 자원에 걸쳐 공유된다. 분산화 시스템은 메시지를 사용해 서로 통신한다. <br>
분산 시스템은 단일 노드의 고장이 전체 네트워크의 고장을 뜻하지 않는다는 점에서 분산화의 특성이 있다. <br>
다수의 컴퓨터에 책임을 분산시키고 처리 능력을 활용해 공동으로 작업을 수행하는 것이 목표다.

탈중앙화된 시스템에서는 특정 노드가 자신의 목표를 달성하기 위해 반드시 모든 다른 노드와 협력할 필요는 없으며 <br>
결정은 합의를 통해 이뤄지며 단일한 개체에 책임을 맡기지 않는다.

<img width="608" alt="Image" src="https://github.com/user-attachments/assets/be5ce67e-1109-43da-acd1-4d3e3467ea2d" /> <br>
<img width="381" alt="Image" src="https://github.com/user-attachments/assets/e4f353a4-02e2-4865-b0b4-7a69ec48b4d1" /> <br>
<img width="713" alt="Image" src="https://github.com/user-attachments/assets/64b6d351-2eca-4077-a68d-c7c0c95b820d" /> <br>
<img width="726" alt="Image" src="https://github.com/user-attachments/assets/27b983b4-d94a-415b-b8b2-feb239910926" /> <br>

## 비트코인 실험

**비트코인 : 피어 투 피어 전자 현금 시스템**이라는 제목의 논문은 인터넷에만 존재하는 가치 시스템을 만들기 위한 구체적인 방안을 제시했다. <br>
은행이나 중앙 정부와 아무런 연결없이 운영될 수 있는 디지털 화폐를 만들고, 금융위기 같은 사건이 다시는 일어나지 않도록 투명한 금융 시스템을 구축하는 것이 목표였다. <br>
비트코인의 제안은 이전 시스템에서 가져온 다음과 같은 아이디어를 특징으로 삼았다.

- 안전한 디지털 거래
- 암호를 사용
- 적은 양의 안전한 가치를 보낼 수 있는 이론적인 능력
- 정부 시스템 밖에서 돈을 창출
- 디지털 자금의 유효성을 검증하기 위해 작업 증명 사용

### 타임스탬프 서버 소개

사토시는 비트코인 네트워크를 보호하기 위해 작업 증명서를 사용하는 것 외에도, 파일 시스템 및 데이터베이스와 유사한 트랜잭션을 검증하기 위해 타임스탬프 시스템을 사용할 것을 제안했다. <br>
트랜잭션 중에 생성된 정보를 해시 알고리즘을 사용해 실행하면 해시라고 알려진 고정된 숫자와 문자의 문자열이 생성된다. <br>
사토시는 SHA-256을 사용할 것을 제안했다. <br>
비트코인 백서는 연쇄 서명, 즉 해시로 거래를 추적하는 개념을 소개한다. 블록들이 연결돼 시간 순으로 구성된 구조다.

블록체인은 디지털 시스템에서 트랜잭션을 추적하기 위해 암호 수학적 신뢰를 사용한다. <br>
네트워크는 블록체인을 확인하고 게시하기 위해 피어 투 피어 시스템을 사용하기 때문에 복잡한 구조가 필요하지 않다. <br>
블록체인은 여러 트랜잭션 블록으로 구성되며, 트랜잭션 블록은 해시를 통해 서로 연결된다. <br>
다음은 모든 비트코인 블록의 중요한 속성이다.

#### Block hash

블록의 고유 식별자다. 블록 해시는 256비트 데이터 안에서 블록체인의 현재 상태에 대한 스냅샷을 제공하는 입력 데이터에서 생성된다. <br>
비트코인 블록은 자체 블록 해시를 포함하지 않지만, 블록이 체인으로 연결된 이전 블록의 해시를 포함한다.

#### Coinbase transaction

네트워크에서 채굴된 새로운 블록의 첫 번째 트랜잭션이다. <br>
체인에 블록을 추가하는 마이너에게 보상으로 주며 블록을 공급해주는 방식이다.

#### 블록 높이 번호

현재 블록가 체인의 첫 번째 블록 사이에 얼마나 많은 블록이 있는지 식별한다.

#### 머클루트

블록체인의 유효성을 검증할 수 있는 해시 값이다.

<img width="338" alt="Image" src="https://github.com/user-attachments/assets/ad074e05-2f53-4fa6-a1e3-61dd1974bb9d" />

## 비트코인을 되살리다

비트코인 아이디어를 실현하기 위해 해야할 많은 일들이 남아 있었다. <br>
오픈소스 소프트웨어와 비트코인의 이상에 헌신한 많은 컴퓨터 프로그래머들은 비트코인의 잠재력을 믿었다. <br>
네트워크를 되살리는 것이 다음 과제였으며, 초기 개척자들의 노력이 필요했다.

### 매력적인 구성 요소

- 가치: BTC라고 하는 계정 단위는 비트코인 블록체인으로도 알려진 원장에 거래를 기록하는데 사용된다.
- 분배: 비트코인 네트워크는 거래 기록을 유지하기 위해 탈중앙화된 노드를 사용한다.
- 합의: 비트코인 네트워크의 마이너들은 분산된 거래 기록의 보안과 안정성을 유지하기 위해 작업 증명을 함께 사용한다.


### 합의를 이루다

사용자들은 비트코인의 블록체인을 새로운 거래 블록으로 업데이트하기 위해 누구를 신뢰해야 하는가? <br>
신뢰를 얻는 것을 합의 달성이라고 한다. 네트워크에 전력을 공급하는 모든 마이너가 다음 두 가지 목적으로 사용하는 프로세스다.

- 블록 발견: 트랜잭션 블록을 추가할 수 있는 권한을 갖는 마이너를 합의한다.
- 트랜잭션의 유효성: 새 블록에 포함된 트랜잭션이 합법적이라는데 동의한다.

#### 공개키 암호학과 개인키 암호학

비트코인은 공개키 암호화와 개인키 암호화를 이용해 거래의 타당성을 증명한다. <br>
개인키는 비트코인 거래에 디지털로 서명하는 데 쓰이고, 비트코인 주소의 소유자가 해당 주소의 정당한 소유자임을 네트워크에 증명하는 데 사용된다. <br>
또한 개인키는 거래를 승인하는 데 쓰인다. 개인키는 비밀번호처럼 사용돼 비밀키라고도 한다.

공개키는 비트코인 주소를 생성하는 데만 사용된다. <br>
주소는 본질적으로 공개키의 압축 버전이므로 읽기가 다소 쉽다. 비트코인 주소는 보통 누군가에게 비트코인을 보내라고 하면 누구와도 공개적으로 공유할 수 있는데 쓰인다.

#### 트랜잭션 생성

비트코인 거래는 UTXO라고 하는 독특한 유형의 회계를 따르는데, 이는 사용되지 않은 거래 산출물을 의미한다. <br>
트랜잭션은 기본적으로 입력 목록과 출력 목록이 존재하는데, 각 입력은 과거에 받은 주소와 자금의 원천으로 작용하는 비트코인 주소의 미지출 거래를 식별한다. <br>
또한 해당 주소의 소유자가 트랜잭션을 승인했다는 것을 증명하는 디지털 서명이 포함되어 있다. <br>
출력은 비트코인 주소와 주소가 받을 금액을 보여준다.



