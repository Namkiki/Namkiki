- 👋 Hi, I’m @Namkiki
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Namkiki/Namkiki is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
select row_number () over (partition A order by B desc) from data

select ntile(100) over (partition A order by sales desc) from sales_data     백분률

select sum(sales) over (partition A order by sales desc) from sales_data      누적합계

select rank() over (partition A order by sales desc) from sales_data        순위


min(case when 누적합계/총합계 >= 0.8 then rank end) as rank (상위80% 에 해당하는 최소랭크)


select if( a > 1, 1보다큼,1이하임)

DATA as Select A, B, C, D, E, - - from set

       select array[A,B,C,A,E,--] from DATA
       
       select filter(array[A,B,C,A,E,--] x->, x = A) from DATA    = [A,A]
       
       select cardinality(filter(array[A,B,C,A,E,--] x->, x= A)) from DATA = 2
    
Json data 
 Data-driven Decision Making을 위해 끊임없이 고민하고, 성장하는 Data Chapter입니다.
- 데이터에 기반한 의사결정 문화를 확산시키고 분석을 통해 더 큰 비즈니스 임팩트를 만드는 데에 기여합니다.


[이런 분을 찾아요]

- 데이터 분석 및 관련 프로젝트 수행 경력이 4년 이상이신 분
- 로그 수준의 데이터를 분석하여 구체적이고 유의미한 인사이트를 도출해본 경험이 있으신 분
- BigQuery로 원하는 데이터를 추출할 수 있으신 분
- Tableau를 통한 데이터 인사이트 전달이 가능하신 분
- A/B 테스트의 설계부터 운영, 분석, 공유, 회고까지의 전 과정을 경험해보신 분
- Amplitude 등의 툴을 사용하여 Behavior Data를 분석 가능하신 분
- 코호트 분석, 퍼널 분석 등 다양한 분석 방법론을 사용하실 수 있는 분
