## select * from 테이블명 group by 열1, 열2,,,,
* select name from sample51 group by name;          # name열을 그룹화해라
* select name, count(name), sum(quantity) from sample51 group by name;      # group by한 것의 총합 각각 구해라

* select name, count(name) from sample51 group by name having count(name)=1;     # 그룹화한것중 name의 개수가 1인 것만 골라서 name, count(name) 출력해라
* select name as n, count(name) as cn from sample51 group by name having count(name)=1;   # 이름도 n, cn으로 바꿔라
* select name, count(name), sum(quantity) from sample51 group by name order by sum(quantity) desc;
