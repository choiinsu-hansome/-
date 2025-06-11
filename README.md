import turtle#여기서 부터
t = turtle.Turtle()
t.shape("turtle")#여기 까지 거북이 프로그램 실행 명령어
t.fillcolor("blue")#색 채우기
t.begin_fill()#채우기 시작
t.circle(100)#원(반지름100만큼)
t.end_fill()#끝
t.forward(100)#앞으로 100만큼
t.fillcolor("orange")
t.begin_fill()
t.circle(120)
t.end_fill()
t.forward(100)
t.fillcolor("black")
t.begin_fill()
t.circle(140)
t.end_fill()
t.forward(100)
t.fillcolor("red")
t.begin_fill()
t.circle(160)
t.end_fill()
t.fillcolor("brown")#색 채우는 삼각형 그리기 
t.begin_fill()
t.left(180)
t.forward(100)
t.left(120)
t.forward(100)
t.left(120)
t.forward(100)
t.left(120)
t.end_fill()
t.up()#범위 벗어나기
t.goto(-200,0)
t.down()
t.fillcolor("red")
t.begin_fill()
t.forward(300)#자동차 몸체
t.left(90)
t.forward(100)
t.left(90)
t.forward(300)
t.left(90)
t.forward(100)
t.end_fill()
t.up()#바퀴 이동
t.goto(-400,-100)
t.down()
t.fillcolor("yellow")
t.begin_fill()
t.circle(50)#바퀴 원
t.end_fill()
t.up()#바퀴 이동
t.goto(-200,-100)
t.down()
t.fillcolor("yellow")
t.begin_fill()
t.circle(50)#바퀴 원
t.end_fill()
#집 만들기 실습

#import turtle
#t = turtle.Turtle()
#t.shape("turtle")

#size = int(input("집의 크기는 얼마로 할까요?"))

#t.left(60)
#t.forward(size)
#t.right(120)
#t.forward(size)
#t.right(30)
#t.forward(size)
#t.right(90)
#t.forward(size)
#t.right(90)
#t.forward(size)
#t.right(90)
#t.forward(size)

#radius라는 입력값 만들어서 수정할수 있는 프로그램 

#f = 50
#radius = 100
#t.circle(radius)
#t.fd(f)
#t.circle(radius)
#t.fd(f)
#t.circle(radius)

#x,y,이름 input 사용하여 문장 만들기

#x = int(input("첫 번째 값을 입력해주세요:"))
#y = int(input("두 번째 값을 입력해주세요:"))
#print(x,"와", y,"의 합은",x+y, "입니다")

#name = input("이름을 입력하세요:")
#print(name," 씨, 안녕하세요?")
#print("파이썬에 오신것을 환영합니다.")
#x = int(input("첫 번째 값을 입력해주세요:"))
#y = int(input("두 번째 값을 입력해주세요:"))
#sum = x+y
#print(x,"과", y,"의 합은",sum, "입니다.")

#야구 경기 input , print 실습

#stadium = input("경기장은 어디입니까?")
#winner = input("이긴팀은 어디입니까")
#loser = input("진팀은 어디입니까?")
#vip = input("우수선수는 누구입니까?")
#score = input("스코어는 몇대몇입니까?")

#print("")
#print("====================================")
#print("오늘",stadium"에서 야구 경기가 열렸습니다.")
#print(winner,"과",loser,"은 치열한 공방전을 펼쳤습니다.")
#print(vip,"이 맹활약을 하엿습니다.")
#print("결국",winner,"가",loser,"을",score,"로 이겼습니다.")
#print("====================================")
#p=int(input("분자를 입력하시오:"))
#q=int(input("분모를 입력하시오:"))
#print("나눗셈의 몫=",p // q)
#print("나눗셈의 나머지=",p % q)
#input()


#a=int(input("숫자를 입력하시오:"))
#b=int(input("두번째 숫자를 입력하시오:"))
#print("덧셈은",a+b)
#print("뺄셈은",a-b)
#print("나눗셈은",a//b)
#print("곱셈은",a*b)


#sec = 1000
#min = 1000 // 60
#remainder = 1000 % 60
#print(min , "분" , remainder , "초")

#안됨 보류
#import turtle
#t=turtle.Turtle()
#t.shape("turtle")
#n = int(input("몇각형을 그리시겠어요?(3*6):"))


#for i in range(n)
#t.forward(100)
#t.left(360//n)


#카페 마감 정산
#print("아메리카노 한잔 2000원")
#print("라떼 한잔 3000원")
#print("카푸치노 한잔 3500원")
#ame_p = 2000
#lat_p = 3000
#cap_p = 3500
#ame = int(input("아메리카노의 판매 개수를 입력해주세요:"))
#lat = int(input("라데의 판매 개수를 입력해주세요:"))
#cap = int(input("카푸치노의 개수를 입력해주세요:"))
#print("아메리카노의 매출은" , ame * ame_p ,"원 입니다.")
#print("라떼의 매출은", lat * lat_p , "원 입니다.")
#print("카푸체노의 매출은" , cap * cap_p , "원 입니다.")
#print("총합 매출은", ame * ame_p + lat * lat_p + cap * cap_p , "원 입니다")


