# 환경설정
```
git clone https://flapper@git.boaflower.com/flapper/jhmybatis
cd jhmybatis
code . (윈도우는 탐색기 해당폴더에서 VSCode 실행)
./mvnw (윈도우는 mvnw.cmd)
```
localhost:8080/jhmybatis 에서 확인

# jhmybatis
created by [JHipster](https://www.jhipster.tech/) generator  
and modified to use [Mybatis](mybatis.org) not only [Spring Data JPA](https://spring.io/projects/spring-data-jpa).
In this case,  "Region" of Entities is Mybatis applied.
Still, you can use Spring Data Jpa not only Mybatis.
And when I use Mybatis, I used HashMap instead using VO(Value Object), so there is no impl, dto, dao etc.

# 만든 이유
한국 IT개발자들이 많이 쓰는 SQL 방식의 Mybatis 를 적용한 것

# jar 생성
`./mvnw -Pprod clean verify -Dmaven.test.skip=true`
