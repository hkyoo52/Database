## update 테이블명 set 열1=값1, 열2=값2,,,, where 조건문 : 조건문이 만족하는 행의 값을 열에 나오는 값으로 바꿔라
* update sample41 set b='2014-09-07' where no=2;                          # no=2인 행에 b열을 '2014-09-07'로 바꿔라
* update sample41 set no=no+1;                                            # 모든 no값을 1씩 증가시켜라
* update sample41 set a='xxx' where no=2;                                 # no=2 행에 a값을 'xxx'로 바꿔라
* update sample41 set no=no+1, a=no;                                      # no값을 1씩 더하고 a를 no와 동일하게 바꿔라
* update sample41 a=no, set no=no+1;                                      # a값을 no로 바꾸고 no값에 1을 더해라