#화씨를 섭씨온도로 바꾸는 식
#ftemp = int(input("화씨온도:"))
#ctemp = (ftemp - 32.0) * 5.0/9.0
#print("섭씨온도:",ctemp)


#섭씨를 화씨온도로 바꾸는 식
#ctemp = int(input("섭씨온도:"))
#ftemp = (ftemp * 9.0/5.0) + 32
#print("화씨온도",ftemp)


#원의 면적 구하기
#r = int(input("원의 반지름의 길이를 입력해주세요:"))
#area = r * r * 3.14
#print("원의 면적은", area , "입니다.")


#사각형의 면적
#u = int(input("사각형의 밑변의 길이를 입력하십쇼:"))
#h = int(input("사각형의 높이의 길이를 입력하십쇼:"))
#n = u * h
#print("사각형의 면적은",n,"입니다.")


#돈 계산
#money = int(input("투입한 돈:"))
#price = int(input("물건값:"))

#change = money - price
#print("거스름돈:",change)
#coin500s = change // 500
#change = change % 500
#coin100s = change // 100
#change = change % 100
#coin50s = change // 50
#change = change % 50
#coin10s = change // 10
#change = change % 10

#print("500원 동전의 개수:" ,coin500s)
#print("100원 동전의 개수:", coin100s)
#print("50원 동전의 개수:",coin50s)
#print("10원의 동전의 개수:",coin10s)


#지수 계산(미완)
#money = 10000000
#rate = 0.06
#n = 5
#print("")


#
#a = float(input("a:"))
#b = float(input("b:"))
#c = float(input("c:"))


#r = b ** 2 - 4 * a * c

#print("2개의 실근이 있는 경우만 계산할 수 있습니다.")
#x1 = (((-b)+ r ** 0.5)/(2 * a))
#x2 = (((-b)- r ** 0/5)/(2 * a))
#print("2개의 실근:", x1 , x2)


#bmi값 구하기
#w = float(input("몸무계를 kg단위로 입력하시오:"))
#h = float(input("키를 미터단위로 입력하시오:"))
#BMI = (w / (h ** 2))
#print("당신의 BMI는",BMI,"입니다.")


#test
#점수 = int(input("당신의 점수를 입력해주세요:"))
#점수 < 50
#if 
#수학에서 가까운 수 인가 테스트 (거의 버그 테스트임)
#import math
#math.isclose(3.14,3.15)


#평균값 계산기
#x = int(input("첫 번째 수를 입력하시오."))
#y = int(input("두 번째 수를 입력하시오."))
#z = int(input("세 번째 수를 입력하시오."))
#v = (x + y + z) / 3 #x+y+z에 괄호를 넣어줌으로써 계산이 꼬이지 않게 도와줌
#print("평균 = ",v)


#수학 문제 만들기
#ans = int(input("2 + 5 = ")) # 질문을 만들고 빈칸을 넣을수 있게 명령어(input)를 넣음
#print(ans==2 + 5) # 답변을 정답과 비교해서true 혹은 false로 나올수 있게 명령(같다 : ==)
#ans = int(input("7 - 6 = "))
#print(ans==7 - 6)
#ans = int(input("2 ** 3 = "))
#print(ans==2 ** 3)
#ans = int(input("4 / 2 = "))
#print(ans==4 / 2)

#숫자 랜덤 지정 문제
#import random
#x = random.randint(0,10)
#y = random.randint(0,10)
#s = str(x) + "+" + str(y) + "="
#ans = int(input(s))
#print(ans==x + y) #여기 까지임 아래는 테스트
#x = random.randint(0,10)
#y = random.randint(0,10)
#s = str(x) + "-" + str(y) + "="
#ans = int(input(s))
#print(ans==x - y)
#x = random.randint(0,10)
#y = random.randint(0,10)
#s = str(x) + "*" + str(y) + "="
#ans = int(input(s))
#print(ans==x * y)
#x = random.randint(0,10)
#y = random.randint(0,10)
#s = str(x) + "/" + str(y) + "="
#ans = int(input(s))
#print(ans==x / y)

import math

#원의 둘레 계산
radius = 3
circ = 2 * math.pi * radius
print("원의 둘레="circ)

#팩토리얼 계산
print("7!=",math.factorial(7))

#2개의 실수 비슷한지 비교
print("6.999999999 와 7의 비교 =", math.isclose(6.999999999))

#로그 계산
print("log(3.4)=", math.log(3.4))

#제곱근 계산
print("4의 제곱근 =", math.sqrt(4.0))
#작은 따옴표 안에 큰 따옴표 넣거나 큰 따옴표 안에 작은 따옴표 넣으면 출력가능
#message('철수가"안녕"이라고 말했습니다.')


#""넣으면 문자열 되서 "100"+"200"하면 100200 됨


#type()하고 괄호안에 무언갈 넣으면 <class>하고 뭐인지 알려줌 ex)문자열 정수 등등
#type("hello World")

#type(3.2)


#int로 바꿀수 있음
#t = input("정수를 입력하시오:")
#x = int(t)

#t = input("정수를 입력하시오: ")
#y = int(t)

#print(x+y)


#원래 문자열 사이에서는 숫자열을 못쓰는데 str을 넣으면 숫자열을 사용할수 있다.
#print('나는 현재' + str(21) + '살이다.')

#print()


