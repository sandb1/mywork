# mywork
<!--spring-servlet.xml-->
<?xml version="1.0" encoding="UTF-8"?>
<web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xmlns="http://java.sun.com/xml/ns/javaee"
	xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_3_0.xsd"
	id="WebApp_ID" version="3.0">

	<display-name>MySpringMVCAnno</display-name>
	<servlet>
		<servlet-name>spring</servlet-name>
		<servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>

		<!-- <init-param> <param-name>contextconfigLocation</param-name> <param-value>/WEB-INF/spring-config.xml</param-value> 
			</init-param> -->

	</servlet>
	<servlet-mapping>
		<servlet-name>spring</servlet-name>
		<url-pattern>/welcome</url-pattern>
	</servlet-mapping>

</web-app>
















