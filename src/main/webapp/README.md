# 说明
该项目与SpringMVCStudy1基本相同唯一不同的是该项目是添加了视图解析器

    <bean class="org.springframework.web.servlet.view.InternalResourceViewResolver" id="viewResolver">
        <property name="prefix" value="/WEB-INF/jsp/"/>
        <property name="suffix" value=".jsp"/>
    </bean>

访问路径：http://localhost:8080/product_input.action
访问效果图在image 中的图1 和图2.