# llm_basic_ex
생성형 AI, API 활용실습


# 콘다 가상환경 만들기
```
# 새로운 가상환경 만들기
conda create -n llm_env python=3.10

#가상환경 활성화
conda activate llm_env

# Jupyter 노트북에서 파이썬 코드를 실행할 수 있는 파이썬 커널
pip install ipykernel

# jupyter lab에 가상환경(llm_env) 등록하기
python -m ipykernel install --user --name llm_env
```

# openai gpt모델 api 사용방법 실습
## 라이브러리 설치

```
pip install --upgrade openai 
pip install tiktoken
```


# google llm model api 사용방법
```
pip install google-genai
```

# chocolatey 설치 및 FFmpeg설치
```
Windows에서 FFmpeg 설치
Chocolatey 설치
Chocolatey가 설치되어 있지 않다면 다음 단계를 따라 설치할 수 있습니다:

    1) 관리자 권한으로 PowerShell을 엽니다.

    2) 다음 명령어를 실행하여 Chocolatey를 설치합니다:
        
URL에서 복사해서 설치
      
https://chocolatey.org/install  

  3) Chocolatey 설치가 완료되면, 다음 명령어로 FFmpeg를 설치할 수 있습니다:

choco install ffmpeg


vs-code, 터미널 모두 닫았다가 다시 시작
```
