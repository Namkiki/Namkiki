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

