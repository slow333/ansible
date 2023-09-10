andible test 환경 구성 관련

처음에 vmware에 5개의 vm을 구성해서 그 중하나에서 ansible coding을
수행 함 => keyboard lag 이 심해서 ubuntu에서 centos로 바꿈
(vs code를 활용 , 그냥 nano나 vim을 사용하면 큰 문제 없으나 많이 불편함)

좀 좋아지기는 했으나 여전히 답답함...
너무 많은 vm을 구성하고 그중 하나에서 편집을 진행하니 뭔가 성능에 문제가 있는 듯함

그래서 구성 변경
vm들은 순수하게 성능 수집용으로만 활용

window에 wsl을 구성하고 => wsl에서 openssh, ansible, git 등 설치

그 상태에서 vs code를 실행해서 코딩을 수행 => 쾌적함...
("wsl에서 vs code 실행하기" 로 검색하면 ms에서 설명을 잘해놨음
 windows용 vs code 설치하고 extension 설치하고 폴더 공유하고 등등
)

