# π PAJAMA

---

## β¨ ν μκ°

- κΉμ€μ° : νμ₯, λ°±μλ, WebRTC κ΅¬ν, μλ² λ΄λΉ
- κΉκ²½νΈ : λ°±μλ, λͺ¨μμΈμ, μμ±μΈμ λ΄λΉ
- κΉμ μ : λ°±μλ, Entity μ€κ³ λ° API κ΅¬ν, Jiraκ΄λ¦¬μ
- μ΄λμ£Ό : νλ‘ νΈμλ
- μ μ¬μ²  : νλ‘ νΈμλ
- μ§μ£Όν : νλ‘ νΈμλ

## π‘κΈ°νλ°°κ²½

νμλ§ μλΉμ€ κΈ°ν λ°°κ²½μ μ½λ‘λ μ₯κΈ°νλ‘λΆν° μμλμμ΅λλ€.

μ½λ‘λ μ§ νμλ λΉλλ©΄ μνμ΄ λ§€μ° μμνμμ§λ§ νμ¬λ μ½λ‘λ μ₯κΈ°νλ‘ μ¨λΌμΈ νμ νμ, κ°μλ±μ΄ νμ±ν λμμΌλ©° μ΄λ° λΉλλ©΄ μλΉμ€κ° μ΅μν΄μ‘κ³  λ€μνκ² μ¬μ©λκ³  μμ΅λλ€.

κ·Έ μ€ μ ν° νν°λΌλ νλ§λ₯Ό μ ννμ¬ λ μ¨,κ³΅κ°μ μ μ½ μμ΄ μΈμ λ μ§ νν°λ₯Ό ν  μ μλ μλΉμ€λ₯Ό κΈ°ννκ² λμμ΅λλ€.

## β­νλ‘μ νΈ ν΅μ¬ κΈ°λ₯

### WebRTC

![νμλ§_μ€λͺ2](./image/νμλ§κ°μ.png)

### λͺ¨μμΈμ

- λͺ¨μ μΈμμ ν΅ν ν­μ£½ ν¨κ³Ό

![KakaoTalk_20220817_155957074](./image/ν­μ£½ν¨κ³Ό.gif)

- λͺ¨μ μΈμμ ν΅ν μ΄λΆ λκΈ°

![KakaoTalk_20220817_165807081](./image/μ΄λΆλκΈ°.gif)

- λͺ¨μ μΈμ ( ννΈ )

![ezgif-4-bba324d641](./image/ννΈμΈμ.gif)

- λͺ¨μ μΈμ ( λΈμ΄ )

![ezgif-4-7a9e4914d9](./image/λΈμ΄μΈμ.gif)

- λͺ¨μ μΈμ ( μΌ λͺ¨μ )

![ezgif-4-5b35591b16](./image/μΌμΈμ.gif)

### μμ±μΈμ(Speech-to-Text)

- μμ± μΈμμ ν΅ν΄ μμ μ¬μ

## π νλ‘μ νΈ μμΈ μ€λͺ

## ERD

![Untitled](./image/erd.png)

## β¨οΈ κΈ°μ μ€ν

![νμλ§λ‘κ³ μμ2](./image/κΈ°μ μ€ν.png)

### Server-side

- Spring Boot 2.7.1 + JPA + Gradle
- AWS
- KMS (Kurento Media Server)
- Docker
- Jenkins
- Nginx
- Node.js (express.js)
- JWT Authentication
- My SQL 8.0.30

### Client-side

- React.js 18.2.0
- Redux 4.2.0
- Node.js 16.16.0
- React Bootstrap
- Openvidu

### μ£Όμ API

- Tensorflow.js
- Web Speech Api
- WebSocket
- REST API

### νμν΄

- Gitlab
- Jira
- Notion
- Mattermost
- Webex
- Figma
- Draw.io

## π¨ Git μ»¨λ²€μ

