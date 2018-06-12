###Install below plugins

    -Maven integration plugin  
    -Checkstyle Plug-in  
    -FindBugs Plug-in  
    -Static Analysis Collector Plug-in  
    -Cobertura Plugin  

**Done**  

###Install below softwares under Global tool configuration###

   ![Maven | Maven 3.5.2](/arorah23/Assignments/tree/master/media/maven.png)  
   ![Java | You need Oracle account for same | JDK 8u162](https://github.com/arorah23/Assignments/tree/master/media/jdk.png)  
   ![ Git | You need to manually install git first](https://github.com/arorah23/Assignments/tree/master/media/git.png)  



###Setup CodeStability Job###

    -Choose Job type as MavenProject    
    -Provide git repository  
    -Use clean compile as target  

![Done](https://github.com/arorah23/Assignments/tree/master/media/codestability.png)



###Setup static code analysis Job###

    -Choose Job type as MavenProject  
    -Provide git repository https://github.com/OpsTree/ContinuousIntegration  
    -Use clean compile findbugs:findbugs checkstyle:checkstyle as target  

![Done](https://github.com/arorah23/Assignments/tree/master/media/stability.png)




###Setup code coverage Job###

    -Choose Job type as MavenProject  
    -Provide git repository https://github.com/OpsTree/ContinuousIntegration  
    -Use clean compile cobertura:cobertura as target  

![Done](https://github.com/arorah23/Assignments/tree/master/media/cobertura.png)






