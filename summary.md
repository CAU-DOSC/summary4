__성당과 시장__ (The Cathedral and the Bazaar) 요약
==================================================

Contents 0 ~ 2 (20163786 박세현)
------------------------------

__1. 성당과 시장__

저자는 기존의 오픈소스 참여자였지만 리눅스를 만나기 전 까지는 오픈소스로는 간단한 프로그램만 만들 수 있다고 생각했다. 그러나 리눅스가 수 많은 사람들에 의해서 안정적이고 일관성있는 운영체제가 보고는 생각이 바뀌었다. 기존의 운영체제가 반드시 `성당`스타일 처럼 소수의 베테랑 프로그래머들에 의해 설계되어야 된다고 생각했지만 리눅스의 성공을 보며 `시장`스타일의 가능성을 보았고 이러한 믿음을 증명하기 위해서 새로운 오픈소스 프로젝트를 시작했다.

__2. 메일은 반드시 배달되어야만 한다.__

그는 1993년 펜실베이나 주, 웨스트 체스터에서 작은 무료 IPS를 운영하면서 `locke`이라는 멀티유저 게시판 소프트웨어를 작성했다. 그는 다른 유저들과 소통을 하기위해서 인스턴트 인터넷 이메일을 사용했는는데 그에게 매우 불편한 경험을 선사했다. `locke`내의 유저가 그에게 이메일을 보내고 그가 자신의 로컬 시스템으로 이메일을 가져와 읽은 후 답장을 하려하면 로컬 시스템 내의 유저에게 답장을 하려고 했기때문에 이메일 주소 뒤에 `@ccil.org`를 손수 붙여야했다.
자신에게 필요한 프로그램을 만들려했지만 처음부터 설계하는건 좋은 생각이 아니라 여겨 `Carl Harris`의 `popclient`를 자신이 원하는 기능을 추가하고 수정하기로 했다.
이러한 과정 속에서 그는 우리에게 여러가지 교훈을 제시해준다.

Contents 3 ~ 4 (20154645 팽진욱)
------------------------------

__3. 사용자가 있다는 것의 중요성__

그는 popclient를 물려받으면서 동시에 사용자들도 물려 받았다.
그는 많은 사용자들을 갖는다는 것의 중요성을 명확하게 알고 있었다. 사용자들을 그냥 사용자가 아닌 공동 개발자로서 생각하면서 코드를 다른 어떤 방법보다 빠른 속도로 개선시키고 디버깅 할 수 있다는 사실을 알고 있었다.
이는 선례로 리누스 토발즈가 명확하게 보여주었다.
리누스 토발즈는 다른 성당건축(Cathedral) 스타일과는 다르게 프로그램을 유동적으로 사용자가 주도하게 하였다.
이를 미루어 보아 그가 fetchmail 이전에 했던 가장 성공적인 해킹은 Emacs VC 모드였다. 이를 위한 세 명의 사람들은 email을 통해 리눅스와 비슷한 협동작업을 하였고, 이는 코드의 발표/테스트/개선 주기를 빠르게 반복하게 하였다.

__4. 일찍, 자주 발표하라.__

