### 1. 1부터 100까지의 숫자 중 2의 배수의 합을 구하는 코드를 구현하시오.
~~~
public class testClass {
  public static void main(String[] args) {
  	
    
    
    
    
    
    
    
  }
}
~~~

### 2. java단에서 db에서 가져온 list타입 형태의 데이터를 model에 담아 jsp에 전달했다는 가정하에 jstl로 "bno(게시글 번호)", "title(글제목)", "writer(작성자)", "regdate(작성일)", "updatedate(수정일)"을 가져와서 표현하는 문법을 아래 코드를 완성하시오(모델에 담은 변수명은 "list"로 가정). 
~~~
<c:         items="${        }" var="board">
    <tr>
    	<td>                 </td>
        <td>                 </td>
        <td>                 </td>
        <td>                 </td>
        <td>                 </td>
    </tr>
</c:          >
~~~

### 3. 아래 코드를 보고 결과물이 나올 수 있도록 코드를 완성하시오.
~~~
public class Test2 {
	public static void main(String[] test) {
	
	String str = "아이언맨#캡틴아메리카#헐크#토르#닥터스트레인지";
	String[] newStr = 
	
    for(int i = 0; i <                 ;     ) {
			System.out.println("newStr : " +             );
		}
	}
}
~~~
결과물 : <br/>
newStr : 아이언맨 <br/>
newStr : 캡틴아메리카 <br/>
newStr : 헐크 <br/>
newStr : 토르 <br/>
newStr : 닥터스트레인지 <br/>

### 4. id가 "btn"인 버튼 클릭 시 "area"영역에 본인 이름을 추가하는 코드를 구현하시오.(javascript 사용)(문제를 더 명확하게 기입 필요)
~~~

 <div>
   <button id="btn" type="button">cl</button>
 </div>
 <div class="area">
 </div>
<script>




</script> 
~~~

### 5. 4번의 코드를 jQuery로 구현하시오.(lib는 다운받았다는 가정 하에 코드만 구현)(2번과 )
~~~
 <button id="btn" type="button">버튼</button>
 <div id="area">
 </div>
<script>
$(document).ready(function() {
	
    
    
    
    
});
</script>
~~~

### 6. 아래 div의 스타일을 너비 - 420px, 높이 - 200px로, 배경색을 #FF00DD로 정의하는 css 문법을 구현하시오.
~~~
<style>




</style>
<div class="good"></div>
~~~

### 7. 아래 xml(ibatis)에서 parameter값으로 전달받은 "keyword"가 있는 경우(동적 쿼리) SQL문에 AND절을 붙여 넘겨받은 "keyword"를 조건 추가하는 코드를 완성하시오.
~~~
<select id="board.getList" parameterClass="boardVO" resultClass="resultVO">
SELECT
        title, 
        content,
        writer
FROM board
		WHERE bno = #bno#
        <               prepend="      " property="      ">

        </                >
</select>    
~~~

### 8. 아래 SQL문에서 조건식을 추가해서 stat가 2는 "승인", 1은 "미승인", 3은 "승인대기 중", 그밖은 "기타"로 stat컬럼을 추가조회하는 코드를 완성하시오.
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

