- π Hi, Iβm @Namkiki
- π Iβm interested in ...
- π± Iβm currently learning ...
- ποΈ Iβm looking to collaborate on ...
- π« How to reach me ...

<!---
Namkiki/Namkiki is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
select row_number () over (partition A order by B desc) from data

select ntile(100) over (partition A order by sales desc) from sales_data     λ°±λΆλ₯ 

select sum(sales) over (partition A order by sales desc) from sales_data      λμ ν©κ³

select rank() over (partition A order by sales desc) from sales_data        μμ


min(case when λμ ν©κ³/μ΄ν©κ³ >= 0.8 then rank end) as rank (μμ80% μ ν΄λΉνλ μ΅μλ­ν¬)


select if( a > 1, 1λ³΄λ€νΌ,1μ΄νμ)

DATA as Select A, B, C, D, E, - - from set

       select array[A,B,C,A,E,--] from DATA
       
       select filter(array[A,B,C,A,E,--] x->, x = A) from DATA    = [A,A]
       
       select cardinality(filter(array[A,B,C,A,E,--] x->, x= A)) from DATA = 2
    
Json data 
 Data-driven Decision Makingμ μν΄ λμμμ΄ κ³ λ―Όνκ³ , μ±μ₯νλ Data Chapterμλλ€.
- λ°μ΄ν°μ κΈ°λ°ν μμ¬κ²°μ  λ¬Ένλ₯Ό νμ°μν€κ³  λΆμμ ν΅ν΄ λ ν° λΉμ¦λμ€ μν©νΈλ₯Ό λ§λλ λ°μ κΈ°μ¬ν©λλ€.

