# Bash 환경 사용 방법

## 기본 명령어

* 파일 생성
```Bash
touch 파일이름.확장자
```

* 폴더 생성
   * 무조건 폴더 생성 명령어
   * 이름 뒤에 /가 붙으면 반드시 폴더(=디렉토리)
```Bash
mkdir 폴더명
```
* ls -a : 현재 difectory의 파일 및 폴더 확인 
```Bash
ls
ls -a #모든 숨겨진 폴더 포함해서 보기
```

* cd : directory로 이동
   * 현재 위치를 기준으로 이동 
   * 상위 폴더로 이동하기 위해서는 ..을 이용
      * ex) cd .. 입력하면 한 번 위로, cd ../.. 입력하면 두 번 위로


* start : 폴더/파일을 열기

* code : (vscode 설치)

* rm : 파일삭제(디렉토리 삭제는 -r옵션을 추가 사용)
```Bash
 rm -r zxc.txt 를 입력하면 폴더 삭제
 강제 삭제는 f까지 붙여서 사용
 ex) rm -rf zxc.txt
 ```