### 9. 이클립스 환경 & tomcat container 구동 중 아래와 같은 에러가 발생했다. 어느부분을 확인해 봐야 될지 기입 하시오.
~~~
9월 23, 2020 8:03:52 오후 org.apache.catalina.core.StandardContext listenerStart
심각: Context initialized 이벤트를 [org.springframework.web.context.ContextLoaderListener] 클래스의 인스턴스인 리스너에 전송하는 동안 예외 발생
org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in ServletContext resource [/WEB-INF/spring/root-context.xml]: Bean instantiation via constructor failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Constructor threw exception; nested exception is com.zaxxer.hikari.pool.HikariPool$PoolInitializationException: Failed to initialize pool: Could not connect to address=(host=123.165.242.176)(port=3306)(type=master) : Connection timed out: connect
	at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:282)
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.autowireConstructor(AbstractAutowireCapableBeanFactory.java:1276)
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1133)
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:543)
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:503)
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:317)
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222)
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:315)
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:199)
	at org.springframework.beans.factory.support.DefaultListableBeanFactory.preInstantiateSingletons(DefaultListableBeanFactory.java:760)
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:869)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550)
	at org.springframework.web.context.ContextLoader.configureAndRefreshWebApplicationContext(ContextLoader.java:409)
	at org.springframework.web.context.ContextLoader.initWebApplicationContext(ContextLoader.java:291)
	at org.springframework.web.context.ContextLoaderListener.contextInitialized(ContextLoaderListener.java:103)
	at org.apache.catalina.core.StandardContext.listenerStart(StandardContext.java:4682)
	at org.apache.catalina.core.StandardContext.startInternal(StandardContext.java:5143)
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:183)
	at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBase.java:717)
	at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:690)
	at org.apache.catalina.core.StandardHost.addChild(StandardHost.java:705)
	at org.apache.catalina.startup.HostConfig.deployDescriptor(HostConfig.java:631)
	at org.apache.catalina.startup.HostConfig$DeployDescriptor.run(HostConfig.java:1831)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at org.apache.tomcat.util.threads.InlineExecutorService.execute(InlineExecutorService.java:75)
	at java.util.concurrent.AbstractExecutorService.submit(AbstractExecutorService.java:112)
	at org.apache.catalina.startup.HostConfig.deployDescriptors(HostConfig.java:526)
	at org.apache.catalina.startup.HostConfig.deployApps(HostConfig.java:425)
	at org.apache.catalina.startup.HostConfig.start(HostConfig.java:1576)
	at org.apache.catalina.startup.HostConfig.lifecycleEvent(HostConfig.java:309)
	at org.apache.catalina.util.LifecycleBase.fireLifecycleEvent(LifecycleBase.java:123)
	at org.apache.catalina.util.LifecycleBase.setStateInternal(LifecycleBase.java:423)
	at org.apache.catalina.util.LifecycleBase.setState(LifecycleBase.java:366)
	at org.apache.catalina.core.ContainerBase.startInternal(ContainerBase.java:936)
	at org.apache.catalina.core.StandardHost.startInternal(StandardHost.java:841)
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:183)
	at org.apache.catalina.core.ContainerBase$StartChild.call(ContainerBase.java:1384)
	at org.apache.catalina.core.ContainerBase$StartChild.call(ContainerBase.java:1374)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at org.apache.tomcat.util.threads.InlineExecutorService.execute(InlineExecutorService.java:75)
	at java.util.concurrent.AbstractExecutorService.submit(AbstractExecutorService.java:134)
	at org.apache.catalina.core.ContainerBase.startInternal(ContainerBase.java:909)
	at org.apache.catalina.core.StandardEngine.startInternal(StandardEngine.java:262)
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:183)
	at org.apache.catalina.core.StandardService.startInternal(StandardService.java:421)
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:183)
	at org.apache.catalina.core.StandardServer.startInternal(StandardServer.java:932)
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:183)
	at org.apache.catalina.startup.Catalina.start(Catalina.java:633)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.catalina.startup.Bootstrap.start(Bootstrap.java:344)
	at org.apache.catalina.startup.Bootstrap.main(Bootstrap.java:475)
Caused by: org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Constructor threw exception; nested exception is com.zaxxer.hikari.pool.HikariPool$PoolInitializationException: Failed to initialize pool: Could not connect to address=(host=123.165.242.176)(port=3306)(type=master) : Connection timed out: connect
	at org.springframework.beans.BeanUtils.instantiateClass(BeanUtils.java:182)
	at org.springframework.beans.factory.support.SimpleInstantiationStrategy.instantiate(SimpleInstantiationStrategy.java:117)
	at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:275)
	... 55 more
