# Hana-blog

25.1.31 - OT 

til 
공부한 개념 확실히 쓰기 


My First Day at Bootcamp 
- OT
  - 전반적인 채용시장
  - 커리큘럼
  - 채용전략
    - 개인의 매력 향상시킨다

//
//
2/2 

블록 + 체인 
데이터 전체가 아닌 해시값만 전송해 타임스템프를 받고 이를 디지털 서명으로 보증받는다. 

블록체인 
- Blockchain = Block + Chain 
- 데이터는 블록에 저장되어 있고, 블록들은 시간 순서대로 연결되어 있다 (새 블록은 바로 이전 블록의 링크를 포함하도록 하는 방식으로)  
- 데이터가 블록에 저장될 때는 데이터 그대로 저장되지 않고 해시로 변환되어 타임스탬프를 부여받고, 이를 디지털 서명으로 보증받고 저장된다. 

화폐로서의 비트코인 
- 비트코인은 다음 화폐 3대 요소를 갖추고 있는가?: (1) 교환의 매개체, (2) 가치 척도의 기능, (3) 가치 저장의 기능 
- (1) 교환의 매개체: 아직 대부분의 사람들은 실생활에서 비트코인을 사용해 교환/거래 하지 않는다 
- (2) 가치 척도의 기능: 스테이블 코인의 등장으로 가치 척도가 어느정도 가능해졌지만 여전히 높은 가격 변동성으로 인해 가치 척도의 기능을 온전히 해내기 어렵다 
- (3) 가치 저장의 기능: 현재 가치 저장 가능. 우리나라에서 비트코인은 과세 대상인 가상자산으로 분류되고 있으며 일부 나라에서는 법정화폐를 대신해 사용되기 시작했다. 

블록체인 엔지니어로서 고민할 부분 
- 마트에세 비트코인으로 계산하기 어렵다. 사용성 향상하는 방법. 

Web3 사업할 때 살펴볼 부분 
- STO(Security Token Offering). 블록체인 기술을 활용해 자금 모집하는 방법 중 하나. 자산을 토큰화 하는 것.  
- 가상자산 관련 법룰, ISMS 에 대해 잘 아는게 중요함. 나라마다 규제가 더하거나 덜하기도 함. 

신용 창출
- 싱용창출로 인한 경제 대공황이 있었고 이에 대한 정부의 대응책은 양적 완화였다. 
- 양적완화는 금융위기 극복과 경제 부양에 큰 역할을 했지만 자산 버블, 인플레이션, 부의 양극화, 금융 불안정, 신흥국의 외환위기 위험 증가 등의 부작용이 있었다. 

사이퍼 펑크 
- 개인정보 관련 정부와 대기업의 행보에 반해 개인의 프라이버시를 중요시하는 사람들이 ‘시이버 펑크’라는 단체를 만들어 탈 중앙화된 문화를 옹호하는 사회운동 시작 
- 사토시 나카모토의 비트코인 백서는 사이버 펑크에 보낸 이메일를 통해 처음 세상에 선보이게 됨 
- 사토시는 추후 사이버 펑크 멤버들과 소통하며 비트코인 개발함

비트코인 제네시스 블록에 기록된 메세지
- The Times 03/Jan/2009 Chancellor on brink of second bailout for banks 
- 금융위기에서 영국 정부의 은행 구제금융에 대한 비판적 메세지. 
- 비트코인 탄생의 목적: (1) 중앙화 금융 시스템의 블안정성과 문제점 비판, (2) 탈중앙화 금융의 대안 제시 

블록체인은 디지털 세상에서 데이터의 신뢰를 만들어내는 신뢰의 기술임. 

* 여러분도 여러분만의 문제 인식과 그 해결을 위한 블록체인 활용법에 대해 스케치 해보시기 바랍니다. 


//
//
2/4
해시와 디지텉 서명 

블록체인에서는 각 타임스탬프가 이전 타임스탬프의 해시 값을 포함하도록 설계됨. 

SHA-256 알고리즘 작동 과정 
1. 입력 데이터 준비 : 입력 데이터는 고정된 크기(512비트 블록)로 처리되고 필요한 경우 패딩을 통해 데이터를 맞춤 
2. 패딩
3. 초기 해시 값 설정 : SHA-256은 8개의 32비트 초기 해시 값을 정의함. 이 값들은 암호학적 연구를 통해 설정된 상수임. 이 값들이 초기값이 되어 64번의 Round를 거친 후 나오게 됨. 
4. 메시지 처리 : 메시지 스캐줄 생성 > 해시 압축 함수(라운드 연산) 
5. 최종 출력 


블록 해시 값 생성 인자 
- 이전 블록의 해시 값
- 머클 루트: 블록 내 모든 트랜잭션의 요약 값 
- 난이도 목표: 
- 논스: 작업 증명을 완료하기 위해 반복적으로 변경되는 값 

블록 해시 역할: 블록 간 연결성 유지 & 변경된 데이터 탐지 

워드 = 단위 
코스모스 불록체인 - 라운드 

비트코인과 이더리움 모두 비대칭 암호화를 사용해 개인 키와 공개 키 생성. 모두 타원 곡선 암호화(ECC)를 기반으로 함. 

서명의 역할: 문서의 진위성과 무결성 보증 
서명: 나는 이 문서를 확인하고, 문서의 내용에 동의하며, 문서가 변조되지 않았음을 보증한다는 의미 전달해줌 

디지털 서명 
- 개인키를 사용해 서명: 서명 주체가 나인 것을 인증하고 데이터 변조되지 않았음을 증명 
-  수신자는 공개키로 서명을 검증해 다음을 확인할 수 있음: 무결성 보증과 진위성 확인 
- 무결성 보증: 데이터가 전송 중 변조되지 않았는지 
- 진위성 확인: 데이터를 서명한 사람이 신뢰할 수 있는 발신자인지 