일찍, 자주 발표하는 것은 리눅스 개발 모델 중 중요한 부분이다.
이전의 대부분의 개발자들은 이러한 정책이 나쁘다 생각하였고, 성당건축(Cathedral) 스타일의 개발을 선호하였지만 이러한 개발모델의 문제점들에 의해서 큰 실패를 겪었다.
그 후 성당건축과는 완전히 반대되는 정책의 리눅스가 널리 알려지기 시작했고, 이는 가장 효과적인 방식으로 사용자들을 공동개발자라고 생각하여 일찍, 자주 발표하고, 소비자들에게 귀를 기울였다.
그가 생각하기에 리누스는 제임스 고슬링같은 천재는 아니었다. 대신 공학의 천재인 것으로 봤다. 버그, 개발의 막다른 골목을 피하는 가장 좋은 방법의 설계를 리누스라는 본질적으로 보수적이고 단순한 설계방식으로 해낸것이다.
"문제를 보고 있는 눈이 충분히 많으면 찾지 못할 버그는 없다." 리누스의 법칙이다. 리누스는 '어떤 특정한 사람에게는 문제가 간단할 수 있다. 하지만 그게 중요하다기 보다는 문제를 발견하고 그 문제를 해결하는 데에 있어서 눈이 충분히 많을 경우 이 둘이 모두 빨리 일어나는 경향이 있다는 것이 중요하다'라고 말했다.
수년 전, 사회학자는 비슷하게 전문적인 관찰자들로 이루어진 대중의 평균적인 의견이 그 관찰자 무리 중 무작위로 뽑은 한 명의 의견보다 더 신뢰할 만하다는 점을 발견하였고, 이는 '델파이 효과'라고 불린다. 이 효과는 리눅스로서 확실히 증명되었다고 할 수 있다.
이 효과를 도와주는 리눅스의 특별한 특징은 어떤 프로젝트에 기여한 사용자들은 이 프로젝트를 선택했다는 점이다. 랜덤의 샘플로 모아진 개발자 들이 아닌, 이 프로젝트에 관심이 있고, 문제를 해결하려고 노력하는 집단의 모임이 기여를 하기에 이러한 필터를 거친 사람들은 프로젝트에 유용하다고 판단이 되는 것이다.

Contents 5 ~ 7 (20155265 김재환)
------------------------------

__5. 얼마나 많은 눈이 문제를 지켜보는가__

시장 스타일이 디버깅과 코드 개발을 크게 가속화한다. 프로그램 내부 구조를 모르는 사용자들의 버그 리포트가 어째서 그리 유용하지 않은지 정확히 파악해야 한다. 겉으로 드러나는 증상에 대해서만 서술하고 중요한 백그라운드 데이터를 생략하고 버그를 재현하기 위한 방법에 대해 거의 보고하질 않는다. 여기서 보이는 근본적인 문제는 테스터와 프로그램 개발자의 사고방식이 일치하지 않는다는 점이다. 오픈 소스 개발은 이러한 문제점을 타개 할 수 있습니다. 대부분의 버그는, 대부분의 경우에, 사용자의 오류 환경에 대해 소스 코드 수준으로 표현해주면 표현이 완전하지 않고 암시적이더라도 쉽게 파악할 수 있습니다. 개발자의 시간을 절약해주는 오픈 소스의 또 다른 특징은 오픈소스 프로젝트의 의사소통 구조입니다. 오픈 소스 프로젝트에서 halo 개발자들은 서로간에 영향이 거의 없는 병렬적이고 분리가능한 일을 수행한다. 코드 수정과 버그 리포트는 핵심그룹을 통해 전달되고, 오로지 그 작은 규모의 핵심 그룹 내에서만 브룩시안 오버헤드 비용이 발생하게 된다. 또한 복잡한 multi-symptom 에러를 처리할 때 많은 수의 사람들이 버그를 추적하는 것이 상대적으로 수준이 높은 소수의 사람들이 순차적으로 추적해보는 것보다 훨씬 효과적이다.

__6. 장미가 장미다우려면__

리누스의 행동을 연구하고 그것이 왜 성공적이었는지에 대한 이론을 만든 후, 이 이론을 새 프로젝트에 적용하기로 했다. 가장 먼저 한 일은 popclient 를 더 재조직화하고 단순화한 것이었습니다. 자료구조를 훌륭하게 만들고 코드를 멍청하게 만드는 것이 그 반대의 경우보다 훨씬 잘 작동한다. 그리고 프로젝트를 다음과 같이 시험했다. 일찍, 자주 발표. fetchmail 에 대한 일로 나에게 연락해 오는 사람은 누구든지 베타테스터 목록에 올림. 새로 발표할 때마다 베타테스터들에게 떠들썩하게 발표를 알리며 사람들이 참여하도록 격려. 그들의 이야기를 듣기. 설계 결정에 대해 투표를 하고 패치나 피드백을 보내올 때마다 베타테스터들을 구슬리기. 결과는 훌륭했고 베타테스터들을 가장 중요한 자원으로 여긴다면 그들은 정말 가장 중요한 자원이 되어준다는 결론을 얻었다.

