### 1. 1부터 100까지의 숫자 중 2의 배수의 합을 구하는 코드를 구현하시오.
~~~
public class testClass {
  public static void main(String[] args) {
  	
    
    
    
    
    
    
    
  }
}
~~~

### 2. java에서 db에서 가져온 list타입 형태의 데이터를 model에 담아 jsp에 전달했다는 가정하에 jstl로 "bno(게시글 번호)", "title(글제목)", "writer(작성자)", "regdate(작성일)", "updatedate(수정일)"을 가져와서 표현하는 문법을 아래 코드를 완성하시오(모델에 담은 변수명은 "list"로 가정). 
~~~
<c:         items="${     }" var="board">
    <tr>
    	<td>                </td>
        <td>                </td>
        <td>                </td>
        <td>                </td>
        <td>                </td>
    </tr>
</c:          >
~~~

### 3. id가 "btn"인 버튼 클릭 시 "area"영역에 본인 이름을 추가하는 코드를 구현하시오.(javascript 사용)
~~~

 <div>
   <button id="btn" type="button">cl</button>
 </div>
 <div class="area">
 </div>
<script>




</script> 
~~~

### 4. 2번의 코드를 jQuery로 구현하시오.(lib는 다운받았다는 가정 하에 코드만 구현)
~~~
 <button id="btn" type="button">버튼</button>
 <div id="area">
 </div>
<script>




</script>
~~~

### 5. 아래 div의 너비 - 420px, 높이 - 200px로, 배경색을 #FF00DD로 정의하는 css 문법을 구현하시오.
~~~
<style>




</style>
<div class="good"></div>
~~~

### 6. 아래 xml(ibatis)에서 parameter값으로 전달받은 "keyword"가 있는 경우(동적 쿼리) SQL문에 AND절을 붙여 넘겨받은 "keyword"를 조건으로 추가하는 코드를 완성하시오.
~~~
<select id="test.getList" parameterClass="testVO" resultClass="resultVO">
SELECT
    title, 
    content,
    writer
FROM board_test
	WHERE bno = #bno#
    <               prepend="      " property="      ">
    	
    </                >
</select>    
~~~

### 7. 아래 SQL문에서 조건식을 추가해서 stat가 2는 "승인", 1은 "미승인", 3은 "승인대기 중", 그밖은 "기타"로 stat컬럼을 추가해서 조회하는 코드를 완성하시오.
~~~
SELECT user_idx, 
	   user_nm,
		   
		   			 stat = '2'           '승인'
		   			 stat = '1'           '미승인'
					 stat = '3'           '승인대기 중'
		   	 '기타'
		   	 AS 상태
FROM tm_user
;		
~~~

### 8. 