```bash
# FEAT : μλ‘μ΄ κΈ°λ₯ μΆκ°
# FIX : λ²κ·Έ μμ 
# DOCS : λ¬Έμ μμ 
# DATA : DataSet, λ¨μ λ°μ΄ν° κ΄λ ¨ μ¬ν­
# DB : λ°μ΄ν°λ² μ΄μ€ κ΄λ ¨ μ¬ν­
# TEST : νμ€νΈ μ½λ μΆκ°
# REFACTOR : μ½λ λ¦¬ν©ν λ§
# STYLE : μ½λ μλ―Έμ μν₯μ μ£Όμ§ μλ λ³κ²½μ¬ν­
# CHORE : λΉλ λΆλΆ νΉμ ν¨ν€μ§ λ§€λμ  μμ μ¬ν­
# DIR : λλ ν λ¦¬ κ΄λ ¨ λ³κ²½μ¬ν­ (μΆκ°/μ­μ /μμ )
# DEL : μ­μ 
# ETC : κΈ°ν
# Ex) [FEAT][A-01] : νμκ°μ κ΅¬ν
################
# ! : νμ
# Ex) !FIX : λ²κ·Έ μμ  νμ, !FEAT : κΈ°λ₯ μΆκ° νμ, !DOCS : λ¬Έμν, λ¬Έμ μμ  νμ
# HOT : κΈν μμ(μ°μ  μμ μμ)
# Ex) !HOTFIX : κΈ΄κΈ λ²κ·Έ μμ  νμ
# * : λ κ°μ§ μ΄μμ νκ·Έκ° νμν  λ (κΆμ₯νμ§ μμ - λλλ‘ λ°λ‘λ°λ‘ μ»€λ° λΆνλλ¦½λλ€.)
# Ex) [FEAT] * [DIR] : νμκ°μ κ΅¬ν, λλ ν λ¦¬ λ³κ²½ XXX.Java
```

## λ°°ν¬
[λ°λ‘κ°κΈ°](https://lab.ssafy.com/s07-webmobile1-sub1/S07P11C203/-/blob/master/exec/README.md)

## π»μλΉμ€ νλ©΄

### λ©μΈ νμ΄μ§

![Untitled](./image/λ©μΈνμ΄μ§.png)

![Untitled](./image/λ©μΈμ€λͺ.png)

![Untitled](./image/λ©μΈμ€λͺ2.png)

![Untitled](./image/λ©μΈμ€λͺ3.png)

### νμκ°μ λ° λ‘κ·ΈμΈ

- νμκ°μ ( λ³ΈμΈ μΈμ¦μ μν΄ μ΄λ©μΌ μΈμ¦λ²νΈ μ μ‘ )

![KakaoTalk_20220817_165806635](./image/νμκ°μ λ‘κ·ΈμΈ.gif)

- λ‘κ·ΈμΈ , λΉλ°λ²νΈ μ΄κΈ°ν ( μ΄λ©μΌμ

![Untitled](./image/λ‘κ·ΈμΈ.png)

- μμ΄λ μ°ΎκΈ° ( μ νλ²νΈλ₯Ό ν΅ν΄ μμ΄λμ μΌλΆλ₯Ό λ³΄μ¬μ€ )
- 

![KakaoTalk_20220817_165806745](./image/μμ΄λμ°ΎκΈ°.gif)

- λΉλ°λ²νΈ μ°ΎκΈ° ( μ΄λ©μΌμ ν΅ν΄ μλ‘μ΄ λΉλ°λ²νΈλ₯Ό μ κ³΅ν¨ )

![KakaoTalk_20220817_165806880](./image/λΉλ°λ²νΈμ°ΎκΈ°.gif)

### νν°λ£Έ μμ±

![νν°μμ±](./image/νν°λ£Έ μμ±.gif)

### νμ λ―Ένλ£Έ λ° κ·Έλ£Ή μ±ν

- μ±ν νλ©΄

![KakaoTalk_20220817_145651357](./image/λΉλμ€λ°© μ±ν.png)

### μμμ¬μ

### μ¬μ§μ΄¬μ

### λ§μ΄νμ΄μ§

- μ°Έμ¬ν νν° λ³λ‘ μ°μλ μ¬μ§μ νμΈν  μ μμ

![Untitled](./image/λ§μ΄νμ΄μ§.png)

- μ¬λ¬ μ¬μ§κ³Ό νΌλ λ΄μ© μμ , νΌλ μ­μ  κ°λ₯

![Untitled](./image/νΌλ.png)