__7. Popclient가 Fetchmail이 되다.__

fetchmail 프로젝트에서 큰 전환이 일어났던 것은 해리 호흐하이저(Harry Hochheiser) 가 클라이언트 머신의 SMTP 포트로 메일을 포워딩하는 대략적인 코드를 보내준 때였다. SMTP 포워딩에 대한 아이디어는 내가 리누스의 방법을 모방하려고 의식적으로 노력한 것에 대한 가장 큰 보답이었다. 사용자 한 명이 내게 끝내주는 아이디어를 주었으며 내가 해야했던 일은 그 의미를 이해하는 것 뿐이었다. 좋은 아이디어를 생각해내는 것 다음으로 중요한 일은 사용자들이 알려준 좋은 아이디어를 깨닫는 것이다. 종종 가장 충격적이고 혁신적인 해결책은 당신 자신이 문제에 대해서 가지고 있는 개념이 잘못되어 있다는 것을 깨닫는 것에서 나온다. 낡아서 사용할 수 없는 기능이라면 효율을 떨어뜨리지 않고 제거할 수 있을 때는 망설이지 말고 제거해 버리라. 설계에 있어서 완벽함이란 더 이상 추가할 것이 없을 때 이루어지는 것이 아니라 더 이상 버릴 것이 없을 때 이루어진다.

Contents 8 ~ 9 (20150577 김찬일)
------------------------------

__8. Fetchmail의 성장__

SMTP 포워딩 기능으로 fetchmail은 경쟁에서 독보적인 능력과 경쟁력을 가지고 있다.
앤드류 타넨바움은 교습 도구로 사용하기 위해 386용으로 간단한 네이티브 유닉스를 만드려는 원래의 아이디어를 가지고 있었다. 하지만 리누스 토발즈는 더 밀고 나갓고, 리눅스는 굉장히 발전되었다. 독창적인 것은 아니었지만, 기준을 높게 잡음으로써 성공한 것이다. 그래서 fetchmail을 최고로 만들기 위해서 다른 사람들에게는 필수적인 기능을 포함시키고 지원해야했다. 프로그램을 단순하고 튼튼하게 유지하면서 해야했다. 가장 중요한 첫번째 기능은 그룸이나 사용자들의 메일을 한꺼번에 가지고 있는 메일 박스에 메일을 다른 개인 사용자들에게 라우트 시켜주는 기능인 멀티드롭이었다. 이것은 어드레싱을 완벽하게 구현함으로써 싱글드롭 코드에 있는 버그들을 잡아낼 수 있을 거라고 생각했기 때문에 사용자와 개발자 모두의 원하는 점 때문에 만들어졌다. 멀티드롭 fetchmail의 용도는 메일링리스트를 유지한 채 SLIP/PPP로 연결된 클라이언트 쪽에서 메일링리스트를 운영하는 것인데, 나는 데이터스트림에 가능한 최소한의 조작만 가하고 강제로 정보를 삭제하지 말라는 규칙에 의해서 8비트에 대비하여 프로그램을 유지시켜왔기 때문에, 8비트 MIME 오퍼레이션을 요구하는 베타테스터들에게 손쉽게 기능을 제공할 수 있었다.

__9. Fetchmail에서 배울 점__

 전통적인 프로그래머들은 짧고 중복이 되지 않는 제어구문을 선호하는데, 컴퓨팅 자원이 비쌌을 때의 이야기이다. 간단히 명칭을 바꾸는 방식은 없어지지 않는 점이 이제는 가격 보다는 사람에게 편리한 가의 관점에서 더 중요해진 것이다. 하지만, 파싱할 때 복잡함에 따른 코스트가 클 경우를 피해야한다. Fetchmail 제어구문은 이런 문제를 피하기 위해서 언어의 영역이 매우 제한했고, 실제 언어를 표현할 때 실제 제어언어로 옮겨가는 경우에 혼란을 일으킬 경우를 매우 줄일 수 있었다.
 또 하나는 불투명함에 의한 보안에 대해서이다. Fetchmail은 읽기 퍼미션을 얻음으로써 스누퍼들이 패스워드를 보지 못하도록하는 것에 대해서 암호화하는 프로세스를 만들지 않았는데 보안이 강화되는 부분이라고 생각하지 않았기 때문이다. 보안시스템을 뚫고 들어온다면, 이미 보안시스템 내부의 정보에 대해서는 디코딩을 통해서 얻을 수 있기 때문이다. 보안시스템은 그것이 보호하려고 하는 비밀만큼만 안전하다는 규칙이다. 뚫고 들어와서 데이터를 보았을 때를 대비한다기보다는 뚫고 들어오지 못하도록 그 보안 시스템에 더 신경을 써야한다.

