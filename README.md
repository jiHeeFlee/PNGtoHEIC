# 🦁 멋쟁이사자처럼 12기 한국외대 글캠 홍보부
### 벨로그 사진 변환하기 너무 힘들어서 확장자 변환 코드 만듬

### 사용방법
1. HEIC 폴더 안에 사진 파일 넣기
2. 코드 돌아갈 pip 설치 후 가상환경?myenev 열어서 돌리기
  ```
  python.exe -m pip install --upgrade pip
  pip install Pillow
  pip install Image
  cmake 설치(터미널로 설치X. 홈페이지 들어가서 설치)
  python -m venv myenv
  .\myenv\Scripts\activate
  pip install Pillow  
  pip install pillow_heif
  ```
4. PNG 폴더 안에 변환된 사진 사용하면 됨