#str과 len을 이용한 연습문제 + \n 사용법(\n은 출력할때 한줄 내려줌)
#print('안녕하세요?')
#name = input("이름이 어떻게 되시나요?")
#print('\n만나서 반갑습니다.' + name + "씨")
#print('이름의 길이는 다음과 같군요:' + str(len(name)))

#age = int(input("\n나이가 어떻게 되나요? : "))
#print("내년이면"+str(age+1)+"이 되시는군요.")

#hab = input('\n취미가 있으신가요?')
#print('아 ' + hab + '말하시는건가요? 저도 굉장히 좋아하는 것 중 하나입니다 :)')
#문자 두개를 붙히려면 +연산자 사용하면 된다.


#"="*50
#=를 50번 쳐줌

#len("hello World")
#치면 문자열의 길이를 알려줌 = 11

#'hello' in "hello world"
#hello world 안에 hello 있는지 물어봄 결과값 = true



#text = "hello world"
#print(text.count('o'))


#text.strip()

#text.lower()
#"hello world"


#대괄호를 쓰면 ' 나 " 안에도 명사를 불러올수 있다.
#price = 10000
#print(f'상품의 가격은 {price} 원 입니다.')


#()안에 f 넣기 와 대괄호 사용 편
#product = "coffee"
#count = 3
#price = 10000
#print(f"상품 {product} {count} 개의 가격은 {count *price}원 입니다.")


#(s[])하면 (띄어쓰기 포함) n:m n의 초과부터 m의 이하까지 출력한다.
#s = "monty python"
#print(s[6:10])


#\n = 다음줄로 보냄 ex) (안녕\n하세요) = 안녕(다음줄)하세요
#\t = tap만큼의 길이가 생김
#\\ = \다음의 문자를 출력해줌 아래꺼 다 같음
#\" = 
#\' = 

#print("\"안녕 하세요\"")
#위에 같이 치면 "안녕 하세요" 가 출력됨 ("출력할수 있음)


#첫 글자만 출력하는 프로그램 만들기
#x = input("이름의 첫번째 글자를 입력하시오 :")
#y = input("이름의 두번째 글자를 입력하시오 :")
#z = input("이름의 셋번째 글자를 입력하시오 :")

#initial = x[0] + y[0] + z[0]
#print("\n영어 이니셜은" + initial +"입니다.")



#도전 문제
#x = input("이름의 첫번째 글자를 입력하시오 :")
#y = input("이름의 두번째 글자를 입력하시오 :")
#z = input("이름의 셋번째 글자를 입력하시오 :")

#initial = y[0] + z[0] + x[0]
#print("\n영어 이니셜은" + initial +"입니다.")


#tts로 음성 파일 만들기 참고)이거하기전에 명령 프롬프트에서 파일 만들어야 함 pip install gtts
#from gtts import gTTS
#import os
#text="안녕하세요, 여러분. 파이썬은 재미있습니다."
#tts = gTTS(text = text, lang = 'ko')
#tts.save("ttt.mp3")
#os.system("ttt.mp3")


#문자열 문제 만들기
#s = input("세상에서 가장 쉬운 프로그래밍 언어는? ")
#print(s=="파이썬")
#s = input("파이썬에서 제곱 연산자는? ")
#print(s=="**")
#s = input("프로그래밍 언어에서 텍스트를 무엇이라고 부르는가? ")
#print(s=="문자열")
#s = input("\를 출력하려면 어떻게 해야할까요?")
#print(s=="\\")
#s = input("문자열 안에 숫자열을 사용하려면 문장 사이에 무엇을 넣어야할까요?")
#print(s=="str")
#성적에 따른 합 불합 분류기
#sc = int(input("성적을 입력하시오: "))
#if sc >= 60:
#       print("합격입니다. ")
#else:
#       print("불합격입니다.")


#홀짝 분류기
#num = int(input("정수를 입력하시오: "))

#if num % 2 == 0:
#    print("짝수입니다.")
#else:
#    print("홀수입니다. ")


#성적에 따른 합 불합 분류기 + 장학금 받을수 있는지 확인
#sc = int(input("성적을 입력하시오: "))
#if sc >= 60:
#    print("합격입니다. ")
#if sc >= 85:
#    print("장학금을 받을수 있습니다. ")
#else:
#    print("불합격입니다.")


#거북이한테 명령, 값을 줌으로써 거북이 위치 바꾸며 출력
#import turtle
#t = turtle.Turtle()
#t.shape("turtle")

#t.penup()
#t.goto(100,100)
#t.write("거북이가 여기로 오면 양수입니다.")
#t.goto(100,0)
#t.write("거북이가 여기로 오면 0입니다.")
#t.goto(100,-100)
#t.write("거북이가 여기로 오면 음수입니다.")

#t.goto(0,0)
#t.pendown()
#s = turtle.textinput("","숫자를 입력하시오: ")
#n= int(s)

#if n > 0:
    #t.goto(100,100)
#if n == 0:
    #t.goto(100,0)
#if n < 0:
    #t.goto(100,-100)
#turtle.done()


