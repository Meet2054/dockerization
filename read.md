Steps to run the docker with prisma/Database

Step 1 :
    create .env file and add database url 
    then run 'npx prisma migrate dev'

Step 2 :
    Run "npx prisma generate"

Step 3 :
    Remove the Database Key from .env file 
    then run  docker run -p 3000:3000 -e DATABASE_URL="Your_Database_URL" backend_1(name of the docker image )