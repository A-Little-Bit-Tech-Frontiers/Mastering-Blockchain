# 💡 비트코인의 제한된 기능 개선

-	비트코인은 어떤 조건(예: 이 사람의 서명이 맞는가?)이 맞으면 거래가 되도록 만든 시스템이다.
-	그래서 사람들이 처음엔 “오, 이건 프로그래밍 가능한 돈이야!”라고 생각했는데, 실제론 단순한 기능밖에 없어서 그냥 조건만 걸 수 있는 돈 정도에 그침.
-	그리고 비트코인을 돈(결제 수단)으로 볼지, 아니면 가치 저장 수단(디지털 금)으로 볼지를 두고 다양한 논쟁이 존재했다.
-	개발자들 대부분은 “안전하게, 분산된 방식을 지키자”고 해서, 비트코인의 시스템을 크게 바꾸는 걸 꺼려했다. (예: 블록 크기 늘리기 등)
-	하지만 일부 개발자들은 “비트코인 위에 새로운 기능이나 블록체인을 쌓자”고 하면서 점점 더 프로그래밍이 가능한 플랫폼으로 발전하려는 움직임도 있었다.

## 컬러드 코인

- 비트코인 블록체인 위에 주식, 금 등 실제 자산을 표현하고 관리하려는 개념
- 비트코인 스크립트는 튜링 불완전해서 복잡한 기능 구현이 어렵고, 데이터 저장 공간도 제한적이어서 직접 구현에는 제약이 있음.
- 그래서, 컬러드 코인은 비트코인 위에 덧붙여서 만들었고, 토큰(Token)이라는 개념이 도입됨.
- 토큰이란? 기존 블록체인(예: 비트코인, 이후엔 이더리움 등)에 별도 원장을 만들어 표현한 가치 단위. 겉보기엔 암호화폐와 비슷하지만 블록체인 위에서 만들어진 자산 표현 방식임.
- 컬러드 코인은 이더리움 등에서 발전된 다양한 토큰 생태계의 시초가 됨.

## 마스터코인과 스마트 콘트랙트

- 마스터코인(Mastercoin)은 2013년에 등장한 비트코인 기반의 스케일링 솔루션이다.
- 비트코인의 기본 프로토콜에 없는 기능들을 추가하며, 프로그래밍 가능한 돈 개념을 확장시켰다.
-	주요 기능 중 하나는 스마트 콘트랙트(블록체인에서 실행되는 프로그램) 개념의 도입이었다.
-	또한 토큰(Token) 개념을 최초로 도입해, 비트코인 위에서 새로운 암호화폐를 생성할 수 있게 했다.
-	마스터코인은 지금은 원시적으로 평가되지만, 이후 스마트 콘트랙트, 토큰, ICO 발전의 기반이 되는 실험 플랫폼이었다.
- 마스터코인은 비트코인 위에 스마트 콘트랙트와 토큰 개념을 도입한 초기 프로젝트로, 이후 이더리움 등 암호화폐 생태계의 발전에 중요한 기반이 되었다.

## 옴니레이어의 이해

- 비트코인 위에 구축된 오픈소스 분산 자산 거래 플랫폼. 원래 마스터코인으로 시작했으며, 이후 옴니레이어로 이름이 변경됨.
- 옴니코어란? 옴니레이어의 참조 구현체로, 비트코인 기능을 확장하고 스마트 콘트랙트 기능을 제공함. 이를 통해 자동화된 화폐 기능과 토큰 생성이 가능해짐.
- 스마트 콘트랙트를 통해 트랜잭션, 합의, 자산 발행 등 비통화적 기능도 블록체인 위에서 구현할 수 있음.
- 옴니레이어는 마스터코인에서 발전한 비트코인 기반 자산 플랫폼으로, 스마트 콘트랙트와 토큰 생성을 지원하며 메이드세이프 같은 프로젝트를 가능하게 했다.

## 테더

- 테더(Tether)는 옴니레이어에서 탄생한 가장 유명한 프로젝트로, 법정화폐(미국 달러)를 담보로 한 안정적인 암호화폐(스테이블코인)이다.
- 테더의 핵심 목표는 1달러에 고정된 디지털 통화를 제공하는 것. (백서상으로는 1 테더 = 1 USD)
- 그러나 실제로 은행 계좌에 1달러가 보관되어 있는지 증거 부족. 단지 웹사이트에서 잔고만 공개함. 2018년엔 외부 회계감사 기관과의 관계도 중단함.
- 테더는 한때 1달러 밑으로 하락하기도 했으나, 특별한 설명 없이 다시 회복됨. -> 여전히 신뢰성과 투명성에 대한 논란이 존재함.
- 그럼에도 불구하고, 테더는 토큰화된 자산의 대표 사례로, 암호화폐 생태계에서 중요한 실험적 사용 사례로 간주됨.