Contents 10 ~ 11 (20130910 박민서)
------------------------------

__10. 바자르 스타일을 위한 필수적인 전제 조건__

오픈 소스 프로젝트를 하는데 있어서 리더와 협력자들에게 요구되는 역량들은 다양하다. 디자인 능력, 커뮤니케이션 능력 그리고 기본적인 코딩 능력이다. 그 중에서 디자인 능력은 꼭 뛰어나거나 특출날 필요는 없다. 하지만, 여러가지 안 중에서 특출난 디자인을 선별해낼 수 있는 능력은 반드시 가지고 있어야 한다. 여기서 주의해야할 점이 있는데, 과도하게 디자인을 하는데 있어서 영특함과 뛰어남을 가지려고 하면 결국 간단하게 디자인 해야만하는 프로젝트에서도 복잡하게 디자인 한다는 것이다. 
기본적인 코딩 능력은 말할 것도 없다. 오픈소스 프로젝트를 진행하려는 사람은 기본적으로 어느 정도 수준 이상의 코딩 능력을 가지고 있다고 생각한다. 
디자인 그리고 코딩 능력만큼 중요한 것이 바로 의사소통 능력이다. 리누스도 그렇고 나도 그렇고 외향적이고 사람들이 좋아할 만한 성격을 가진 것은 우연이 아니다. 위의 2가지 능력도 당연히 중요하지만, 그것이 전부는 아니다. 반드시 사람을 끄는 매력 좋은 의사소통 능력을 가지고 있어야만 프로젝트를 진행하는데 있어서 큰 도움이 될 것이다. 


__11. 오픈소스 프로젝트의 사회적 맥락__

결국 닫힌 소스를 개발하는 사람과 그룹보다는 오픈 소스 프로젝트를 진행하는 그룹이 더 큰 역량을 발휘할 수 밖에 없다. 서로가 서로를 위해서 헌신하고, 각자 자신의 코드에 텃세를 부리지 않고 수많은 사람들로부터 피드백을 받고 개선안을 받는 오픈 소스 프로젝트에서느 다른 프로젝트에서는 절대 볼 수 없는 엄청난 발전 속도를 볼 수 있을 것이다. 모든 프로젝트에서는 리더십이 중요한데, 이러한 오픈 소스 프로젝트에서 정의하는 훌륭한 리더십이란 과연 무엇일까? 강압적이고 명령을 내리는 방식의 리더십으로 만약 진행을 했다면 현재 리눅스와 같은 좋은 결과물을 볼 수 없었을 것이다. 텃세를 부리지 말고, 순전히 자신의 자아 상승 (주변 다른 프로그래머들로부터 인정을 받거나 본인의 명성이 올라가는 등) 만으로 순순하게 프로젝트에 헌신을 하는 활동적인 오픈소스 커뮤니티가 있기에 이렇게 성공할 수 있었던 것이다. 
결국 미래에는 오픈소스가 도덕적으로 더 옳고 소프트웨어 매점이 도덕적으로 더 옳지 못하고가 아니라 더욱 숙련된 프로그래머의 시간을 많이 쓸 수 있고 특정 문제를 풀려고 할 때 모을 수 있는 인재 풀의 규모에서 오픈소스가 더 우위에 있기에 오픈소스 문화가 결국에는 승리할 것이라고 생각된다.
