Maven 3.x Jdee Plugin for Emacs
======


Create a Emacs JDEE project for a maven2 based project

The original project is [here](https://code.google.com/p/m2jdee/)

I modify it for newest maven support, it supports Maven 3.x

1. Get the project

        git clone https://github.com/songuo/m2jdee.git
        cd m2jdee
        mvn install
    
2. Update the ~/.m2/settings.xml, add

        <pluginGroups>
          <pluginGroup>org.apache.maven.plugins</pluginGroup>
        </pluginGroups> 
    
3. Generate your jdee project

        cd YOUR_M2_PROJECT
        mvn jdee:jdee 

  To clean the jdee project

        mvn jdee:clean
