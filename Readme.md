#Cucumber Framework for Demoblaze Application

##Framework Format
1. configuration.properties: to avoid hard coding, externalize the test data and avoid effecting the project, centralized location, cross-browser testing

2. create `resources` directory same level with `java` directory. The purpose is to hold our scenarios for the project.

3. create java packages:
    a. runners
    b. pages (POM)
    c. utilities
    d. step_definitions