#나이 입력 받아 영화관 적용 (응용으로 안된다고 하면 나이에 맞는 영화 추천+여기에 더 심화로 들어가면 영화 목록 list로 등록한담에 해야할듯.)
#print("안녕히세요? 민듀 영화관입니다.")
#old = int(input("나이를 입력하시오. :"))
#if old >= 19:
#    print("이 영화 시청이 가능합니다.")
#    print("이 영화 가격은 1만 5천원 입니다. ")
#else:
#    print("이 영화는 시청이 불가합니다. ")
#    agr = input("다른 영화를 추천해드릴까요?:")
#    if agr == "네":
#        print(old,"세가 시청할수 있는 영화를 추천해드릴게요.")
#    else:
#        print("안녕히가세요.")


#ag = int(input("나이를 입력하시오: "))
#h = int(input("키를 입력하시오: "))

#if (ag > 15) and (h >= 150):
    #print("기구를 탈 수 있습니다. ")
#else:
    #print("기구를 탈 수 없습니다. ")


#거북이 입력값 만들어서 명령 내리기 (while문)
#import turtle
#t = turtle.Turtle()
#t.shape("turtle")

#t.width(3)

#t.shapesize(3,3)

#while True:
#    command = input("명령을 입력하시오:")
#    if command == "l":
#        t.left(90)
#        t.forward(100)
#    if command == "r":
#        t.right(90)
#        t.forward(100)
#turtle.done()


#윤년 계산(왜 인지 모르게 안됨)
#year = int(input("연도를 입력하시오:"))

#if((year % 4 == 0 and year % 100 !=0) or year % 400 == 0):
#    print(year,"년은 윤년입니다.")
#else:
#    print(year, "년은 윤년이 아닙니다.")


#
#import random

#print("동전 던지기 게임을 시작합니다.")
#coin = random.randrange(2)

#if coin == 0:
#    print("앞면입니다.")
#else:
#    print("뒷면입니다.")
#print("게임이 종료되었습니다.")


#
#import random
#print("주사위 던지기 게임을 시작합니다.")
#coin = random.randrange(6)

#if coin == 0:
#    print("1면 주사위 당첨입니다.")
#if coin == 1:
#    print("2면 주사위 당첨입니다.")
#if coin == 2:
#    print("3면 주사위 당첨입니다.")
#if coin == 3:
#    print("4면 주사위 당첨입니다.")
#if coin == 4:
#    print("5면 주사위 당첨입니다.")
#if coin == 5:
#    print("6면 주사위 당첨입니다.")


#
#import turtle
#import random

#screen = turtle.Screen()
#image1 = "front.gif"
#image2 = "back.gif"
#screen.add
#아 왜 넘기심


#elif 사용법 -> if를 계속 쓰는것이 아닌 반복적인 문장에서는 if 가 아니면 elif 로 출력됨 마무리 할때는 else 사용
#num = int(input("정수를 입력하시오:"))

#if num > 0:
#    print("양수입니다.")
#elif num == 0:
#    print("0입니다.")
#else:
#    print("음수입니다.")


#과제
sco = int(input("점수를 입력해주십시오:"))

if sco >= 90:
    print("A학점입니다.")
elif sco >= 80:
    print("B학점입니다.")
elif sco >= 70:
    print("C학점입니다.")
elif sco >= 60:
    print("D학점입니다.")
else sco >= 50:
    print("F학점입니다.")
    print("공부를 더 하셔야겠네요.")
#기본 텍스트
#import random
#time = random.randint(1,24)
#sunny = random.choice([True,False])


#랜덤 시간 + true,false로 나눠서 화창 or 화창하지 않다 랜덤시킴
#import random
#time = random.randint(1,24)

#print("좋은 아침입니다. 지금 시각은"+str(time)+"시 입니다.")
#sunny = random.choice([True,False])

#if sunny:
#    print("현재 날씨가 화창합니다.")
#else:
#    print("현재 날씨가 화창하지 않습니다.")

#종달새가 노래할 것인지
#if time >= 6 and time < 9 and sunny:
#    print("종달새가 노래를 합니다.")
#else:
#    print("종달새가 노래를 하지 않습니다.")


#응용
#if ((time >= 6 and time < 9) or (time >= 14 and time < 16)) and sunny:
#    print("종달새가 노래를 합니다.")
#else:
#    print("종달새가 노래를 하지 않습니다.")



#if 안에 if 넣기
#num = int(input("정수를 입력하시오:"))

#if num >= 0:
#    if num == 0:
#        print("0입니다.")
#    else:
#        print("양수입니다.")
#else:
#    print("정수입니다.")


#and 사용해서 아이디 비번 로그인
#id = "wlsgkr3392"
#pw = "wlsgkr1224"
#inid = input("아이디를 입력하시오:")

#inps = input("비밀번호를 입력하시오:")

#if (inps == pw) and (inid == id):
#    print("환영합니다")
#else:
#    print("아이디와 비번이 맞는지 확인해주십시오")

#if 두번 사용해서 아이디 비번 로그인

#id = "wlsgkrid"
#pw = "wlsgkrpw"
#inid = input("아이디를 입력하시오:")
#if id == inid:
#    inps = input("비밀번호를 입력하시오:")
#    if inps == pw:
#        print("환영합니다")
#    else:
#        print("비밀번호가 틀렸습니다.")
#else:
#    print("아이디가 틀렸습니다.")
#1~5까지 더하기
#sum = 0
#for i in[1,2,3,4,5]:
#    print(f"{i}를 더하는 중")
#    sum += i
#print("합계는=",sum)


