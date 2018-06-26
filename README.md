## 내멋대로 프로젝트

어느덧 개발경력이 10년이나된 중년 개발자가 되었다.
나름 참 열심히 해왔다고 위안하면서도 나도 모르게 나태해지진 않았을까? 라는 의문을 가지며
이 프로젝트를 시작하게 되었다.

거창한 목적은 없는 프로젝트이다. 어쩌면 자기만족을 위한 프로젝트랄까.
하지만 작은 소망이 있다면 누군가 나와같은 고민을 할지 모르는 사람들에게 도움이 되었으면 한다.

### 프로젝트를 기획하면서

어쩌면 시작은 굉장히 충동적이었다. 딱히 계획도 없고 목적도 없었다. 
무작정 여행을 떠나기위해 집을 나서듯 '새로운 것들을 해보자' 라는 어린아이 같은 마음으로 시작했다.

당연히 처음부터 헤매었다. 하지만 '근데 이제 뭐하지 ㅡㅡ?' 라며 헤맬때 여러가지 조언을 해준 친구, 선배들 덕분에 하나하나 시작할 수 있었다.

Docker, AWS, MSA, RestApi, Springboot.. 하나하나 무작정 따라하기 시작하면서 조금은? 감을 잡기 시작하였다.
AA 업무를 5년동안 수행하며 나무가 아닌 숲을 볼 수 있을정도의 안목은 있었는지 대부분의 기술을 연결하여 하나의 큰 흐름을 잡을 수 있었다.

이제부터 하나하나 프로젝트를 진행해온 과정, 기술, 격었던 어려움등을 기록해보려한다.

### 프로젝트 진행초기 어려움

누군가 변화하고 싶다면 환경을 바꿔보라고 권해주고 싶다. 환경을 바꾸는 방법중에 새로운 사람을 만나보는것은 좋은 방법중 하나인것 같다.
내가 그랬다. 같은 회사에 오래 있다보니 맡은 일에 대해서는 자신 있었다. (참고로 내 대부분의 경력은 공공 SI에서 PL, AA, 개발자 이다).
하지만 이 테두리를 조금만 벗어나면 내가 얼마나 아는게 없는지 종종 느낀다.

진행초기 가장 어려웠던 점은 10년동안 프로젝트를 진행하며 가지게된 편견이랄까? 
오로지 내 의사결정만으로 방향이 잡아지는 자유분방한 프로젝트는 처음이라 무엇부터 해야할지 당황스러웠다. 
계획부터 수립해볼까라고 생각할때쯤 웃음이 나왔다. 왜? 누구도 안볼건데 만들필요가 없었다.

그럴때 도움을 준게 항상 곁에 있던 친구다. 
그 친구와 프로젝트를 공유하면서 편하게, 호기심 가득하게 내멋데로 프로젝트를 진행 할 수 있게 조금씩 변해갔다.

### 프로젝트 기술요소

부끄러운 이야기지만 프로젝트를 구성하는 모든 기술요소는 전부 처음 해보는 것들이다. (평소 알고는 있었다하더라고 구현은 처음이다;;)
내가 다양한 기술에 익숙치 못한점도 있지만 일부러 내가 익숙한 기술은 전부 배제했기 때문이기도 하다.

처음엔 방향이 없었지만 하나씩 무작정 따라하다 보니 몇가지 구현해보고 싶은 방향과 키워드가 생겼다.
MicroService Architecture, DevOps, OpenSource 이다. 사실 한분야 한분야가 많은 지식과 노하우를 요구한다는건 알지만 뭐어떤가?
내멋대로 이런 것들을 흉내 내보기로 했다.

- SpringBoot : 잘한다고 말은 못하지만 배운게 JAVA 라 ㅠ_ㅠ 그나마 만만했다.
- JPA : Hibernate 시절부터 친구와 단골 논쟁거리였던 ORM 이다. 나로서는 업무에 도입할 일이 없었고 복잡한 쿼리에 대응할 수 있을지 많은 의구심이 든  API 이다. 그래서인지 이럴때 과감히 써보고 싶었다.
- RestApi : 옛날부터 궁금했다. 철처히 독립된 시스템간의 의사소통방식은 어떻게 할까?
- GitHub : 참.. 지금까지 이걸 안써봤다는게 부끄러울 따름이다. SVN, CVS 가 아닌 첫 형상관리 도구이다.
- Travis : CI를 고민할때쯤 친구의 추천으로 쓰게되었는데 참편하다. 당연한 이야기겠지만 GitHub 와 찰떡 궁합인듯 하다.
- Coveralls :  아직 제대로 쓸줄은 모른다 ㅠ_ㅠ 앞으로 해볼 생각이다. 연동만 해놨다.
- Slack :  예전에 잠깐 구경정도 해봤는데 써볼수록 장점이 많은것 같다.
- Trello : 애자일 코스프래를 해보려했는데 혼자라 의미가 없드라 ㅎㅎ 연동만 해놓으려한다 ㅠ_ㅠ
- AWS : 클라우드 흉내내기다. 사실 뭔가를 하고싶은데 개인 개발자 입장으로 가볍게 서버환경을 구성하기에는 AWS 프리티어 짱인듯하다.
- Docker : 호기심에 시작했지만 해보고나니 써야할 이유가 참 많은것 같다.
- Kubernetes : 운영환경 기술의 꽃이 아닐까 생각된다.








```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cain0605/cain0605.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
