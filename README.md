文雅的蜗牛

<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
	xmlns:aop="http://www.springframework.org/schema/aop"
	xsi:schemaLocation="
	http://www.springframework.org/schema/beans
	http://www.springframework.org/schema/beans/spring-beans-2.0.xsd
	http://www.springframework.org/schema/aop
	http://www.springframework.org/schema/aop/spring-aop-2.0.xsd">

	<aop:aspectj-autoproxy />

	<bean id="caculator" class="com.netease.course.Caculator"></bean>

	

			<bean id="loggingAspect" class="com.netease.course.LoggingAspect"></bean>
			
</beans>