#range 사용해서 0부터 지정숫자 까지 더하기 만듦
#for i in range(1,6,1):
#    print("")


#
#import time
#for i in range(10,0,-1):
#    print(i)
#    time.sleep(1)
#print("발사!")


#응용
#import time
#for i in range(10,8,-1):
#    print(i)
#    time.sleep(2)
#print("1\n0\n 발사!")


#
#import time

#while True:

#    current_time = time.localtime()
   
#    hour = current_time.tm_hour
#    minute = current_time.tm_min
#    second = current_time.tm_sec

#    print("{:02d}:{:02d}:{:02d}".format(hour, minute, second))

#    time.sleep(1)


#
#import time
#import winsound

#seconds = int(input("초단위의 시간을 입력하시오:"))

#for i in range(seconds,0,-1):
#    print(f"{i}초 남았습니다.")
#    time.sleep(1)
#winsound.Beep(2000,3000)


#
#dan = int(input("원하는 단은: "))

#for i in range(1,10,1):
#    print(f"{dan}*{i}={dan*i}")



#도전문제
#for dan in range(1,10,1):
#    for i in range(1,10,1):
#        print(f"{dan}*{i}={dan*i}")
#    print()


#
import turtle
import random

t = turtle.Turtle()
t.shape("turtle")

for i in range(30):

    length = random.randint(1,100)
    t.fd(length)

    angle = random.randint(-180,180)
    t.right(angle)

turtle.done()
#import random

#while True:
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    print(x,"+",y,"=",end="")
#    answer = int(input())
#    if answer == x+y:
#        print("잘했어요!!")
#    else:
#        print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break
   

#덧셈 뺄셈 두개 랜덤 문제제출
#import random

#while True:
#    q = random.randint(0,1)
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    if q == 1:
#        print(x,"-",y,"=",end="")
#        answer = int(input())
#        if answer == x-y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    else:
#        print(x,"+",y,"=",end="")
#        answer = int(input())
#        if answer == x+y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break


#모든 경우의 수 list 계산
#breads = ["호밀빵","위트","화이트"]
#meats = ["마트볼","쏘시지","닭가슴살"]
#vegis = ["양상추","토마토","오이"]
#sauces = ["마요네즈","허니 머스타드","칠리"]

#for b in breads:
#    for m in meats:
#        for v in vegis:
#            for s in sauces:
#                print(b+"+"+m+"+"+v+"+"+s)


#
#while True:
#    light = input("신호등 색상을 입력하시오")
#    if light == 'blue':
#        break
#print("전진")


#
#import random
#import sys

#user_pass = input("ㅠㅐ스워드를 입력하시오:")
#password = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

#for letter1 in password:
#    for letter2 in password:
#        for letter3 in password:
#            guess = letter1+letter2+letter3
#            print(guess)
#            if guess == user_pass:
#                print("당신의패스워드는"+guess)
#                sys.exit()
               

#터틀 랜덤위치 지정 그림그리기
#import turtle
#import random
#t = turtle.Turtle()
#t.shape("turtle")
#t.speed(0)
#
#for i in range(30): # 30번 반복
#    t.fillcolor(random.random(),random.random(),random.random()) # 랜덤 색상 지정
#    t.up()
#    t.goto(random.randint(-100,100),random.randint(-100,100)) # 랜덤 위치 지정
#    t.down
#    length = random.randint(10,100) # 랜덤 길이 지정
#    height = random.randint(10,100) # 랜덤 넓이 지정
#    t.begin_fill()
#    for _ in range(2): # 사각형 그리기
#        t.forward(length)
#        t.right(90)
#        t.fd(height)
#        t.right(90)
#    t.end_fill()
#turtle.done()
#import random

#while True:
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    print(x,"+",y,"=",end="")
#    answer = int(input())
#    if answer == x+y:
#        print("잘했어요!!")
#    else:
#        print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break
   

#덧셈 뺄셈 두개 랜덤 문제제출
#import random

#while True:
#    q = random.randint(0,1)
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    if q == 1:
#        print(x,"-",y,"=",end="")
#        answer = int(input())
#        if answer == x-y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    else:
#        print(x,"+",y,"=",end="")
#        answer = int(input())
#        if answer == x+y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break


#모든 경우의 수 list 계산
#breads = ["호밀빵","위트","화이트"]
#meats = ["마트볼","쏘시지","닭가슴살"]
#vegis = ["양상추","토마토","오이"]
#sauces = ["마요네즈","허니 머스타드","칠리"]

#for b in breads:
#    for m in meats:
#        for v in vegis:
#            for s in sauces:
#                print(b+"+"+m+"+"+v+"+"+s)


#
#while True:
#    light = input("신호등 색상을 입력하시오")
#    if light == 'blue':
#        break
#print("전진")


#
#import random
#import sys

#user_pass = input("ㅠㅐ스워드를 입력하시오:")
#password = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

#for letter1 in password:
#    for letter2 in password:
#        for letter3 in password:
#            guess = letter1+letter2+letter3
#            print(guess)
#            if guess == user_pass:
#                print("당신의패스워드는"+guess)
#                sys.exit()
               

