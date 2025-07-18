<!-- Default servlet to serve static files -->
<servlet>
  <servlet-name>default</servlet-name>
  <servlet-class>org.apache.catalina.servlets.DefaultServlet</servlet-class>
  <load-on-startup>1</load-on-startup>
</servlet>

<!-- Mapping for static resources under /resources -->
<servlet-mapping>
  <servlet-name>default</servlet-name>
  <url-pattern>/resources/*</url-pattern>
</servlet-mapping>
