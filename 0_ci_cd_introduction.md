Monolithic approach/microservices

CI/CD process - devops (50-70) (Groovy(DSL pipeline - Jenkins)+ YAML (Azuredevops))

Continous Integration /Continous Delivery /Continous Deployment - (java/git/junit/maven/sonarqube/jfrog/tomcat/jenkins)
                                                                    (java/git/junit/maven/sonarqube/inbuild/tomcat/azuredevops)

                                                                    java/git/junit/maven/sonarqube/jfrog/tomcat/docker/kubernetes/jenkins

SOURCE CODE - ARTIFACT - manual (integration) - automation (continous integration) (Jenkins/azuredevops/codepipeline)
Testing webserver - automation (continous delivery)
production webserver - automation (continous deployment)

1. Source code ( Developer will write the code) (github.com - git)

2. Unit testing (java - junit/.net - nunit/js-jest/python-pytest)

    2.A. CODE QUALITY TESTING (SONARQUBE)

3. Build = machine code + Desired output(code + Unit testing) (java - maven/ant/gradle) (.net - msbuild+nuget)
                                     javascript (npm) (python -no build tools)
        (JAVA - WAR/JAR/EAR/ZIP) 
        (.NET -SLN/EXE/MSI)
    
4. ARTIFACT (WAR FILE BACKUP) 

5. WEBSERVER - ONE WAR (MULTIPLE SESSIONS) (TOMCAT ) 

6. Testing webserver (functional) (tester) (manual testing, automation testing (selenium/restassured/katalon)) 
              (delivery - automation -continous delivery)
7. Production webserver (automation - continous deployment) (manual - deploy - continous delivery)


