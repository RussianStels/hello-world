# hello-world
second attempt to deal with github)


# вступление
>Я долго к этому шёл-шёл и в конце концов пришёл
— сказал я

# управление
1. откройте проект
2. скачайте программу
3. просто программу
4. НАСЛАЖДАЙТЕСЬ

# благодарности
спасибо коту Шалфею за: 
+ мурмяу
+ уруру

<
import time
location = "start"
role = "???"
while True:
  if location == "start":
    print("я просыпаюсь в какой-то хибаре и вижу записку")
    answer = int(input("Прочитать (1) или Осмотреться(2)"))
    if (answer == 1):
      location = "start_1"
      role = "hero"
    else:
      location = "start_o"
      role = "killer"
  elif location == "start_1":
    role = "hero"
    print("в записке написано что я не буду помнить что на записке карта,  под столом меч и мне надо двигать на восток к городку Энестель и код от замка 12321")
    time.sleep(1)
  elif location == "start_o":
    print("Вы осмотрелись")
    location = "sword"
  elif location == "sword" and role == "killer":
    print("я нашёл и сразу взял меч бастард, который сразу лёг в руку как продолжение моей руки - у меча было линзавидное с долом сечение и им можно было только рубить, но это щас не главное подойдя к двери я увидел  магический замок из риндерита который я с лёгкостью разрубил и тем самым опробовав свой бастард который при своей лёгкости был очень очень острым")
    time.sleep(1)
  elif location == "street" and role == "killer":
      print("на улице я обнаружил лошадь с приторчёным к седлу полным колчаном стрел и луком, а рядом стоял человек держащий её за узды который ответил отказом как только я попросил лошадь парень не успел охнуть меч с шипением вылетел из ножен и голова человека отлетела на 2 метра разбрызгивая кровь")
      print("где-то к вечеру я добрался в городок и доехал до трактира где походу было мало народу так как шума не было от слова совсем заведя коня в конюшню я порылся в сёдельных сумках и достал один золотой и пять медяков и стилет после я вошёл в трактир.");
      location = "tavern";
      time.sleep(1)
  elif location == "tavern" and role == "killer":
      print("зайдя в трактир я увидел 4 человека которые потягивая пивко и тихо разговаривали пока я шёл к стойке.Подойдя к стойке я втихаря переложил стилет в руку и заказал себе мяса и пива и я хотел уже съёжиться за стол когда ко мне подошли те четверо и они мне начали втирать что те де они охраняют некого богача и энто его корчма которую он те де выкупил на время своего пребывания")
      time.sleep(1)
      answer = int(input(послать(1) 
  elif location == "street" and role == "hero":
      print("на улице я обнаружил лошадь с приторчёным к седлу полным колчаном стрел и луком, а рядом стоял человек держащий её за узды который ответил отказом как только я попросил лошадь и я медленно пошёл по улице городка на восток")
      time.sleep(1)
print(" И это был его конец", end="")
for i in range(3):
  time.sleep(1)
  print(".", end="")
time.sleep(3)
s = "Так! Чего грустим! История ведь не закончена! Завтра вторая глава будет а щас спать!"
ls = s.split('!')
for i in ls:
  time.sleep(1.5)
  print(i, end="!")
time.sleep(5)
print()
print(" Глава 1 закончена! Мои поздравления!")
>