## 옴니레이어 작동 방식 

- J.R. 윌렛이 제안한 두 번째 비트코인 백서의 기능을 기반으로 개발됨.
-	핵심 기능
	-	사용자 화폐 생성 – 누구나 옴니레이어 원장에 자신만의 화폐(토큰)를 만들 수 있음.
	-	탈중앙화 거래소 – 중앙화 거래소 없이, 네트워크 내에서 트레이드 코드를 통해 직접 통화 교환 가능.
	-	작업 증명 기반 보안 – 비트코인의 채굴자와 해시파워를 활용해 높은 보안성과 신뢰성을 확보.
-	비트코인 위에 구축된 2계층 프로토콜로서, 새로운 네트워크를 만들지 않고도 비트코인의 기존 네트워크 효과를 그대로 활용할 수 있음.
-	초점: 토큰화와 스마트 콘트랙트 기능을 탈중앙화된 환경에서 구현하는 것.

## 사용자 정의 논리와 OP_RETURN

-	옴니레이어는 비트코인의 블록체인에 사용자 정의 논리 연산(맞춤형 기능)을 추가함.
-	2014년 3월, 비트코인에 OP_RETURN 필드가 도입되면서,  트랜잭션에 추가 데이터를 저장할 수 있게 됨.
-	옴니는 이 기능을 활용해 모든 옴니 트랜잭션 데이터를 OP_RETURN 필드에 기록함. (예: 테더(USDT) 전송 정보 등)
-	OP_RETURN은 추가 메타데이터(예: 전송 금액, 주소 등)를 담고 있으며, 이 데이터는 16진수로 인코딩되어 블록체인에 저장됨.
-	옴니 트랜잭션과 일반 비트코인 트랜잭션의 차이점은 OP_RETURN 필드의 유무다.
-	이를 통해 비트코인의 기본 구조를 변경하지 않고도 맞춤형 자산 전송이 가능해짐.
-	즉, 옴니레이어는 비트코인의 OP_RETURN 기능을 활용해 사용자 정의 데이터를 블록체인에 기록하고, 이를 통해 테더 같은 맞춤형 토큰 거래를 지원한다.

