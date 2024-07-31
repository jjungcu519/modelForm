## POST와 token
- form 메서드 포스트로 바꿀시
- {% csrf_token %}을 추가해주세요 ~!


## 유효성 검사
- 숫자에는 숫자, 글자에는 글자 데이터, 이메일 형식 등. 전화번호도 데쉬를 넣냐 안넣느냐, 국가번호 입력방법 등등등등
- 공백 데이터는 받지 않음. 길이 몇 이상 등

## create form태그 대신 ModelForm 활용
- 앱폴더에 forms.py 생성
- 임포트, 상속, 클래스 2개 활용 (models.py와 유사)
- 사실 ModelForm 보다는 ModelInput에 가깝다.
- 장고 form에서 기본 검증을 제공하지만, 프론트적인 검증에 지나지 않음 -> 대안 필요?



-폼은 POST , submit은 GET 형태?
- else 문이 먼저 실행되는 마법 (흐름이해)