#터틀 랜덤위치 지정 그림그리기
#import turtle
#import random
#t = turtle.Turtle()
#t.shape("turtle")
#t.speed(0)
#
#for i in range(30): # 30번 반복
#    t.fillcolor(random.random(),random.random(),random.random()) # 랜덤 색상 지정
#    t.up()
#    t.goto(random.randint(-100,100),random.randint(-100,100)) # 랜덤 위치 지정
#    t.down
#    length = random.randint(10,100) # 랜덤 길이 지정
#    height = random.randint(10,100) # 랜덤 넓이 지정
#    t.begin_fill()
#    for _ in range(2): # 사각형 그리기
#        t.forward(length)
#        t.right(90)
#        t.fd(height)
#        t.right(90)
#    t.end_fill()
#turtle.done()#import random

#while True:
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    print(x,"+",y,"=",end="")
#    answer = int(input())
#    if answer == x+y:
#        print("잘했어요!!")
#    else:
#        print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break
   

#덧셈 뺄셈 두개 랜덤 문제제출
#import random

#while True:
#    q = random.randint(0,1)
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    if q == 1:
#        print(x,"-",y,"=",end="")
#        answer = int(input())
#        if answer == x-y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    else:
#        print(x,"+",y,"=",end="")
#        answer = int(input())
#        if answer == x+y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break


#모든 경우의 수 list 계산
#breads = ["호밀빵","위트","화이트"]
#meats = ["마트볼","쏘시지","닭가슴살"]
#vegis = ["양상추","토마토","오이"]
#sauces = ["마요네즈","허니 머스타드","칠리"]

#for b in breads:
#    for m in meats:
#        for v in vegis:
#            for s in sauces:
#                print(b+"+"+m+"+"+v+"+"+s)


#
#while True:
#    light = input("신호등 색상을 입력하시오")
#    if light == 'blue':
#        break
#print("전진")


#
#import random
#import sys

#user_pass = input("ㅠㅐ스워드를 입력하시오:")
#password = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

#for letter1 in password:
#    for letter2 in password:
#        for letter3 in password:
#            guess = letter1+letter2+letter3
#            print(guess)
#            if guess == user_pass:
#                print("당신의패스워드는"+guess)
#                sys.exit()
               

#터틀 랜덤위치 지정 그림그리기
#import turtle
#import random
#t = turtle.Turtle()
#t.shape("turtle")
#t.speed(0)
#
#for i in range(30): # 30번 반복
#    t.fillcolor(random.random(),random.random(),random.random()) # 랜덤 색상 지정
#    t.up()
#    t.goto(random.randint(-100,100),random.randint(-100,100)) # 랜덤 위치 지정
#    t.down
#    length = random.randint(10,100) # 랜덤 길이 지정
#    height = random.randint(10,100) # 랜덤 넓이 지정
#    t.begin_fill()
#    for _ in range(2): # 사각형 그리기
#        t.forward(length)
#        t.right(90)
#        t.fd(height)
#        t.right(90)
#    t.end_fill()
#turtle.done()#import random

#while True:
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    print(x,"+",y,"=",end="")
#    answer = int(input())
#    if answer == x+y:
#        print("잘했어요!!")
#    else:
#        print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break
   

#덧셈 뺄셈 두개 랜덤 문제제출
#import random

#while True:
#    q = random.randint(0,1)
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    if q == 1:
#        print(x,"-",y,"=",end="")
#        answer = int(input())
#        if answer == x-y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    else:
#        print(x,"+",y,"=",end="")
#        answer = int(input())
#        if answer == x+y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break


#모든 경우의 수 list 계산
#breads = ["호밀빵","위트","화이트"]
#meats = ["마트볼","쏘시지","닭가슴살"]
#vegis = ["양상추","토마토","오이"]
#sauces = ["마요네즈","허니 머스타드","칠리"]

#for b in breads:
#    for m in meats:
#        for v in vegis:
#            for s in sauces:
#                print(b+"+"+m+"+"+v+"+"+s)


#
#while True:
#    light = input("신호등 색상을 입력하시오")
#    if light == 'blue':
#        break
#print("전진")


#
#import random
#import sys

#user_pass = input("ㅠㅐ스워드를 입력하시오:")
#password = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

#for letter1 in password:
#    for letter2 in password:
#        for letter3 in password:
#            guess = letter1+letter2+letter3
#            print(guess)
#            if guess == user_pass:
#                print("당신의패스워드는"+guess)
#                sys.exit()
               

#터틀 랜덤위치 지정 그림그리기
#import turtle
#import random
#t = turtle.Turtle()
#t.shape("turtle")
#t.speed(0)
#
#for i in range(30): # 30번 반복
#    t.fillcolor(random.random(),random.random(),random.random()) # 랜덤 색상 지정
#    t.up()
#    t.goto(random.randint(-100,100),random.randint(-100,100)) # 랜덤 위치 지정
#    t.down
#    length = random.randint(10,100) # 랜덤 길이 지정
#    height = random.randint(10,100) # 랜덤 넓이 지정
#    t.begin_fill()
#    for _ in range(2): # 사각형 그리기
#        t.forward(length)
#        t.right(90)
#        t.fd(height)
#        t.right(90)
#    t.end_fill()
#turtle.done
#import random

#while True:
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    print(x,"+",y,"=",end="")
#    answer = int(input())
#    if answer == x+y:
#        print("잘했어요!!")
#    else:
#        print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break
   

