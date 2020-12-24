## Install

**1. ANACONDA 설치**
- [다운로드](https://www.anaconda.com/products/individual#Downloads)
- 설치하고자 하는 OS에 맞게 선택한다.
  - MacOs | Windows (32-Bit & 64-Bit) | Linux
- Python 3.x 버전이 함께 설치된다.
- 여러가지 수학 및 과학 패키지들을 기본적으로 포함하고 있다.
- 파이썬 배포판이다.
- 설치 가이드
  - [MacOS](https://docs.anaconda.com/anaconda/install/mac-os/)
  - [Windows](https://docs.anaconda.com/anaconda/install/windows/)
- [사용자 가이드](https://docs.anaconda.com/anaconda/user-guide/)

**2. 설치 확인 및 실행**
> GUI
- Anaconda-Navigator 실행
  - JupyterNotebook
  - JupyterLab
> CLI
  ```sh
  $ jupyter notebook
  ```
> ***!!! Warning !!!***
> 실행시 열리는 터미널창은 작업하는 동안 종료하면 안 된다.
> JupyterNotebook 실행 종료하려면 터미널에서 Ctrl+C 키를 입력한다.

**3. 실습**
- JupyterNotebook 실행
- 새로운 파일(.ipynb) 생성
  - New > Python3 (기본 파일명 : Untitled.ipynb)
  - 파일명 Rename
- 예제 코드 
```python
print('Hello World!')
```