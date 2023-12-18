# regiex

# 정규표현식

# /regiex/ ==> Reqular expression의 약자

# 언제 사용하는가?
- 텍스트에서 우리가 원하는 특정한 패턴을 찾을 때(전화번호 형태의 패턴, 웹사이트 주소 형태의 패턴, 이메일 형식의 패턴을 찾을 때 등등)
- 사용자가 입력한 텍스트가 이메일이나 패스워드와 같이 특정한 패턴에 부합하는지 유효성 검사를 할때도 사용할 수 있다.
- 정규식은 문자를 검사하고자 할때 사용하는 식이다.

  # 정규식은 /로 시작하여 "나는 정규표현식"임을 나타낸다
- /우리가 찾고자하는 패턴/

- /regex/i
- i는 어떤 옵션에 따라서 검색할건지 플래그를 활용할 수 있다.

  🤓 문법

  1) Groups anf ranges
     - | : 또는
     - (): 그룹
     - []: 문자셋, 괄호 안에 있는 어떤 문자든
     - [^]:부정 문자 셋, 괄호 안의 어떤 문자가 아닐 때
     - (?:):찾지만 기억하지는 않음

라인 마다마다
![image](https://github.com/gogoringhye/regiex/assets/145514996/3aac4b6a-ebb0-45dc-9f97-35535ce28f58)


![image](https://github.com/gogoringhye/regiex/assets/145514996/29c6528e-58f8-43fc-b9a0-c7b6ab3c5870)
![image](https://github.com/gogoringhye/regiex/assets/145514996/8c5a79b3-8470-4902-8753-72ab0c2a2217)

#EX로 시작하고 중간글자가 p 또는 r가 되고 끝에는 ""로 되는 것을 찾을 수 있음 나는 r까지만 찾은거
![image](https://github.com/gogoringhye/regiex/assets/145514996/905c3145-78d0-4ff9-a74c-3b8bcb2b7248)
