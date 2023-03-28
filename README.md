# r4ds
#강의요약 'Tidyverse part_1'
tidyverse 6가지 기능
  :select, filter, arrange, mutate, summarize, group_by
  파이프기능을 사용하면 내용을 이해하기쉽다. 

#강의요약 "Tidyverse part_2'
*select
    원하는 컬럼만 추출(변수명, 변수번호) 또는 
    특정변수만 제거 (select (-(1:5) 또는 
    공통된 단어 contains('y3'), starts_with, ends_with 또는 
    변수명변경 (새로운이름 앞)
    변수순서 변경 (

#강의요약 "Tidyverse part_3'
*filter 
    작은 데이터셋을 만들어서 사용, 복합조건가능 
    between 
    복합조건 OR (|)
    더 복합조건 AND , OR ( & ) | ( & )
    조건을 만족하지 않는 경우 (=!)
    해당변수 카운트 (count=)
    결측값 카운트 (is.na) 또는 결측값이 아닌것 (!is.na)
    결측값이 있는 건 제외 =drop (drop.na)
    
#강의요약 "Tidyverse part_4'
 *mutate
    새로운 변수 생성 
    조건을 이용한 새로운 변수 생성 -> ifelse(조건, 조건이 참일경우, 조건이 거짓일경우)
    ifelse: 조건에 따라 그룹핑할때 enter를 하면 가독성이 올라감. 
    변수복합조건: high, intermediate, high risk 
    id의 누적합계: sumid 변수생성
    여러개의 변수 생성
    연속변수를 범주형으로 그룹핑
    cut (해당 variaebl, c'나눌구간' , c'구간의 이름' ) 
    -> ex) cut (age,
                c(c-inf,30,40,50,60,inf),
                c('<30','>=30', '>=40',)))
                
    
 
 
