### Legacy Application Modernization 

Many critical applications within our projects are over a decade old and have no build, CI/CD, automated Unit testing, Sonar, and TRO integration implemented. Several such applications must be available round the clock for the customer's reference and from time to time, the application team ended up fixing performance and TRO issues caused by bad code or by using vulnerable libraries and there were several application outages, post deployments due to missing runtime components, configuration, and source code, which caused several production deployment failures. 

This idea aids in converting all legacy applications to Maven-based build projects which are committed in Git and created a reusable Jenkins build pipeline via which he implemented all of the CI/CD process that includes build, unit testing, Sonar scanning, TRO scanning(Nexus, Whitehat SATS & DATS) and effective deployment/rollback tracker with the help of Artifactory. 
Via this process, all such legacy applications have been adapted to modern standards and this process helped to slash down the time taken to build and deploy the application binary and bring down the number of post-deployment failures due to missing components/configurations, code defects, Duplicate code, and TRO issues.


### The problem statement that the idea attempts to solve*

This idea aids in converting all legacy applications to Maven-based build projects via which all applications have been adapted to modern standards. This process helps to slash down the time taken to build and deploy the application binary and bring down the number of post-deployment failures due to missing components/configurations, code defects, and Duplicate code and also brings down the number of vulnerabilities associated with bad libraries within the code.  

###  Why is it a problem worth solving?

There are lots of critical applications within our projects that are over a decade old and have no build, CI/CD, automated Unit testing, Sonar, and TRO integration implemented. Several such applications must be available round the clock for the customer's reference and from time to time, the application team ended up fixing performance and TRO issues caused by bad code or by using vulnerable libraries and there were several application outages, post deployments due to missing runtime components, configuration, and source code, which caused several production deployment failures. 

This process listed would eliminate all of the above problems. 

### What are the benefits to the Customer if this idea is implemented?*

This process aids in keeping the application code in alignment with modern standards, this way it would be easier to upgrade the code during any migration such as the java/OS/app server’s version upgrade. 
Also, this process helps to slash down the time taken to build and deploy the application binary and bring down the number of post-deployment failures due to missing components/configurations, code defects, and Duplicate code and also brings down the number of vulnerabilities associated with bad library within the code.  


### Tell us how you came up with this idea*

The client I worked for had lots of legacy applications, and we faced frequent deployment failures from time to time due to missing components/configurations, code defects, and sometimes we had performance issues post-deployment due to Duplicate code, numerous numbers of sonar defects, or bad code. During the vulnerability breaches such as Equifax, Log 4j 1.x issues, we faced multiple challenges upgrading our code immediately. 

With this process improvement, we modernized over 60+ applications, which slashed the post-deployment issues a lot, and the code became more standard due to sonar integration and the application became less vulnerable as we integrated sonar, whitehat, and nexus to monitor for vulnerable code and library. 


### Solution Provided

I adopted a legacy application modernization approach that integrated various processes ranging from Mavenizing the application to implementing CI/CD process using Jenkins, Unit testing, TRO scanning(via Nexus, Whitehat DATS, and SATS), Sonar, Artifactory integration, established Git as a proper version control management tool via automated release process and provided an approval and Rollback step in Jenkins to deploy artifacts to production.
Technologies Used: Maven, Jenkins, Junit, Sonar, Nexus, Whitehat, Artifactory, Git, IBM UCD, Groovy 

This process was created as a reusable asset that can be used across multiple applications in other projects. 





