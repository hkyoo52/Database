## CASE WHEN 조건문 THEN 식1 WHEN 조건문2 THEN 식2 ELSE 식3 END
* SELECT a,
    -> case
    -> when a is null then 0
    -> else a
    -> end "a(null=0)" from sample37;    # null인경우 0으로, 나머지는 a 그대로 "a(null=0)"인 부분에 저장해라
    
* SELECT a AS "코드",
    -> CASE
    -> WHEN a=1 THEN '남자'
    -> WHEN a=2 THEN '여자'
    -> ELSE '미지정'
    -> END AS '성별' FROM sample37;
    
    
