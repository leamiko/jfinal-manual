#Modify web.xml

Add following content to the web.xml

```xml
	<filter>
		<filter-name>jfinal</filter-name>
		<filter-class>com.jfinal.core.JFinalFilter</filter-class>
		<init-param>
			<param-name>configClass</param-name>
			<param-value>demo.DemoConfig</param-value>
		</init-param>
	</filter>
	<filter-mapping>
		<filter-name>jfinal</filter-name>
		<url-pattern>/*</url-pattern>
	</filter-mapping>
```