![image](https://github.com/user-attachments/assets/b2e348a5-5955-4ad8-8347-a6c640646123)

![image](https://github.com/user-attachments/assets/78bb236a-c79f-482e-a52a-118eb58db57d)

- 그림을 보면, OP_RETURN 필드 값 6f6cI6e6900000000000000001f00001dcd6500은 UDST 트랜잭션을 기록하는 옴니레이어 메타 데이터임을 알 수 있다.
- 메타 데이터는 16진수 형식으로 암호화돼 있다.

# 💡 이더리움: 마스터코인을 한 단계 끌어올리기

- 이더리움(Ethereum)은 비트코인과 마스터코인의 개념을 바탕으로 만든, 더 기능적이고 범용적인 블록체인 연산 플랫폼이다.
-	2013년, 비탈릭 부테린이 이더리움 개념을 처음 제안했고, 개빈 우드 등과 함께 개발을 시작함.
-	이더리움의 목표: 탈중앙화된 개방형 컴퓨터 시스템(스마트 콘트랙트 기반의 범용 플랫폼) 구축.
-	초기에는 비트코인처럼 작업 증명(PoW) 기반이었지만, 2022년 9월, 지분 증명(PoS)으로 전환함. -> 더 효율적이고 친환경적인 보안 모델로 변화

## 이더와 가스

- 이더(Ether)는 이더리움의 암호화폐이며, OX로 시작하는 주소를 사용한다. -> 전송 속도는 비트코인보다 빠름.
-	계정 구조 차이
	-	비트코인: UTXO 방식(지폐처럼 개별 단위 추적) -> 잔액 계산이 복잡하고, 잔돈 개념이 있음.
	-	이더리움: 계정 기반 모델(은행 잔고처럼 관리) -> 잔액 계산이 단순하고 직관적임.
-	가스(Gas)
	-	이더리움에서 프로그램 실행 비용을 측정하는 단위.
	-	디앱(DApp) 실행 시 과도한 자원 사용(무한 루프 등)을 방지하기 위해 사용됨.
	-	개발자는 가스 한도를 지정하며, 가스가 모두 소모되면 트랜잭션은 중단됨.
	-	마이너는 가스를 통해 수수료를 획득함.
-	이더리움은 비트코인/마스터코인에서 발전해, 디앱과 스마트 콘트랙트 같은 애플리케이션 중심 블록체인 기능을 제공한다.
-	즉, 이더리움은 계정 기반 모델과 가스 시스템을 통해 비트코인보다 빠르고 유연하게 동작하며, 스마트 콘트랙트와 디앱을 안정적으로 실행할 수 있는 환경을 제공한다.

![image](https://github.com/user-attachments/assets/edd810fb-02c9-4669-9121-ac431decc3d4)

- 비트코인 vs 이더리움
- 비트코인은 그냥 “돈 보내는 행위”만 있다.
  - 데이터 용량(트랜잭션 크기)에 따라 수수료가 계산됨.
  - 보내는 사람이 수수료를 얼마 줄지 자율적으로 정함 (높을수록 빨리 처리됨)
- 이더리움은 “돈 보내는 것 + 프로그램 실행(스마트 콘트랙트)“이 가능하다.
  - 단순 송금도 가스를 쓰고, 복잡한 연산(디앱 실행)은 더 많은 가스를 씀.
  - 개발자가 가스 한도와 가격을 정해줘야 함.

## 사용 사례: ICO

- 이더리움의 역할
  - 스마트 콘트랙트를 통해 여러 디앱 실행 가능.
  - 자금을 자동화되고 안전하게 조달할 수 있는 강력한 기능을 제공함.
- 이더리움의 성장
  - 스마트 콘트랙트 + 토큰 발행 기능이 결합되며 신뢰 가능한 자동화된 자금 조달 플랫폼으로 자리잡음.
  - 이후 수많은 암호화폐 프로젝트의 기반이 됨.
- 이더리움은 리카르디안 계약 개념과 스마트 콘트랙트를 바탕으로, 자동화된 자금 조달과 토큰 발행이 가능한 신뢰성 높은 플랫폼으로 발전했다. 

## 탈중앙화된 자율 조직

- DAO(탈중앙화 자율 조직, Decentralized Autonomous Organization)
  - 스마트 콘트랙트를 활용해 중앙집중식 거버넌스를 대체하려는 개념.
  - 기업공개(IPO)를 대체한 ICO와 비슷한 탈중앙화 흐름 속에서 등장.
- DAO의 핵심 아이디어
  - ICO 투자자가 토큰을 소유함으로써 투표권(의결권)을 갖고, 거버넌스와 의사결정에 직접 참여하는 분산형 조직 운영 실현.
- The DAO 프로젝트 (2016년)
  - 이더리움 기반 최초의 대형 DAO 실험.
  - 1만 1천 명의 투자자들로부터 약 1억 5천 4백만 달러 모금.
  - 스마트 콘트랙트 기반으로 자금 운영과 투자를 자동화하려는 시도였음.
- 즉, DAO는 스마트 콘트랙트를 이용해 중앙의 통제 없이 투자자들이 토큰을 통해 직접 의사결정에 참여하는 탈중앙화 거버넌스 시스템이며, ‘The DAO’는 그 대표적 실험이었다.

## 이더리움의 포크로 탄생된 이더리움 클래식

- DAO 스마트 콘트랙트에 재귀 호출 취약점이 있었음.
- 자금 인출 중 잔액이 즉시 업데이트되지 않아 무한 인출이 가능했던 것.
- 2016년 6월 17일, 해커가 이 취약점을 악용해 5천만 달러 이상의 이더리움 탈취.
-	블록체인은 불변이므로, 배포된 스마트 콘트랙트는 수정 불가.
- 해결책: 새로운 스마트 콘트랙트를 배포하고 잔여 자금 이동.
- 이더리움 재단의 대응
  - 하드포크(Hard Fork)를 단행해 도난된 자금을 복구 주소로 이동.
  - 이 결정은 블록체인의 불변성 원칙 위반이라는 논란을 일으킴.
-	하드포크 결과, 이더리움은 두 개의 체인으로 분리됨.
	- 이더리움 (Ethereum, ETH) – 해킹 피해 복구한 체인
	- 이더리움 클래식 (Ethereum Classic, ETC) – 원본 블록체인 유지
- 현재 이더리움 클래식은 존재하지만 규모나 개발 활력은 이더리움보다 작음.

# 💡 탈중앙화 애플리케이션

- 디앱(DApp, Decentralized Application)은 블록체인에서 스마트 콘트랙트를 기반으로 실행되는 애플리케이션이다.
-	디앱은 일반적으로 스마트 콘트랙트(백엔드), 프론트엔드 UI, 블록체인 서버 역할을 수행하는 구조로 구성됨.
-	기존 클라이언트/서버 아키텍처와 유사하지만, 서버 대신 블록체인 노드에서 실행된다는 점이 차이점.
-	디앱은 분산 시스템 위에서 동작하며, 분산된 컴퓨팅 자원 간의 의사소통과 처리가 핵심.
-	이더리움은 현재 디앱을 실행할 수 있는 가장 널리 쓰이는 플랫폼이며, 개발자 친화적인 스마트 콘트랙트 환경을 제공함.

## 사용 사례

- 디앱의 주요 특징은 불변성immutability이다. 불변성이란 블록체인에 게시된 후에는 중앙집중화 권한으로 코드를 변경할 수 없다는 것을 의미한다. (중앙집중 권한 없이 운영됨.)
- 검열 저항성(제3자가 게시 전에 컨텐츠를 검열하지 않음)이 있기 때문에 중앙화 앱과 달리 병목이 거의 없다.
- 비트토렌트처럼 프라이버시 보호 기능을 갖추면서, 디지털 자산을 빠르고 프로그래밍적으로 안전하게 전송 가능. (프라이버시와 자산 이전)
- 이더리움 같은 플랫폼에서는 허가 없이 누구나 애플리케이션을 배포할 수 있음.
- But, 디앱 기술은 아직 초기 단계이며, 지속 가능성, 목적의 정당성에 대한 우려도 존재함. (현재는 주로 도박, 게임, 탈중앙화 거래소에서 활용 중.)

## 디앱의 개발 과제

- 디앱 개발 시 주요 설계 과제
  - 구현 난이도, 사용자 경험(UX), 속도, 확장성 문제가 존재.
  - 이 문제는 이더리움 포함 모든 디앱 플랫폼에 해당됨.
- 스마트 콘트랙트 배포 시 주의점
  - 배포 후 코드 수정이 어렵고, 같은 주소로 재배포도 불가. (왜냐하면, 블록체인은 불변성을 갖기 떄문. 배포된 스마트 콘트랙트는 블록체인에 영구적으로 기록된다. 이것이 신뢰할 수 있는 이유이기도 함. 아무도 몰래 수정할 수 없으니까!)
  - 업그레이드 시 데이터 마이그레이션 등의 복잡한 절차가 필요.
- 개발자의 책임 있는 개발 방식
  - 테스트넷(예: Goerli, Sepolia)에서 충분한 테스트 필요.
  - 보안 감사를 전문 기관(OpenZeppelin 등)에 맡기고, 깃허브를 통해 커뮤니티 감사도 받는 것이 이상적.
- 디앱 속도 및 사용자 경험 문제
  - 블록체인 특성상 속도와 확인 시간에 따라 UX가 저하될 수 있음.
  - 예시: 크립토키티(CryptoKitties)로 인해 2017년 이더리움 네트워크가 혼잡, 디앱 사용이 사실상 불가능했던 사례 발생.
 
# 💡 이더리움에서 스마트 콘트랙트의 배치 및 실행

- 스마트 콘트랙트 개념은 1990년대에 등장했으며, 이후 발전해 왔음.
- 옴니레이어(Omni Layer)는 비트코인 위에 디앱 실행이 가능함을 증명했지만, 여러 한계가 있었음.
- 중앙 집중화 문제
  - 디앱을 배포하려면 옴니코어 개발자에게 승인을 받아야 했음.
  - 옴니코어에 직접 코드를 추가해야 하며, 일반 개발자는 배포 자율성이 부족했음.
- 기술적 제약
  - 비트코인은 복잡한 프로그램 실행에 적합하지 않음 (스크립트 언어가 제한적)
  - OP_RETURN 필드는 80바이트 제한으로 인해 저장 가능한 데이터량이 적어 복잡한 스마트 콘트랙트 구현에 제약이 있음.
- 확장성과 속도 문제
  - 옴니레이어는 비트코인의 성능(속도, 처리량)에 의존함.
  - 비트코인 자체가 가치 저장 중심 설계로, 실행 플랫폼으로서 한계가 있음.

![image](https://github.com/user-attachments/assets/383d1530-49ea-4fc0-801e-3ea5ea31459b)

## 이더리움 가상머신

- 이더리움 가상머신 즉, EVM(Ethereum Virtual Machine)을 사용하면 개발자가 쉽게 디앱을 만들고 네트워크에서 실행할 수 있다.
- EVM의 목적은 두 가지다.
  - 개발자가 스마트 콘트랙트를 블록체인에 도입할 수 있도록 한다.
  - 마이너에게 자신이 실행하는 소프트웨어에 내장된 EVM 스마트 콘트랙트 코드를 실행하는 방법을 지시한다.
