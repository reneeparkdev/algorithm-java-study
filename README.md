# algorithm-java-study
- 개인 스터디
- 참고 도서 : Do it! 알고리즘 코딩 테스트 - 자바 편 / 김종관 / 이지스퍼블리싱(주)<br/><br/>
- 기술 스택 : `Java`
- 사용 툴 : `IntelliJ`, `Mac Terminal`

<br/>
<br/>

## 목표
1. 자바 알고리즘 코딩 능력 향상하기
2. `깃 커밋 컨벤션(git commit convention)`을 지켜서 `커밋 메세지(commit message)`를 작성해보기

    > **Feat** : 새로운 기능 추가<br/>
    **Fix** : 버그 수정<br/>
    **Docs** : 문서 작성<br/>
    **Style** : 코드 포매팅, 스펠링 오류, 세미콜론 추가 등<br/>
    **Refactor** : 리팩토링<br/>
    **Test** : 테스트 관련 코드<br/>
    **Chore** : 추가 유지보수 및 자잘한 수정

    > **Build** : 빌드 관련 파일 수정<br/>
    **CI** : CI 설정 파일 수정<br/>
    **Perf** : 성능 개선

    > **Design** : CSS 등 사용자 UI 디자인 변경<br/>
    **Comment** : 주석 추가 및 변경<br/>
    **Remane** : 파일 혹은 폴더명을 수정하거나 이동하는 작업만인 경우<br/>
    **Remove** : 파일을 삭제하는 작업만 수행한 경우<br/>
    **!BREAKING CHANGE** : 커다란 API 변경의 경우<br/>
    **!HOTFIX** : 급하게 치명적인 버그를 고쳐야 하는 경우<br/>

<br/>
<br/>

### 히스토리
- 230405 : 원격 저장소 주소를 설정할 때 `https://github.com/rowanpark/algorithm-java-study.git` 이 아니라 애초에
`https://rowanpark@github.com/rowanpark/algorithm-java-study.git` 으로 해줘야 한다. 그렇지 않으면 git push 할 때 에러(403)가 뜬다.

- 230409 : Scanner 객체 sc를 사용하고 난 후에는 sc.close() 메소드를 호출하여 객체를 닫아준다.<br/>
**Scanner 객체를 닫아주는 이유** :
    > 1. Scanner 클래스가 사용하는 시스템 리소스를 해제하고, 프로그램이 종료되어도 사용중인 리소스를 계속 점유하지 않도록 하기 위해서<br/>
    > 2. 프로그램이 메모리를 더 효율적으로 사용하게 하고, 프로그램이 종료되었을 때 자원 누수를 방지할 수 있음<br/>
    > 3. 그러므로, 가능하면 Scanner 사용 후에는 close() 메소드를 호출해주는 것이 좋음

- 250105 : 계정 이사

- Add more

- ...