디지털 서명의 동작방식 
- 해싱 
- 서명: 송신자는 개인티로 해시 값에 서명함. 이 서명은 암호화된 해시값으로 서명자는 해당 데이터의 무결성과 진위성 보증 (디지털 서명은 개인키로 암호화 되었기 때문에 공개키로 복호화 할 수 있고, 복호화하면 원본 데이터의 해시 값이 나옴) 
- 검증 : 수신자는 송신자의 공개키로 디지털 서명을 복호화 함. 검증 과정에서 다음 두 데이터 비교. 
- (1) 송신자의 공개키로 디지털 서명을 복호화 해서 원본 데이터의 해시값 구함
- (2) 원본 데이터를 해싱해 데이터의 해시값을 구함. 위 해시값과 같다면 데이터가 정상적으로 송신자에 의해 서명된 것임. 

디지털 서명 시스템의 필요조건: 
- 알고리즘 : 신뢰할 수 있고 널리 사용되어 그 안전성이 입증된 해시 함수(SHA-256, SHA-3 등)와 암호화 알고리즘(RSA, ECDSA)을 사용해야 함 
- 구현: 알고리즘 자체는 안전하더라도 소프트웨어나 하드웨어 구현상의 취약점이 보안 사고로 이어질 수 있음 
- 개인 키 : 개인키 유출이나 손상 > 진위성과 부인 방지 속성 무효화됨 

타임스탬프에서 디지털 서명의 사용 목적: 
- (1) 데이터 무결성 증명(특정 시점 이후 변하지 않았음, 디지털 서명으로 변조 여부 검증), 
- (2) 시간 인증(TSA가 인증), 
- (3) 신뢰 제공(인증 기관의 신뢰를 바탕으로 데이터 진위 보증) 

디지털 서명의 사용과정 
- (1) 데이터 해싱
- (2) 타임스탬프 생성 (TSA에서 서명해 유저에게 반환) 
- (3) 검증: 데이터 해싱 > 반환된 타임스탬프의 디지털 서명과 비교해 TSA의 공개키를 사용해 서명이 유효한지 검증하고 데이터 해시 값이 타임스탬프에 기록된 해시값과 동일한지 확인 > 데이터가 특정 시점 이후 변경되지 않았음을 증명 

디지털 서명에서 사용된 알고리즘 
(1) RSA 또는 DSA
      - TSA는 개인키로 서명하고 이를 공개 키로 검증 가능하게 함 
(2) 해시 알고리즘 
      - 데이터 해시 값 생성 위해 SHA-1 또는 MD5와 같은 해시 함수가 사용됨 

비트코인에서 디지털 서명의 역할: 
(1) 트랜잭션 무결성 보장 
(2) 소유권 증명 
(3) 탈중앙화된 검증 

비트코인에서 디지털 서명의 생성 및 검증 과정: 
(1) 서명 생성: 트랜잭션 데이터 준비 > 해싱 > 송신자의 개인키 사용한 해시 값 서명 > 서명과 트랜잭션 데이터 전송  
(2) 서명 검증: 검증 노드가 트랜잭션 데이터 해싱 >  공개 키를 사용한 검증 (서명이 유효한지, 송신자 개인키로 생성된 서명인지, 트랜젝션 데이터가 변조되지 않았는지 확인) > 검증 결과 (서명이 유효하면 네트워크에 추가) 
* 만약 두 해시값이 다르다면, 송신자의 개인키로 생성된 서명이 아니거나 데이터가 변조되었을 가능성. 

디지털 서명의 예시: 
- 앨리스가 밥에게 0.1 BTC 보내려는 트랜잭션 생성 > 트랜잭션 해시 값을 자신의 개인 키로 서명 > 서명된 트랜젝션을 네트워크에 전송 >> 
- 네트워크의 노드가 이 트랜잭션 데이터를 해싱해서 동일한 해시 값 생성 > 공개 키를 사용해 서명 검증 > 서명이 유효하면 트랜젝션을 블록체인에 추가 

디지털 서명의 장점: (1) 보안성(위조 불가능), (2) 무결성 보장(만약 데이터 변조되면 서명이 유효하지 않음), (3) 부인 방지, (4) 신뢰 기반 탈중앙화

비트코인에서 디지털 서명 활용의 특징 
- ECDSA 사용:
- 공개 키 -> 주쇼 변환 (SHA-256 + RIPMED-160) 
- 비교적 작은 서명 크기(64비트)

//
//
2/5

블록은 무엇으로 이루어져 있나요? 헤더와 바디 

블록 헤더는 왜 필요한가요? 
- 블록에 대한 메타데이터 포함하고 있고, 블록의 고유 식별자 역할을 하기 때문. 
- 구성: 이전 블록 해시(연결성), 머클 루트(루트 해시 값), 타임스탬프, 난이도 타켓, 논스, 버전

블록 바디에는 무엇이 있나요? 
- 트랜잭션 (코인베이스 트랜잭션와 일반 트랜잭션)

