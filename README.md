# Git-practice
 Learning Git & Github


### git을 사용하려면
* git 설치
* console창에서 ```git -version``` 입력 -> 현재 version 알 수 있음
> github desktop은 windows에서 64bytes에서만 사용 가능함. github desktop을 다운받으면 git도 같이 다운 받게 됨

### git
* distributed version control system
* 모든 파일들을 트래킹하여 변경사항을 확인하는 것. 
* 누가, 언제, 어느 곳을 수정했는지 알 수 있음. 
* binary code로 읽기 때문에 text, image, excel, 음악파일 등 모든 것을 읽을 수 있음.

### github
* git 파일을 올려서 변경사항을 볼 수 있는 곳. 파일을 업로드하는 공간.
* git provider : github, bitbucket, gitlab 

## Basic Git Concepts
### repository
*  git이 작동하는 폴더

### commit
* commit : record. point in time. git에 어떤 변경사항이 있을 때 그 시간대의 record를 세팅하는 것.
* github desktop의 경우 git repository를 만들 때 git파일이랑 같이 생성하는데 그 때 initial commit 이 함께 되어 있음. 
* commit을 통해 변화되는 과정 history를 알 수 있음

### Areas
* Areas : git은 3가지 area를 가지고 있음
 - working area(working directory) : working하고 있는 폴더
 - staging area(commit area) : 한 파일이 commit되면 기본적으로 저장되어지는 폴더. 어떤 파일들이 commit 될건지, 어떤 것들이 다시 추가될 것인지 선택하는 폴더.
 - repository area : 파일이 commit 되고 수정사항의 스냅샷을 가지고 있는 것. 수정사항, 시간, 누가 수정했는지 등이 저장되어 있음.
