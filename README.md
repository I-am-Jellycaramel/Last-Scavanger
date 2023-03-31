# Last-Scavanger
## 개요
text game by python with post-apocalypse and virtual earth story background<br>
파이썬으로 만든 텍스트 게임입니다. 포스트 아포칼립스 세계관에 가상 지구 환경 배경에서 생존하는 것이 목표입니다.

모험/탐험(포스트 아포칼립스 세계관을 탐험) + 매트로배니아 속 일부 요소(맵을 밝히고 못가는 구역은 나중에 성장하고 오면 다시 갈 수 있음) + 로그라이트(메인 게임 진행의 수많은 랜덤성, 각 게임 회차마다 진행된 진행 내역은 게임 오버시 증발) 성향을 가지고 있습니다.

## 지원하는 언어 <br>
- 한국어
- English (future, not yet at 2023-03-30)

## 시놉시스 및 세계관 <br>
이윽고 세계가 멸망했습니다. <br>
기후 위기로 인한 인간 거주 환경이 열악해지고, 세계적인 저출산과 하나둘 사라지는 나라들, 질병과 내전<br>
법을 추월한 과학 기술의 발전, 시대를 따라가지 못하고 도태된 사람들<br>
자산을 지키기 위해 카르텔을 형성하는 권력층들, 화폐는 휴짓조각이 되어 더이상 의미가 없어지고<br>
인프라가 모두 망가진 대도시들, 이 지구에서는 더이상 인간이 살아가기에 힘들어졌습니다.<br>
<br>
항상 어두운 하늘과 과학기술의 반짝임만이 아름답게 하늘을 수놓을 때<br>
살아남은 인류가 세워놓은 최후의 철옹성 곳곳과 그 바깥에는<br>
살고자 하는 의지와 죽고자 하는 의지가 거세된 사람들만이 힘겹게 오늘 하루를 살아가고 있었습니다.<br>
당신은 그런 세계에서 인간을 보조하기 위해 만들어진 **로봇입니다.** <br> 
이제 실시간으로 쓰레기 무더기가 되어가는 이 과학 기술의 세계에서<br>
살아남은 사람들과 쓰레기 무더기를 채워나가야 합니다.<br>
<br>

(정보) <br> 
개발자는 하드웨어 및 과학기술의 발전을 잘 모릅니다. 공상 과학으로 대충 과학기술이 발전하면 이러지 않을까 해서 만든 것들이 대부분이며<br>
어린 시절 도라에몽을 보는 느낌으로다가 플레이해주시길 바랍니다. :D (대충 과학기술이 발전해서 그렇다는 겁니다. <-- 중요) <br>

## 게임 진행 방식 <br>
기본적으로 텍스트/텍스트 어드벤쳐 게임 진행 방식을 따릅니다. 플레이어는 상황을 마주하고 선택지를 골라 게임을 진행하며 각 상황은 랜덤 인카운터로 출현합니다. <br>
이때 선택지는 카드 형태로 제공되며 일종의 패 개념으로 플레이어의 손에 쥐어집니다. 원하는 선택지(카드)를 내서 게임을 진행합니다. <br>
제시된 선택지 중 어떤 선택지를 선택하느냐에 따라 다음 나올 상황에 영향이 끼쳐지며 운을 조절할 수 있는 요소와 각 상황에 대한 대응책을 갖출 수 있는 요소들이 준비되어있습니다. <br>
<br>
게임을 켜면 모험을 나갈지(새 게임 시작), 주거지 이동을 선택할 수 있습니다.<br>
<br>
### 모험 시작
모험이 시작되면 지도를 펼칩니다. 이 지도는 대부분의 상황이 정리되면 펼칠 수 있으며 선택한 지역으로 이동할 수 있습니다.<br>
지역은 모두 무작위로 배치되어 서로 연결되어 있습니다. 지역은 수준이 갈리며 높은 수준의 지역은 추후 성장을 해야 진입할 수 있거나 특정 요소를 요구할 수 있습니다.<br>
처음은 지역이 1 까지만 열려 있으며, 각 지역마다 안으로 계속해서 들어갈 수 있습니다. (예시: 쓰레기장-1 -> 쓰레기장-12)<br>
플레이어는 체력을 가지고 있습니다. 체력이 모두 감소하여 0 이 되면 사망합니다.<br>
또한 플레이어는 배고픔 수치를 가지고 있습니다. 배고픔 수치가 모두 감소하여 0 이 되면 지속적으로 체력이 닳고, 일정 수치 이하면 특정 행동을 할 수 없습니다.<br>
체력은 수리 장치를 사용하면 회복할 수 있고, 배고픔은 전기 팩을 먹으면 회복할 수 있습니다.<br>
사망시 가지고 있던 물품 중 일부를 주거지로 보낼 수가 있습니다.<br>
<br>
### 주거지 이동
주거지에서는 모험에서 얻은 물품 일부를 사용할 수 있습니다. 비축한 물품으로 주거지를 수리하고, 확장하며 다음 모험에 영향을 줄 수 있습니다. (지속적인 게임 요소입니다., 한판 한판에서 게임이 휘발적으로 끝나는 것이 아닌 다음 판에 영향을 주는 요소)
<br>
### 부가 설명
스토리를 메인으로 미는 게임이 아니라, 포스트 아포칼립스 세계관을 탐험하며 살아남는 것이 메인인 게임입니다. <br>
스토리는 간접적으로 제공하며 여러 게임 상황 속 이야기를 통해 유추해보는 방향으로 스토리를 경험할 수 있습니다. <br>
<br>
맵 구성은 맵이 전부 연결되어 있으며 지역 배치는 전체 지역에서 각 지역을 수준별로 분류하고, 각 수준별 지역 중에서 일정량을 뽑아 모두 합산해 배치합니다. <br>
