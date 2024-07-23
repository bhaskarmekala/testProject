stages:
      - build

MainBuild:
      stage: build
      script: 
             -(git clone https://github.com/narendraamara/testProject.git; git pull)
             -(cd sampeapplication; clean compile install)


   added the script file to start the springboot application automatically in the production environment...!
   done
   
