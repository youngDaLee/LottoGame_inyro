# LottoGame
๐ฉโ๐ป2021 1ํ๊ธฐ ์ด๋๋ก ์น ํ๋ก์ ํธ
---
### ๊ฐ๋ฐํ๊ฒฝ
- Spring 4.3.3
- Tomcat 8.5
- MySQL 8.0.22
- django 3.2.3

### DB
- id : lotto
- password : game
- DB๋ช : lottoDB
- ํ์ด๋ธ๋ช : lotto, ranking    


![db](.img/table.PNG)
![tabel](.img/show.PNG)
- 21.05.17: ํฌ๋กค๋ง ์์ 
  - winnums -> lottoNo/bnusNo ๋ก ๊ตฌ๋ถ
  - ๋ฆฌ์คํธ๋ก ๋ฒํธ ๋ฐ์์ค์ง ์๊ณ  ๊ฐ๊ฐ ๋ฐ์์ด(lottoNo -> num1, num2, ... ,num6, bonus)
- db์์ 
  - ์ด๋ฆ ์ง๊ด์ ์ผ๋ก firstWinamnt -> price1, ..., price5         

![rank](.img/rankingtable.PNG)
- ranking table
- ์ด ํ์ด๋ธ์ rest framework๋ก /api/rank/ ์ ๋ณด๋
- ์ด์ : ๋๋ค์์ ์ด๋ป๊ฒ ๋ฐ์์ง
### ์ฐธ๊ณ  ๋ธ๋ก๊ทธ
- [Spring ํ๋ก์ ํธ ์ธํ ๋ฐ DB ์ฐ๊ฒฐ](https://all-record.tistory.com/176?category=733072)
### ์๋ฌ
- [Junit](https://subdong2.tistory.com/82)
- [JDBC์ฐ๊ฒฐ](https://yunyoung1819.tistory.com/89)
- [log4j.xml์์ DTD์๋ฌ](https://blog.itpaper.co.kr/spring-log4j-error/)