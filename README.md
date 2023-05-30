# mongodb
mongodb docker compose-file with mongo express 
------------------------------------------------
it consist of mongodb and and its gui verson mongo express

steps to run
-------------
clone the repository
git clone <repo>
  
 docker-compose up -d 
  
Another Gui Tool
-----------------
docker pull samueltallet/mongodb-php-gui
------------------------------------------
docker run --add-host localhost:172.17.0.1 --publish 5000:5000 --rm samueltallet/mongodb-php-gui
--------------------------------------------------------------------------  
Open your browser at this address: http://127.0.0.1:5000/ to access GUI
---------------------------------------------------------------------------
