# SIMPLE BROADCAST STREAM CRUD
 
cd  into folder rtmpserver ```npm init``` when completed run ```npm run start```\
cd  into folder server ```npm init``` when completed run ```npm run start```\
cd  into folder  client ```npm init``` when completed run ```npm run start```\

create new stream channel ```http://localhost:8000/streams/new```

## Folder: rtmserver 
The rtmserver is responsible for the connection OBS and the browser

## Folder: server 
used simple json server to presits data to json file 

## Folder: client 
Create, Read, Update and delete new streams with oauth

# Broadcast stream from desktop
download ```https://obsproject.com/```\

Setting OBS\
create custom stream service\
server ```rtmp://localhost/live```\
stream key = new stream channel id