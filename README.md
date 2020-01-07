## Project :: Front-end 'Login Form' dev. For Spring Boot

### 메인 페이지

1. 아이디
2. 비번

로그인 / 비번찾기 / 회원가입

    ~/index.html



### 로그인 한 다음 페이지 (템플릿은 메인 로그인 페이지랑 비슷하게 하면 댐)

1. 사진 (고양이로 넣자)
2. 바로밑에 hi, <username>

로그아웃 / 회원정보수정


    ~/templates/main.html

### 회원가입 페이지

1. 아이디

2. 비번

3. 비번확인

4. 성별 (남, 여) 버튼으로 만들수 있으면 버튼으로 만들자 개꿀

5. 생년월일 8글자

6. 전화번호

7. 이메일 (인증번호 발송 버튼)

8. 인증번호 ***(인증번호 확인 버튼 얘 누르면 완료버튼 활성화!)***

9. 맨밑에 완료버튼

ㅇㅋ?

    ~/templates/register.html

    - 성별 checkbox 클릭 시, toggle 되도록 구현

    9. !(반드시 필요한 정보 && 인증번호) 일 때는 submit 거부 + 팝업 or slide 효과

    ps. 활성화가 '없던 것이 나타나는 효과'를 포함한다면 디자인적으로 멋있을 듯,
    하지만 인증 이후 단순 '제출 가능'을 허가한다면 상단의 정보를 바꾸어서 제출할
    수 있기에 위험. (결론은, 아무튼 submit 조건을 잘 검사하도록 구현하겠음. ㅋ)

    ps. 생각나는대로 써보면... 반드시 필요한 정보의 누락 여부, 아이디 중복 여부,
        확인 비밀번호 일치 여부 등 검사하도록.

### 비번 찾기 페이지

1. 아이디
2. 이메일 (인증번호 발송)
3. 인증번호 (인증번호 확인 버튼. 이 버튼을 누르면 밑에 애들이 활성화!)
4. 새로운 비번
5. 비번확인
6. 맨밑에 완료버튼

ㅇㅋ?

    ~/templates/forget_password.html