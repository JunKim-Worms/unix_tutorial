## treasurehunt_v2_kor.pl 사용법
UCSF에 계시는 Stephan J. Sanders 박사가 처음 만든 스크립트를 기반으로 준킴이 번역 초안을 맡고, 시바님이 감수해주셨습니다.
자세한 내용은 본문 열어서 확인해보세요!

0. Linux OS 설치된 컴퓨터를 준비한다. 또는 Linux OS 설치된 서버에 접속할 수 있는 ID를 준비한다.

1. git이 깔려있는지 확인합니다. 터미널 열고 타이핑 하세요.
```sh
git --version
```
만약에
```sh
Command 'git' not found, but can be installed with:

sudo apt install git
```
등등 git 설치 안 돼 있으면 시키는 대로 하시고, 버전 딱 뜨면 다음으로 넘어가시면 됩니다.

2. 터미널 열고 복사 붙여 넣기 하십쇼.
```sh
mkdir treasure && cd treasure
git clone git://github.com/JunKim-Worms/genomics-tutorial/unix_tutorial/treasurehunt_v2_kor.pl
perl treasurehunt_v2_kor.pl
mv treasurehunt_v2_kor.pl ..
```

3. 파일들이 잘 생성됐다면 이제 nano를 이용해 단서를 열고 읽어봅시다.
```sh
nano Clue01_S.txt
```

4. 문제 다 풀었는데 선물 준비 안 해놨으면 담당자 때리시면 됩니다. 저는 오지게 맞았어요...
