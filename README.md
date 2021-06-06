#  Git-flow (계속 추가 예정..)

> 1. Git-flow란
>> Vincent Driessen 이 제시한 가장 널리 알려진 프로젝트 git 브랜치 전략  
>> 파생적으로 github-flow, gitlab-flow 등도 존재


> 2. Git-flow를 사용하는 이유  
>> 브랜치 전략을 수립함으로, '코드의 품질' 및 '코드 가독성' 향상  
>> git의 hook 또는 script와 같은 기능을 통해 효율적인 자동화 구성  


> 3. Git-flow전략  
> * 참고그림 - 원작자가 직접 사용한 그림
> ![image](https://user-images.githubusercontent.com/51190295/120925575-1d503080-c714-11eb-8b55-23462937acf3.png)  
>> [단계별 목표]  
>> master (항상유지) : 제품출시의 목적, 자동 빌드 및 배포  
>> develop (항상유지) : 다음 버전의 개발, 테스트 100% 성공 시에만 병합  
>> feature/{feature_name} (일시적) : 신규 기능 개발  
>> release (일시적) : 제품 출시 준비, 제품의 버전체크, QA  
>> hotfix (항상유지): 출시된 버전의 버그 수정, 지속적인 버그 수정  

> 4. 참고사이트  
>> Vincent Driessen 블로그 : https://nvie.com/posts/a-successful-git-branching-model/  
>> donggeun,Bang 블로그 - Git 브랜치 전략의 필요 : https://blog.lulab.net/programming-tools/the-need-for-a-git-branch-strategy/  
>> 휴몬랩 기술 블로그 - git으로 협업하기! : https://devlog-h.tistory.com/6  