#덧셈 뺄셈 두개 랜덤 문제제출
#import random

#while True:
#    q = random.randint(0,1)
#    x = random.randint(1,100)
#    y = random.randint(1,100)
#    if q == 1:
#        print(x,"-",y,"=",end="")
#        answer = int(input())
#        if answer == x-y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    else:
#        print(x,"+",y,"=",end="")
#        answer = int(input())
#        if answer == x+y:
#            print("잘했어요!!")
#        else:
#            print("다음번에는 더 잘할 수 있죠?")
#    stop = input("")
#    if stop == 'q':
#        break


#모든 경우의 수 list 계산
#breads = ["호밀빵","위트","화이트"]
#meats = ["마트볼","쏘시지","닭가슴살"]
#vegis = ["양상추","토마토","오이"]
#sauces = ["마요네즈","허니 머스타드","칠리"]

#for b in breads:
#    for m in meats:
#        for v in vegis:
#            for s in sauces:
#                print(b+"+"+m+"+"+v+"+"+s)


#
#while True:
#    light = input("신호등 색상을 입력하시오")
#    if light == 'blue':
#        break
#print("전진")


#
#import random
#import sys

#user_pass = input("ㅠㅐ스워드를 입력하시오:")
#password = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

#for letter1 in password:
#    for letter2 in password:
#        for letter3 in password:
#            guess = letter1+letter2+letter3
#            print(guess)
#            if guess == user_pass:
#                print("당신의패스워드는"+guess)
#                sys.exit()
               

#터틀 랜덤위치 지정 그림그리기
#import turtle
#import random
#t = turtle.Turtle()
#t.shape("turtle")
#t.speed(0)
#
#for i in range(30): # 30번 반복
#    t.fillcolor(random.random(),random.random(),random.random()) # 랜덤 색상 지정
#    t.up()
#    t.goto(random.randint(-100,100),random.randint(-100,100)) # 랜덤 위치 지정
#    t.down
#    length = random.randint(10,100) # 랜덤 길이 지정
#    height = random.randint(10,100) # 랜덤 넓이 지정
#    t.begin_fill()
#    for _ in range(2): # 사각형 그리기
#        t.forward(length)
#        t.right(90)
#        t.fd(height)
#        t.right(90)
#    t.end_fill()
#turtle.done()
#단어 찾기
#english_dict = {}

#english_dict['one'] = '하나'
#english_dict['two'] = '둘'
#english_dict['three'] = '셋'

#while True:
#    word = input("단어를 입력하시오(종료는 q):")
#    if word == "q":
#        break
#    print(english_dict[word])


#
#english_dict = {}

#english_dict['one'] = '하나'
#english_dict['two'] = '둘'
#english_dict['three'] = '셋'

#while True:
#    word = input("단어를 입력하시오(종료는 q):")
#    if word not in english_dict or word == "q":
#        break
#    print(english_dict[word])


#딕셔너리에 넣는 문장
#mydict = {}

#while True:
#    date = input("날짜를 입력하세요:")
#    if date == "q":
#        break
#    job = input("일정을 입력하시오:")
#    if date not in mydict:
#        mydict[date]=job
#    else:
#        print("오류입니다")
#print(mydict)


#
#alist = []
#sum = 0

#for i in range(5):
#    i = int(input("정수를 입력하시오:"))
#    alist.append(i)

#for i in alist:
#    sum += i
#avg = sum/len(alist)
#print("평균=",avg)


#
#alist = []
#sum = 0

#for i in range(5):
#    i = int(input("정수를 입력하시오:"))
#    alist.append(i)

#s = sum(alist)
#print("총점=",s)


#
import random
counters = [0,0,0,0,0,0]

for i in range(1000):
    value = random.randint(0,5)
    counters[value]=counters[value] + 1

for i in range(6):
    print("주사위가",i+1,"인 경우는",counters[i],"번")
#화면에 클릭할수 있는 버튼띄움(버튼에 글자 넣을수 있)
#from tkinter import*
#window = Tk()

#button = Button(window, text="클릭하세요!")
#button.pack()

#window.mainloop()


#버튼칸이랑 빈칸 만들수 있음(아직 단계에서는 계산되지않음)
#from tkinter import*

#window = Tk()

#l1 = Label(window, text="화씨")
#l2 = Label(window, text="섭씨")
#l1.pack()
#l2.pack()

#e1 = Entry(window)
#e2 = Entry(window)
#e1.pack()
#e2.pack()

#b1 = Button(window, text="화씨 -> 섭씨")
#b2 = Button(window, text="섭씨 -> 화씨")
#b1.pack()
#b2.pack()

#window.mainloop()


#grid통해서 행과 열 나누어
#from tkinter import*

#window = Tk()

#l1 = Label(window, text="화씨")
#l2 = Label(window, text="섭씨")
#l1.grid(row=0 , column=0)
#l2.grid(row=1 , column=0)

#e1 = Entry(window)
#e2 = Entry(window)
#e1.grid(row=0 , column=1)
#e2.grid(row=1 , column=1)

#b1 = Button(window, text="화씨 -> 섭씨")
#b2 = Button(window, text="섭씨 -> 화씨")
#b1.grid(row=2 , column=0)
#b2.grid(row=2 , column=1)

#window.mainloop()


