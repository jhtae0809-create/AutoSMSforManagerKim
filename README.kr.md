# Twilio SMS 자동 발송기

Twilio API를 사용하여 개인화된 설문조사 안내 문자를 자동 발송하는 파이프라인이다. Penn State University 교환학생 과정 중 설문 응답 수집 업무를 효율화하기 위해 제작했다.

## 제작 배경
현지 전문가들에게 일일이 문자를 보내는 반복 작업을 줄이기 위해 개발했다. 단순 발송을 넘어 수신자의 이름과 회사명을 메시지에 포함하여 응답률을 높이고자 했다.

## 설치 및 설정
1. 필수 패키지 설치:
   ```bash
   pip install twilio python-dotenv
   ```
2. .env 파일에 Twilio 계정 정보 입력:

TWILIO_ACCOUNT_SID=발급받은_SID
TWILIO_AUTH_TOKEN=발급받은_토큰
TWILIO_NUMBER=트윌리오_번호

## 실행 방법
sms_dispatcher.py 파일의 contacts 리스트에 수신자 정보를 넣은 후 실행한다:
  
  ```Bash
  python sms_dispatcher.py
  ```

**작성자**: 정현태
