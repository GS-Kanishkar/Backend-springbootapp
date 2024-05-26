# Backend-springbootapp
Step 1:
    clone frontend repo ( git clone https://github.com/GS-Kanishkar/Frontend-app.git )
Step 2:
    clone backend repo (  git clone https://github.com/GS-Kanishkar/Backend-springbootapp.git )
Step 3:
    open Frontend code in VS code and install below two
        npm install
        npm install vite  
    it will install all nodemodules
Step 4:
    open Intellij IDE / any IDE and run maven install
    mvn clean
    mvn install
Step 5:
    open cmd ,change Directory to the path  where exactly docker-compose file locate 
    run the below cmd
    docker compose up --build 

open http://localhost/ in browser
    You can able to see the app

 docker ps 
 Now , You can able to view 3 Containers are running in Docker desktop !!!