#버튼 누르면 프로세스안에 있는 값 출력하는 프로그램
#from tkinter import*

#def process():
#    print("안녕하세요")

#window = Tk()
#button = Button(window, text="클릭하세요!",command = process)
#button.pack()
#window.mainloop()


#버튼2 누르면 e2에 값에 "100"들어가는 프로그램
#from tkinter import*

#def process():
#    e2.insert(0,"100")

#window = Tk()

#l1 = Label(window, text="화씨")
#l2 = Label(window, text="섭씨")
#l1.grid(row=0 , column=0)
#l2.grid(row=1 , column=0)

#e1 = Entry(window)
#e2 = Entry(window)
#e1.grid(row=0 , column=1)
#e2.grid(row=1 , column=1)

#b1 = Button(window, text="화씨 -> 섭씨",command = process)
#b2 = Button(window, text="섭씨 -> 화씨")
#b1.grid(row=2 , column=0)
#b2.grid(row=2 , column=1)

#window.mainloop()


#화씨 섭씨 변환됨(화씨 -> 섭씨) 하지만 처음의 내용이 지워지지않음
#from tkinter import*

#def process():
#    temperature = float(e1.get())
#    mytemp = (temperature-32)*5/9
#    e2.insert(0,str(mytemp))

#window = Tk()

#l1 = Label(window, text="화씨")
#l2 = Label(window, text="섭씨")
#l1.grid(row=0 , column=0)
#l2.grid(row=1 , column=0)

#e1 = Entry(window)
#e2 = Entry(window)
#e1.grid(row=0 , column=1)
#e2.grid(row=1 , column=1)

#b1 = Button(window, text="화씨 -> 섭씨",command = process)
#b2 = Button(window, text="섭씨 -> 화씨")
#b1.grid(row=2 , column=0)
#b2.grid(row=2 , column=1)

#window.mainloop()


#섭씨 -> 화씨 , 화씨 -> 섭씨 둘다 됨
#from tkinter import*

#def process():
#    temperature = float(e1.get())
#    mytemp = (temperature-32)*5/9
#    e2.insert(0,str(mytemp))

#def process2():
#    temperature = float(e2.get())
#    mytemp = (temperature*9/5)+32
#    e1.insert(0,str(mytemp))


#window = Tk()

#l1 = Label(window, text="화씨")
#l2 = Label(window, text="섭씨")
#l1.grid(row=0 , column=0)
#l2.grid(row=1 , column=0)

#e1 = Entry(window)
#e2 = Entry(window)
#e1.grid(row=0 , column=1)
#e2.grid(row=1 , column=1)

#b1 = Button(window, text="화씨 -> 섭씨",command = process)
#b2 = Button(window, text="섭씨 -> 화씨",command = process2)
#b1.grid(row=2 , column=0)
#b2.grid(row=2 , column=1)

#window.mainloop()


#이번엔 배경 및 폰트 변경함
#from tkinter import*

#def process():
#    temperature = float(e1.get())
#    mytemp = (temperature-32)*5/9
#    e2.insert(0,str(mytemp))

#def process2():
#    temperature = float(e2.get())
#    mytemp = (temperature*9/5)+32
#    e1.insert(0,str(mytemp))


#window = Tk()

#l1 = Label(window, text="화씨",font = 'helvetica 16 italic')
#l2 = Label(window, text="섭씨",font = 'helvetica 16 italic')
#l1.grid(row=0 , column=0)
#l2.grid(row=1 , column=0)

#e1 = Entry(window, bg="yellow",fg="black")
#e2 = Entry(window, bg="yellow",fg="black")
#e1.grid(row=0 , column=1)
#e2.grid(row=1 , column=1)

#b1 = Button(window, text="화씨 -> 섭씨",command = process)
#b2 = Button(window, text="섭씨 -> 화씨",command = process2)
#b1.grid(row=2 , column=0)
#b2.grid(row=2 , column=1)

#window.mainloop()

#2교시

#박스만드는 프로그램
#from tkinter import*

#window = Tk()

#w = Label(window, text="박스 #1",bg="red",fg="white")
#w.place(x=0,y=0)
#w = Label(window, text="박스 #2",bg="green",fg="black")
#w.place(x=20,y=20)
#w = Label(window, text="박스 #3",bg="blue",fg="white")
#w.place(x=40,y=40)

#window.mainloop()


#gif파일 입력해서 사진 바꾸기
#from tkinter import*

#def change_img():
#    path = inputBox.get()
#    img = PhotoImage(file = path)
#    imageLabel.configure(image = img)
#    imageLabel.image = img

#window = Tk()

#photo = PhotoImage(file="wl.gif")
#imageLabel = Label(window, image=photo)
#imageLabel.pack()

#inputBox = Entry(window)
#inputBox.pack()
#button = Button(window, text = 'Submit', command = change_img)
#button.pack()
#window.mainloop()


#그림판 앱
#from tkinter import*

#def paint(event):
#    x1 , y1 = (event.x-1),(event.y+1)
#    x2 , y2 = (event.x-1),(event.y+1)
#    canvas.create_oval(x1,y1,x2,y2,fill = "black")

#window = Tk()
#canvas = Canvas(window)
#canvas.pack()
#canvas.bind("<B1-Motion>",paint)
#window.mainloop()

