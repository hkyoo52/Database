* DESC sample41;                                            # 각 column에 어떤 것 넣을 수 있는지 찾기
* insert into sample41 values(1,'ABC','2014-01-25');        # row에 (1, 'ABC', '2014-01-25')를 추가한다.
* insert into sample41(a,no) values('XYZ',2);               # a에는 'XYZ', no에는 2를 추가해라 (나머지 column은 null)
* insert into sample411(no, d) values(2,default);           # no에는 2, d에는 default값을 넣어라 (defalut값은 DESC sample411 치면 알 수 있음)


