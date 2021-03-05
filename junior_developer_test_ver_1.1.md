# 구글링 가능, 구글링 한 문제는 옆에 구글링이라고 표시, 작성하지 못한 문제는 이유 간략하게 기입(ex: 시간부족) ※ 제한시간 10분
## 요지는 정답이 있는게 아니라 어떻게 문제해결을 하는지에 있습니다.

### 1. 1부터 100까지의 숫자 중 2의 배수의 합을 구하시오.
■ 조건 : 합계에 사용할 변수는 sum 사용, 값 출력 함수는 sysout으로 기입)
~~~
public class testClass {
  public static void main(String[] args) {
      int sum = 0;  // 합계에 사용할 변수	
       
    
    
    
    
    
    
    
       
  }
}
~~~

### 2. 타입이 BoardVO인 list(boardList)에 DB에서 가져온 데이터("bno", "title", "writer", "regdate")가 담겨 있고 이를 model에 담아(변수명은 "list") jsp에 전달했다. jsp에서 jstl문법으로 반복해서 이 데이터들을 전부 표시하는 코드를 완성하시오.
~~~
<c:forEach                              >
    <tr>
      <td>                </td>
      <td>                </td>	
      <td>                </td>
      <td>                </td>
    </tr>
</c:forEach>
~~~

### 3. 아래 결과물이 나오도록 코드를 작성하시오.(클릭 시 면접자의 이름을 div에 표시, jquery 써도 무방)
~~~
<button id="btn" type="button">click</button>
 <div id="area">
 </div>
<script>
  $(document).ready(function() {








});







</script> 
~~~
결과물 : <br/>
<img src="https://user-images.githubusercontent.com/44331989/94353167-ad7ba780-00a8-11eb-9650-fe2dbf54c7c1.PNG">


### 4. 아래 결과물이 나오도록 SQL문을 완성하시오. 
■ 조건 : user_id, user_nm, sex_cd컬럼만 조회하되 성별(sex_cd)이 '01'인 경우 '남성', '02'인 경우 여성 그외는 '기타'로 작성)
~~~
SELECT 
       






FROM tm_user
;

~~~
결과물 : <br/>
<img src="https://user-images.githubusercontent.com/44331989/108151937-35775200-711b-11eb-9ce1-925032402c07.png">



### 5. 아래 결과물이 나오도록 html 코드를 완성하시오.
■ 조건 : 비밀번호는 ****식으로 입력되야 함,  전송 버튼 누를 경우 form data를 test/send.do로 전달
~~~
<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>test</title>
</head>
<body>	
	<form name="frm" id="frm" action="                  ">
           이름 : <input type="text" placeholder="이름을 입력 해주세요."> <p>
        비밀번호 : <input type="              " placeholder="비밀번호를 입력 해주세요."> <p>
		<label><input type="checkbox"> 남성</label> 
		<label><input type="checkbox"> 여성</label>
		 
	</form>
</body>
</html>
	
~~~
<img src="https://user-images.githubusercontent.com/44331989/94006631-14fcd300-fddb-11ea-9b9a-f07da602ed5d.PNG">

## 고생 많으셨습니다 감사합니다.