트랜잭션 흐름에 대해 간략하게 설명하세요. 
- 입력: 송신자가 이전 트랜젝션 출력((UTXO)를 참조하고, 지출할 UTXO 정보 등을 포함한 인풋에 개인 키로 디지털 서명을 한다
- 출력: 출력 금액 등의 정보를 포함한 아웃풋에 수신자의 주소를 지정하는 잠금 스크립트를 만든다
- 수신: 수신자가 공개키와 서명을 제공해 잠금 스크립트를 해제한다
- 검증: 노드가 입력과 출력을 검증한다  

비트코인 UTXO 모델에서 내 계좌에 10,000원이 있는데 밥에게 3,000원을 송금했다. 이 과정을 설명하세요.  
- 내가 갖고 있던 10,000의(UTXO) 상태가 “사용됨(입력, Input)”으로 변하고, 밥에게 3,000(UTXO)이 “미사용됨(출력, Output)”으로 생성된다. 내 계좌에는 수수료를 뺀 나머지 69999.999원(UTXO)이 “미사용됨(출력, Output)”으로 생성된다.  
* 비트코인은 필요한 금액만큼 UTXO을 소모하고 잔액은 새로운 UTXO로 생성됨. 

UTXO란? 
- Unspent Tranxaction Output의 약자로 이전 트랜잭션에서 생성되었지만 아직 소비되지 않은 출력을 말한다.  
- 내 지갑이 모든 UTXO를 더하면 잔고가 된다.
- 이미 소비된 UTXO는 다시 사용할 수 없어 "이중지불" 방지의 역할을 한다. 

이더리움과 비트코인의 차이점은? 
- 비트코인은 UTXO기반 모델이고 이더리움은 계정 기반 모델임. 
- 비트코인과는 달리 이더리움에서는 반복문을 쓸 수 있어 스마트 컨트랙트를 만들기 더 용이하다. 해커의 공격을 막기 위해 가스비를 도입해 공격할 때마다 가스비를 써야 하도록 설계했다. 

OP 코드로 각 트랜잭션이 올바르게 작동하는지 검증할 때 어떤 것을 보나요? 
- 소유자 확인, 출력 주소와 금액 확인, 다중 서명 및 공개 키 변조 방지

머클 루트는 어떤 역할을 하나요? 
- 마클 트리에서 하나의 트랜잭션만 변경해도 머클 루트가 변함으로써 데이터 무결성을 보장하고 위변조를 방지합니다. 


////
2/6


4. 블록체인의 작동원리 

사토시 나카모토는 중앙 집중형 원장의 어떠한 특징을 해결하고 싶어했나요? 
- 중앙화된 신뢰: 데이터의 신뢰가 국가와 같은 중앙 기관의 신뢰성과 권위를 기반으로 형성되는 점 
- 단일 장애점: 중앙 서버가 해킹, 손상, 장애를 겪으면 데이터가 유실되거나 손상될 위험이 있음. 
- 투명성 부족 

중앙 집중형 원장의 특징 중 어떤 것이 사타시 나카모토의 최우선 과제가 아니었나요? 
- 효율성: 중앙 기관이 직접 데이터를 관리해서 처리 속도가 빠를 수 있음 

분산원장이란 무엇인가요? 
- 데이터를 중앙 서버가 아닌 네트워크의 여러 노드에 걸쳐 분산 저장하는 데이터베이스의 일종. 중앙기관 없이 데이터의 무결성과 보안이 유지됨. 

분산원장의 종류로 어떤 것이 있나요? 
- 퍼블릭 (예: 비트코인, 이더리움) 
- 프라이빗: 제한된 참여자만 접근 가능. 기업 내부에서 사용됨. (예: 하이퍼레저, 리플)
- 컨소시엄: 특정 그룹(기업 연합 등) 내에서 공유되며, 참여 노드가 제한됨. 

중앙 집중형 원장과 분산원장의 대표적 차이점 몇 가지를 얘기해보세요. 
- 데이터 추가/수정 가능 여부: 중앙 집중형 원장에서는 가능, 비트코인에서는 불가능 
- 신뢰 형성 방법:  중앙 집중형에서는 중앙 기관의 권위 사용, 비트코인에서는 합의 알고리즘과 암호화 기술 사용 
- 확장성: 중앙 집중형에서는 높음(중앙화된 처리), 비트코인에서는 낮음(분산 처리로 인한 제한) 

합의 알고리즘이란?: 무엇이 우선시 되어야 하는가를 정의하는 것  
- 블록이 포크 되었을 때 무엇을 우선시 해야하나? 비트코인은 작업을 많이 한 체인. 

분산 원장 기술의 작동 방식을 설명하세요. 
- 트랜잭션 생성 
- 트랜잭션이 모든 노드에 전파됨 
- 협의 과정: 노드들이 합의 알고리즘을 통해 해당 트랜젝션의 유효성 검증 
- 데이터 저장: 검증된 트랜잭션 원장에 기록; 노드 동기화  
 
노드란?
- 블록체인 네트워크에 연결된 장치.PC. 

노드는 어떤 역할을 하나요? 
- 데이터 저장, 데이터 검증 (블록의 유효설 검증), 네트워크 연결 및 데이터 전파, 합의 참여 

노드 유형으로 어떤 것이 있나요?  
- 풀노드 (예: 비트코인 코어 노드) 
- 라이트 노드, SPV 노드: 머클 루트를 포함한 블록 헤더만 저장하여 작동함; 트랜젝션 검증을 위해 다른 풀 노드 필요; 예: 모바일 지갑 앱   
- 마이닝 노드: 작업 증명을 수행해 새 블록 생성. (예: 지난 실습에서 풀노드에서는 비트코인 데몬을 켜 놓고, 마이닝 노드는 비트코인 블록을 생성 했었음) 

알트코인에서 볼 수 있는 노드로 어떤 것이 있나요? 
- 검증 노드: 지분 증명 네트워크에서 블록 생성 및 검증. 예: 이더리움 2.0, 폴카닷, 솔라나  
- 아카이브 노드: 블록체인의 모든 기록과 상태 데이터 자장. 주로 스마트 컨트랙트가 실행되는 블록체인(예: 이더리움, 폴카닷, 솔라나) 에서 사용됨. 

비잔틴 장군 문제에 대해 얘기해보세요. 
- 4개 군대가 힘을 합쳐 포위하고 있는 적군의 성을 함락해야 함. 
- 4개 군대고 동시에 공격해야만 성을 함락할 수 있음. 만약 한 군대가 배신해서 동시에 공격 못 하면 작전 실패.
- 해결: 각 국대가 모든 군대에게 메세지를 전파한다. > 다수결로 공격 성공
- 레슬리 램포트의 해법: 네트워크의 노드가 3n+1 이상이어야 최대 n명의 배신자기 있어도 합의 가능하다 

분산된 네트워크 환경에서 악의적인 노드(배신자)가 존재할 때 이를 어떻게 극복하고, 정직한 참여자들이 올바르게 합의에 도달할 수 있을까?
- 비잔틴 장애 허용(BFT): 네트워크 내 일부 노드가 악의적이거나 오류를 발생시켜도 나머지 정직한 노드가 올바른 합의에 도달하여 시스템이 정상적으로 작동하도록 보장하는 메커니즘.  
- 한마디로 악의적 노드가 있어도 돌아가는 시스템을 돌아가게 하자는 것. 
 
블록이 생성되는 과정을 설명해보세요. (* 잘 이해하기) 
1. 트랜잭션 생성 > 모든 노드에 전파(브로드캐스트)  
2. 트랜잭션 수집: 마이닝 노드가 전파된 트랜잭션을 수집해 메모리 풀에 저장 
3. 블록 템플릿(임시 블록) 생성: 피라미드 쌓기 
4. 작업 증명(PoW): 블록 헤더의 해시값이 네트워크에서 요구하는 난이도 목표 이하의 값이 되도록 논스 값을 변경하며 반복적으로 해시 계산 
5. 블록 검증 및 전파: 유효한 해시값을 찾으면 블록이 채굴(생성)됨. > 브로드캐스트 > 다른 노드들이 새 블록의 유효성 검증 
6. 블록체인에 추가 
7. 보상 지급: 코인베이스 트랜잭션 
8. 새 블록 이후 체인 확장 

작업증명이 뭔가요?  
- 네트워크 참여자(마이너)가 퍼즐 게임에 참여해 먼저 퍼즐을 푸는 사람이 보상을 받는 경쟁적 구조. 

PoW 작동 방식을 설명하세요. 
1. 트랜잭션 모으기 
2. 퍼즐 문제 해결 
3. 블록 검증 
4. 보상 지급 

Hash Puzzle에 사용되는 값은? 
마이너는 아래 값들을 하나의 값으로 모아서 SHA-256 해시 함수를 실행함. 
- 이전 블록의 해시 
- 머클 루트 
- 타임 스탬프 : 이전 블록의 타임스탬프보다 크고 네트워크 현재 시간보다 2시간 이내여야 함. 
- 난이도: 네트워크에서 설정 (예: 비트코인 목표는 10분마다 1개 블록 생성); 블록 해시 값 앞 부분에 0이 몇 개인지가 중요  
- 논스 : 유효한 해시를 찾기 위해 반복적으로 변경되는 값; 유일한 변수 

체인 분기(Fork)는 왜 발생하나요? 
- 두 명의 채굴자가 동시에 블록 생성 및 브로드캐스트
- 네트워크 지연으로 일부 노드가 특정 블록을 먼저 수신하고 다른 블록을 뒤늦게 수신했을 경우 

분기 상태에 대해 설명하세요. 
- 두 체인의 길이가 동일하며 각각 다른 노드 그룹에서 다른 체인을 유효한 체인으로 인식하는 일시적인 상태. 
- 네트워크는 가장 긴 체인(또는 가장 많은 작업량을 포함한 체인)을 신뢰하며 새 블록이 추가됨에 따라 다음 블록을 채굴하기 위한 작업이 반복됨. 

체인 리오르그(Chain Reorganization)이란? 
- 분기 체인 중 가장 긴 체인 선택하는 과정. 가장 긴 체인이 메인 체인으로 선택되면, 기존의 짧은 체인의 블록들은 무효화되고 버려진 블록, 즉 고아 블록이 됨. 이 고아 블록들은 다시 멤풀로 반환되어 다른 블록에 포함될 기회를 얻게 됨. 

PoW의 장단점에 대해 말하시오. 
- 장점1: 높은 보안성 
- 장점2: 검증 용이성(블로 헤더의 해시 값을 계산해 블록이 타켓 값 조건을 만족하는지 확인) 
- 단점1: 에너지 소모가 큼 
- 단점2: 확장성 문제(비트코인은 초당 약 7건의 트랜잭션 처리 할 수 있어 대규모 사용자 지원 어려움)
- 단점3: 높은 진입 장벽(고성능 하드웨어와 막대한 전력 비용) 
- 단점4: 중앙화 위험 

만약 공격자가 PoW 네트워크의 해시 파워의 51% 이상을 장악하면 어떤 일이 벌어지나요? 
- 블록 생성 독점 
- 이중 지불: 이전 트랜잭션 취소하고 새 체인을 생성해 코인을 다시 사용
- 네트워크 방해 : 다른 채굴자들이 유효한 블록을 생성하지 못하도록 방해. 

PoS에 대해 설명하세요. 
- 지분증명. 네트워크 참여자의 지분을 기준으로 블록을 생성하고 합의를 이루는 방식. 
- PoW와는 달리 에너지 효율성과 확장성이 높음. 

PoS 네트워크에서 블록이 생성되는 과정은?  
1. 지분 기반 참여: 스테이킹  
2.  검증자 선택: 네트워크는 무작위 알고리즘으로 블록 생성자 선택. 선택 기준은 스테이킹된 코인의 양과 코인을 스테이킹한 기간. 
3. 블록 검증 및 추가: 선택된 검증자가 블록 생성하면 나머지 검증자가 이를 검증하여 블록체인에 추가 

PoS의 장단점에 대해 말하시오. 
- 장점: 에너지 효율, 확장성(블록 생성 속도 빠름), 보안성(경제적 페널티) 
- 단점: 지분 집중화 문제(초기 지분 많으면 유리), 복잡성(구현 및 운영 복잡) 

PoS의 보안성에 대해 설명하세요. 
다음 두 보안 장치가 있음. 
1. Slashing: 악의적 검증자는 스테이킹된 자산을 잃을 위험이 있음. (예: 이더리움 2.0) 
2. 51% 공격 방지: PoW에서는 해시 파워 과반수를 장악해야 하지만, PoS에서는 네트워크의 과반수 지분을 확보해야 함. 

Nothing at Stake 문제란? 
- PoS 블록체인에서 검증자가 여러 체인에 동시에 서명해 네트워크의 신뢰성/일관성을 저하시킬 위험. 
- 문제 원인: PoW와 달리 경제적 비용 없이 여러 체인에서 작업할 수 있는 구조. 
- 문제의 결과: 합의 실패(혼란), 체인 분기로 인한 보안 위협(이중지불, 정당한 거래가 무효화될 가능성), 네트워크 신뢰 손상 

PoS에서 Nothing at Stake 문제 해결 방안 
- 경제적 패널티(Slashing) 
- 체인 선택 규칙 : Longest Chain Rule - 가장 긴 체인(또는 가능 많은 작업 증명을 포함한 체인)이 유효한 체인. 
- 경제적 인센티브 설계 
- 검증자 서명 공개 

DPoS(위임 지분 증명)이 무엇인가요? 
- PoS에서 고래만 계속 블록생성할 위험 (중앙화 위험)을 해결하기 위해 만들어진 것 
- 대표자(Delegate)를 선출해 블록 생성과 검증을 맡기고 이 대표자가 네트워크 블록 생성과 검증을 담당하는 합의 알고리즘. PoS 효율성 개선과 PoW 탈중앙화 유지를 목표로 설계됨. 

DPoS 작동방식 설명하세요. 
1. 대표자 선출.: 사용자가 지분을 위임하여 투표로(내 코인으로) 대표자 선출  (예: EOS) 
2. 블록 생성과 검증: 대표자들이 번갈아 가며 블록 생성; PoS처럼 복잡한 해시 계산이 필요 없어 블록 생성 속도가 매우 빠름 
3. 보상 분배: 대표자는 블록 생성으로 받은 보상을 자신에게 투표한 사용자와 공유함 
4. 대표자 교체: 사용자는 언제든 자신의 투표를 변경해 대표자 교체 가능 

DPoS의 장단점에 대해 설명하세요. 
- 장점: 소수의 대표자가 블록을 생성해 블록 생성과 검증 속도가 빠름; 에너지 효율; 미국 대통령 선출 방식처럼 민주적 구조; 실시간 부정직한 대표자 빠르게 교체 가능 
- 단점: 대표자 담합 등 중앙화 가능성; 낮은 투표 참여율; 대표자 신뢰 문제 

DPoS 블록체인 사용하는 곳은? 
- EOS, Tron, Steem 

DPoS의 보안 장치는? 
- 대표자 교체 가능 
- 경제적 인센티브 (부정행위시 신뢰 잃고 보상 못 받음; Slashing) 
- 투명성 

채굴 이란? 
- 블록체인 네트워크에서 노드로 새로운 불록을 생성하여 체인에 연결하고 보상을 받는 것 

반감기의 역할은? 
- 채굴 보상이 주기적으로 절반으로 줄어들게 함으로써 암호화폐의 공급량을 조절하고 희소성을 유지하며, 궁극적으로 암호화폐의 가치를 보호함. 

거래수수료는 누구에게 주나요? 
- 채굴자와 검증자에게 보상을 지급 
- PoW에서는 채굴자에게만, PoS에서는 검증자에게만 

거래 수수료는 어디에 쓰여요? 
- 네트워크상의 스팸 공격 줄이기 
- 거래 수수료로 트랜잭션을 확인하고 유효성을 검증하는 사용자에게 인센티브를 제공함 

비트코인의 채굴자를 이더리움에서 뭐라고 부를까요? 
- 블록 제안자(proposer)

채굴풀이란? 
- 채굴을 위해 만들어진 조합 

채굴 풀의 위험성(51% 공격) 을 극복한 좋은 사례: GHash.IO - 탈중앙화를 지키기위해 스스로 51% 이하로 해시 파워를 줄인 사례 


/////

2/7 

튜링 기계 
- 앨런 튜링(Alan Turing)이 제안한 가상의 계산 모델. 
- 구성 요소: 무한한 길이의 테이프(데이터 저장), 읽기/쓰기 헤드, 상태 머신(현재 상태와 입력에 따라 동작을 결정하는 규칙 집합) 
- 모든 계산 가능한 문제를 모델링할 수 있는 이론적 컴퓨터. 

튜링 완전성에 대해 설명하세요. 
- 토스트기 밖에 없는 주방에서는 빵 굽기 밖에 못함 (튜링 불완전함) 
- 모든 도구와 리소스가 있는 주방에서는 어떤 요리도 가능함 (튜링 완전함) 
- 계산기 vs. 컴퓨터 
- 반복문과 조건문이 가능해야 튜링 완전함. 
- 즉, 튜링 완전성은 튜링 기계와 같은 계산 능력을 가졌음을 의미한다. 어떤한 계산 가능한 문제도, 적절한 알고리즘과 충분한 리소스(시간과 메모리)가 주어진다면 해결할 수 있다. 
- 블록체인에서 튜링 완전성을 가진 플랫폼은 더 많은 유연성을 제공하지만 동시에 더 많은 책임과 위험 관리가 필요함. 

이더리움은 튜링 완전한가요? 
- 네, 이더리움의 EVM은 튜링 완전성을 지원해 복잡한 스마트 계약 생성을 가능하게 함
- 튜링 완전해서 생길 수 있는 문제: (1) 무한 루프 문제(이를 막기 위해 가스 제한을 둠), (2) 보안 취약점 발생 가능 

비탈릭 부테린은 왜 이더리움을 만들었나요? 
- 프로그래밍 가능한 블록체인을 만들겠다는 목표로 (비트토인 op 코드 몇 개로는 그러기 어려움) 

이더리움 핵심 목표는 무엇인가요? 
- 스마트 계약 
- DApps 
- 프로그래밍 가능성 : 튜링 완전한 언어(Solidity)를 통해 블록체인 상에서 복잡한 프로그램 구현 가능 

이더리움은 왜 프로그래밍이 가능한 블록체인일까? 
- 스마트 계약: Solidity와 같은 프로그래밍 언어로 작성되며, 특정 규칙을 코딩하고 이를 블록체인에 배포하여 실행할 수 있음. > 다양한 DApps을 실행할 수 있는 플랫폼이 됨.  
- EVM: 이더리움 네트워크에서 스마트 계약을 실행하는 환경. 
- 튜링 완전성: 스마트 계약이 튜링 완전한 언어로 작성됨. > 계약이 매우 유연하고 강력한 기능을 제공할 수 있음.  

비트코인과 이더리움은 설계 목적이 어떻게 다른가? 
- 비트코인: 디지털 통화(가치 저장 및 거래)가 목적. 단순하고 안정적인 네트워크 설계 
- 이더리움: 스마트 계약 및 DApp 실행이 목적. 유연하고 확장 가능한 네트워크 설계. 


ECDSA가 뭔가요? 
- 타원 곡선 암호학을 기반으로한 디지털 서명 알고리즘. 
- 기존 RSA보타 짧은 키 길이로도 높은 보안성을 제곰하며, 개인키로 서명을 생성하고 공개키로 이를 검증하는 방식으로 동작함. 
- 장점: 속도와 보안성을 동시에 확보할 수 있음. 
- 비트코인, 이더리움에서 거래 서명과 인증에 쓰임. 

이더리움의 블록체인 모델은 비트코인과 어떻게 다른가요? 
- 비트코인은 UTXO 기반 모델, 이더리움은 계정 기반 모델 
- 비트코인 모델에서는 UTXO 합이 잔액임, 이더리움에서는 계정 잔액. 

이더리움 계정의 종류 2가지는 무엇인가요?  (꼭 이해하기***) 
    - 외부 소유 계정(EOA): 사람이 씀. 프라이빗 키가 있어 디지털 서명 할 수 있고 트랜젝션 생성 할 수 있음.
    - 스마트 계약 계정(CA): 특정 코드가 배포된 계정. 프라이빗 키가 없어서 트잭 생성 못함 (출금 못함). 스스로 트잭 생성은 못하지만 EOA가 요청한 트랜젝션 만들 수는 있음 (인터널 트랜잭션). 

이더리움의 논스와 비트코인의 논스는 어떻게 다른가요?  (꼭 이해하기***) 
- 해당 계정에서 보낸 트랜잭션의 횟수/순서 (비트코인에서는 시도 횟수로 PoW 채굴 과정에서 유효한 해시를 찾기 위해 사용)
- 이중지불을 비트코인에서는 UTXO로 방지 - 사용된 UTXO 값은 더하지 않음. 미사용된거 합치면 잔액. 이미 소모된 UTXO를 다시 사용하는 트잭은 유효하지 않고 네트워크에서 거부됨. 
- 이중지불을 이더에서는 논스로 막음. 즉 재생 공격(replay attack)을 방지함.  
- 이더리움의 논스는 계정별 트랜잭션의 고유 식별자 역할을 함.

이더리움에서 재생 공격 방지 방법은?  
1. 논스 사용   
2. 체인 ID: 포크된 체인에서 체인 ID를 도입해 각 체인을 구분함. 예: 이더리움과 이더리움 클래식은 서로 다른 체인 ID 사용 

EVM이란? 
- Ethereum Virtual Machine. 우리가 작성한 코드와 이더리움 블록체인 사이에 존재하는 가상 머신.
- 여행갈 때 가져가는 어댑터 
- 이더리움에서 스마트 계약 기반의 dApp은 Solidity로 작성됨. Solidity 코드를 Solidity 컴파일러(solc)를 사용해 EVM이 이해할 수 있는 Bytecode로 변환. -> 바이트코드를 이더리움 네트워크로 배포-> EVM이 바이트코드를 해석하고 실행함. 

EVM에서 바이트코드는 스택 기반 아키텍처로 실행됩니다. 바이트코드가 실행되는 과정을 설명해보세요. 
- EVM은 명령어를 Opcode로 해석하며 모든 연산은 스택을 이용해 처리됨. 
- 스택, 즉 프링글즈 과자처럼 먼저 들어온 대로 쌓아 올리고, 맨 마지막에 올린 것 부터 꺼냄. 

EVM에는 보안을 위한 어떤 장치가 있나요? 
- 보안 격리(Sandboxing): 스마트 계약 간 충돌을 방지하며, 잘못된 코드가 네트워크나 다른 계약에 영향을 미치지 않도록 격리된 실행 환경을 제공함.  
- 가스(Gas): 바이코드 실행에는 가스 비용이 소모됨. 각 Opcode는 실행 비용에 따라 특정 가스 양이 할당됨. 

스마트 컨트랙트란? 
- 블록체인 네트워크에서 호스팅되고 실행되는 프로그램으로, 특정 조건을 설정하고 해당 조건이 충족되면 자동으로 계약을 이행하도록 설계된 자동화된 계약 실행 프로토콜임. 
- * 프로토콜: 컴퓨터나 네트워크 시스템이 데이터를 주고받을 때 따르는 규칙과 절차. 데이터 전송 방식, 오류 처리, 인증 절차 등을 표준화하여 다른 시스템간 원활한 통신을 가능하게 함. 디지털 세계에서 ‘언어’와도 같은 역할을 함. 
- 블록체인의 분산 구조와 암호화 기술로 인해 계약 조건이나 이행 내용을 변조하기 어렵고, 계약을 신뢰하기 위한 제3자가 필요하지 않음. 

닉 재보는 스마트 컨트랙트를 어떻게 정의 했나요? 
- 계약 조건을 실행하는 전산화된 트랜잭션 프로토콜은 일반적인 계약 조건을 만족하고, 악의적이거나 우발적인 예외를 최소화하며, 신뢰할 만한 중개자의 필요성을 최소화 하는 것을 목표로 한다. 마치 자판기와 같다. 

스마트 컨트랙트가의 장점이 뭔가요? 일반적인 중앙집권화된 디지털 계약과 비교해 설명하세요. 
- 보안: 분산형 블록체인에서 실행되어 Single point of failure 위험이 없음. 
- 신뢰성: 모드 노드에 의해 검증되어 계약 위변조가 매우 어려움. 
- 공평함: 수수료 없고, 특정 용의적 목적의 제3자가 필요 없음. 
- 효율성  

스마트 컨트랙트의 한계점은? 
- 배포 후 작동 수정이 불가능함: 보안 허점이 발견될 경우 해킹에 취약해 질 수 있음. 프록시 패턴과 같은 컨트랙트 업그레이드 방법이 개발되었으나 완벽한 해결책은 아님.  
- 블록체인 외 정보를 스스로 얻지 못함. 오라클을 사용하지만, 그 데이터가 신뢰할 수 있는지, 전달 과정에서 오류가 발생하지 않는지 확인해야 함. 악의적인 데이터 입력 시 계약이 의도하지 않은 방식으로 실행될 위험도 있음. 


지갑에 EVM 계열 블록체인 노드를 어떻게 연결하나요? 
- 지갑은 특정 노드의  RPC URL(노드 주소)을 이용해 블록체인에 저장된 온체인 데이터를 요청할 수 있음. 이러한 노드와의 통신 방식은 RPC(Remote Procedure Call)이라고 하며 RPC URL을 통해 연결함. 

메타마스크에서 다른 지갑 주소로 KAIA 보내며 컨펌을 누르면 어떤 일이 벌어지나요? 
1. 트랜젝션 세부 정보가 명확히 표시됨. 유저는 승인 진행 
2. 개인키로 트랜잭션에 디지털 서명 
3. 서명된 트랜잭션은 네트워크로 브로드캐스트 되어 처리됨 
4. 네트워크가 트랜잭션 처리하고 블록에 포함한 뒤 상태 업그레이드 


////
2/10
웹이란? 
- 인터넷 위에서 동작하는 정보 시스템 
   
인터넷과 웹은 어떻게 다른가? 
- 인터넷은 도로, 웹은 도로를 달리는 자동차. 
- 인터넷은 물리적 네트워크 인프라, 웹은 웹 브라우저를 통해 사람들이 정보를 검색, 읽기, 쓰기 할 수 있고 상호작용할 수 있는 공간 

웹은 왜 만들어 졌나요? (어떤 문제를 해결하기위해 만들어졌나요?) 
- 각 과학 연구소마다 다른 시스템으로 데이터 저장 및 접근 > 데이터 찾고 이해하기 위해 시간과 노력 많이 소요. > 하나의 통합된 플랫폼을 통해 데이터 공유하고 접근 가능성 높일 필요성 

군사나 학술 목적으로 사용되던 인터넷이 언제부터 확산화되기 시작했나요? 
- 1983년 TCP/IP 프로토콜이 만들어 지면서. 
- TCP/IP 프로토콜: 우리만의 규약. 
- 데이터를 패킷화, 주소 지정 및 전송, 라우팅, 수신하는 방법에 대한 일련의 규칙 제공 (마치 택배 배달 하는 것처럼) 

팀 버너스가 제안한 www의 개념을 설명하세요. 
1. 하이퍼텍스트(링크)의 활용 
2. 인터넷을 활용한 글로벌 정보 공유 
3. 웹의 구성 요소 
           - HTML: 웹 문서 구조 정의; 태그 기반 언어이고 태그 안에는 약속된 기능이 있음  
           - HTTP: 클라이언트와 서버 간에 데이터를 주고받는 프로토콜; 요청과 응답 구조 
           - URL: 웹 리소스의 위치를 정하는 주소; 구조: 프로토콜://도메인/경로?쿼리문자열# 프래그먼트 
                      - 프로토콜: 데이터를 주고받는 방식 
                      - 도메인: 서버 주소 또는 IP 주소 
                     - 경로: 서버 내에서 자원의 위치 
                      - 프래그먼트: 문서 내 특정 위치 

현재 웹 표준을 담당하는 기관은 어디인가요? 
- 팀 버너스 리가 주도하는 W3C(World Wide Web Consortium)  

Web의 발전 과정을 설명하세요. 
Web 1.0 - 사용자가 데이터를 받는다.  예: 게임 공지 
Web 2.0 - 사용자도 데이터 만들고 공유할 수 있다. 예: 홈페이지  
Web 3.0 
     - 지능화, 개인화, 탈중앙화를 중심으로 하는 차세대 웹. 
     - 사용자의 데이터 소유권과 분산 네트워크 강조 
     - 블록체인, AI, 스마트 계약, 시맨틱 웹 
     - 확장성 문제: 네트워크가 커질수록 처리 속도가 느려지는 문제 
     - 네트워크 속도 문제: 블록체인은 전 세계 노드 간 데이터 전파가 필요하며, 인터넷 속도가 느려면 합의 과정이 지연됨. 
Web 2.5. 


DNS: Domain Name System. 도메인 이름과 IP 주소를 연결해 주는 시스템. 

클라이언트 동작 과정을 설명하세요. 
1. 사용자가 브라우저 주소창에 https://www.example.com 입력 
2. 브라우저가 해당 URL의 DNS를 조회하고 서버 IP 주소 획득 
3. 서버에 HTTP GET 요청을 전송 
4. 서버로부터 HTML 문서와 관련 리소스를 응답받음 
5. 브라우저가 HTML, CSS, JavaScript를 해석하여 사용자 화면에 표시 
6. 사용작 버튼을 클릭하거나 입력을 추가하면 추가 요청을 서버로 전성 

서버 종류는 어떤 것이 있나요? 
- 웹 서버 : 주로 배포 단계에서 
- 애플리케이션 서버: 동적 요청 처리(예: 데이터베이스와 상호작용, API 호출, 주로 서비스 로직 개발에 사용 
- 데이터베이스 서버 
- 파일 서버 : 클라이언트에 파일을 저장하고 전송. 클라우드 기반 파일 서버가 주로 사용됨.

풀스택 개발자: 클라이언트와 서버의 구성 요소를 모두 개발할 수 있는 개발자 

클라이언트와 서버는 어떻게 다른가요? 
- 행사장 뒷편에서 물품을 나르는 역할을 하는건 서버. 
- 행사장에서 참가자들 관리하는건 클라이언트 

블록체인의 노드와 웹 개발의 노드는 어떻게 다른가요? 
- 블록체인에서의 노드는 블록체인 네트워크에 연결된 컴퓨터를 말하며 여기서 노드는 데이터 저장, 검증 등을 한다 
- 웹 개발(Node.js)에서의 노드는 자바스크립트를 이용해 시스템을 만드는 서버이다. 

웹 개발에 쓰이는 기본 언어 3가지가 무엇인가요? 
- HTML, CSS, JavaScript 
- 각각 다른 언어고 쓰임세가 다름 
- 웹페이지 구성 도구 

html에 대해 말해보세요. 
- Head - 속성 
- Body - 구조 
- Html  문서는 브라우저가 올바르게 해석할 수 있도록 .html 파일 확장자가 필요함. 

CSS에 대해 말해보세요. 
- Style 태그 안에 넣어야 함 
- 선택자(selector)를 사용해 특정 HTML 요소에 스타일을 적용. 
- P { color: red; }
- 선택자Selector { 속성property: 속성값property value;}
- 박스모델: padding - border - margin 

JavaScript에 대해 말해보세요. 
- Script 태그 안에 넣어야 함 
- 다양한 라이브러리(jQuery, Lodash) 및 프레임워크(React, Vue.js)와 함께 사용 가능 

터미널 기반 텍스트 편집기를 사용해 내용 입력 후 저장하는 과정은? 
- % vim test.html  
- I -> 내용 입력 -> ESC -> :wq (저장 후 종료) 

HTML 문서를 브라우저에서 볼 수 있는 이유는? 
- 브라우저가 HTML 문서를 해석하고 렌더링 하는 기능을 가지고 있기 때문. 

코딩이란? 
- 명령어를 사용해 컴퓨터에 작업을 지시하는 과정. 이를 위해 코드 실행 가능한 런타임 환경에서 구동해야 함. 


VS Code의 확장 프로그램 Liver Server는 왜 필요하죠? 
- HTML, CSS, JS 파일을 실시간으로 브라우저에서 자동 새로고침 하며 실행해줌. 

* 노트: 확장프로그램 Codeium: AI Coding Autocomplete!  (나중에 쓸 것) 

VSCode에서 코드 자동 정렬 방법
- 윈도우: Shift + Alt + F 
- macOS: Shift + Option + F 
- Linux: Ctrl + Shift + I 
- 혹은 마우스 우클릭 > “Format Document” 누르기 



////
2/11

Shift + Option + F : 들여쓰기 자동완성 

Ctrl + Shift + I (VS Code에서 자동 정렬)

VSCode에서 코드 자동 정렬 방법
- 윈도우: Shift + Alt + F 
- macOS: Shift + Option + F 
- Linux: Ctrl + Shift + I 
- 혹은 마우스 우클릭 > “Format Document” 누르기 


폴더 만들고, 파일 만들고, 파일에 글 쓰기 
1. 폴더 만들기 - mkdir folder.git
2. 폴더로 이동 - cd folder.git
3. 폴더에서 파일 만들기 - touch filename.txt 
4. 파일에 글 쓰기 - echo ‘Hello, Git!’ > filename.txt 


피일을 로컬 -> 원격 옮길 때 쓰는 명령어 3개는? (**중요) 
1. git add (파일이름 혹은 . ): 상태는 마치 노드 멤풀에 트랜젝션들이 모여있는 상태. 
2. Git commit -m ‘메세지’ : 동료들이 내 메세지 보고 어떤 작업 했는지 파악이 되어야함
3. Git push origin main : 여기서 origin은 이 코드가 원래 있어야 할 곳 (마스터 브랜치, 여기선 원격저장소); main은 브랜치 
* Git help 치면 git 명령어 볼 수 있음 

브랜치끼리 충돌할 때, 덮어쓰지 말기. (**중요) 
Git pull origin main —no-rebase. (**중요) 
- rebase: 우리 코드가 먼저다, 덮어 써라는 뜻. 
- 덮어쓰지 않도록 no rebase로 

브랜치 만들고 그 브랜치로 이동할 때 쓰는 명령어 
- Git checkout -b 브랜치이름 


아래 습관화 하기. 출근 하자마자 이거 하고 시작. 이래야 충돌 안 남. (** 중요) 
- Git fetch —all : 모든 원격 저장소 최신화 
- Git pull origin main : 원격 저장소 origin의 main 브랜치 코드를 가져옴 

