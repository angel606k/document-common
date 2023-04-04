# Linux 명령어 정리
## 기본 명령어
- 디렉토리 이동
``` bash
# cd [대상 경로]
cd /usr/local
```
- 복사
  - 대상 파일 및 디렉토리를 지정한 경로 또는 파일명으로 복사
``` bash
# cp [대상 파일 경로] [복사 경로]
# 디렉토리 복사의 경우 옵션 -R 을 추가한다
cp ./study/copy.txt ./study/copy_test.txt
```
- 이동
  - 대상 파일 및 디렉토리를 지정한 경로 또는 파일명으로 이동
  - 파일명 변경 시에도 이동 명령어로 변경함
``` bash
# mv [대상 파일 경로] [이동 경로]
# 디렉토리 이동의 경우 옵션 -R 을 추가한다
mv ./study/move.txt ./study/move_test.txt
```
- 삭제
  - 대상 파일 및 디렉토리를 삭제
``` bash
# rm [삭제 대상]
# 디렉토리 이동의 경우 옵션 -r 을 추가한다
rm ./study/delete.txt
rm -r ./study
```
