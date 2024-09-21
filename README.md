## Specification

- Java 21
- Spring Boot 3.3.4
- Spring Batch 5.1.2
- MySQL

---

## Example

- datasets: 100 million
- Reader
  - ZeroOffsetItemReader (with QueryDSL-JPA)
- Writer
  - JDBC Batch Insert

---

## References

- [Spring Batch 애플리케이션 성능 향상을 위한 주요 팁 (김남윤, Yun)](https://youtu.be/VSwWHHkdQI4?si=a48wd9Ft7cpELFaJ9Q1J9A)
  - [블로그](https://tech.kakaopay.com/post/spring-batch-performance/)
- [데이터 배치 퍼포먼스 극한으로 끌어올리기: 1억 건 데이터 처리를 위한 노력 / if(kakao)dev2022](https://youtu.be/2IIwQDIi3ys?si=aDZLuI_Nkr8ElzcR)
  - [블로그](https://tech.kakaopay.com/post/ifkakao2022-batch-performance-read/)
- [우아한테크세미나 - 우아한스프링배치 이동욱님](https://youtu.be/_nkJkWVH-mo?si=sbXij-MUAKFYNRDX)
  - [Spring Batch in Action](https://github.com/jojoldu/spring-batch-in-action)
  - [블로그](https://jojoldu.tistory.com/category/Spring%20Batch?page=5)
- [DevCan - spring batch 발표](https://youtu.be/VMizPUHTQ7o?si=WpLcoEJCKznlvV7Z)