Caused by: com.zaxxer.hikari.pool.HikariPool$PoolInitializationException: Failed to initialize pool: Could not connect to address=(host=123.165.242.176)(port=3306)(type=master) : Connection timed out: connect
	at com.zaxxer.hikari.pool.HikariPool.throwPoolInitializationException(HikariPool.java:569)
	at com.zaxxer.hikari.pool.HikariPool.checkFailFast(HikariPool.java:555)
	at com.zaxxer.hikari.pool.HikariPool.<init>(HikariPool.java:115)
	at com.zaxxer.hikari.HikariDataSource.<init>(HikariDataSource.java:81)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
	at org.springframework.beans.BeanUtils.instantiateClass(BeanUtils.java:170)
	... 57 more
Caused by: java.sql.SQLNonTransientConnectionException: Could not connect to address=(host=123.165.242.176)(port=3306)(type=master) : Connection timed out: connect
	at org.mariadb.jdbc.internal.util.exceptions.ExceptionMapper.get(ExceptionMapper.java:175)
	at org.mariadb.jdbc.internal.util.exceptions.ExceptionMapper.connException(ExceptionMapper.java:83)
	at org.mariadb.jdbc.internal.protocol.AbstractConnectProtocol.connectWithoutProxy(AbstractConnectProtocol.java:1092)
	at org.mariadb.jdbc.internal.util.Utils.retrieveProxy(Utils.java:493)
	at org.mariadb.jdbc.MariaDbConnection.newConnection(MariaDbConnection.java:150)
	at org.mariadb.jdbc.Driver.connect(Driver.java:86)
	at com.zaxxer.hikari.util.DriverDataSource.getConnection(DriverDataSource.java:117)
	at com.zaxxer.hikari.util.DriverDataSource.getConnection(DriverDataSource.java:123)
	at com.zaxxer.hikari.pool.PoolBase.newConnection(PoolBase.java:365)
	at com.zaxxer.hikari.pool.PoolBase.newPoolEntry(PoolBase.java:194)
	at com.zaxxer.hikari.pool.HikariPool.createPoolEntry(HikariPool.java:460)
	at com.zaxxer.hikari.pool.HikariPool.checkFailFast(HikariPool.java:534)
	... 64 more
Caused by: java.net.ConnectException: Connection timed out: connect
	at java.net.DualStackPlainSocketImpl.waitForConnect(Native Method)
	at java.net.DualStackPlainSocketImpl.socketConnect(DualStackPlainSocketImpl.java:85)
	at java.net.AbstractPlainSocketImpl.doConnect(AbstractPlainSocketImpl.java:350)
	at java.net.AbstractPlainSocketImpl.connectToAddress(AbstractPlainSocketImpl.java:206)
	at java.net.AbstractPlainSocketImpl.connect(AbstractPlainSocketImpl.java:188)
	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)
	at java.net.SocksSocketImpl.connect(SocksSocketImpl.java:392)
	at java.net.Socket.connect(Socket.java:589)
	at org.mariadb.jdbc.internal.protocol.AbstractConnectProtocol.connect(AbstractConnectProtocol.java:447)
	at org.mariadb.jdbc.internal.protocol.AbstractConnectProtocol.connectWithoutProxy(AbstractConnectProtocol.java:1084)
	... 73 more
~~~

### 10. 결과물이 아래와 같이 나오도록 html 코드를 완성하시오.
■ 조건 : 이름 최대입력 길이 8자,
        비밀번호 최대입력 길이 12자,
        전송 버튼 누를 경우 form data를 test/send.do로 전달
~~~
<form							>
	이름 : 
	비밀번호 : 
    






</form>
~~~
<img src="https://user-images.githubusercontent.com/44331989/94006631-14fcd300-fddb-11ea-9b9a-f07da602ed5d.PNG"/>

## 감사합니다.






