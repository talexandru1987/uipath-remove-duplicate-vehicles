# uipath-remove-duplicate-vehicles-in-autoline

#Description

When the daily MOT check scenario runs it identifies duplicate vehicles and stores them in a knack object 
(https://builder.rd.knack.com/salesjourney/digital/records/objects/object_173). 
Every day at a specified time an Integromat scenario (https://www.integromat.com/scenario/3058298/edit) 
takes vehicles from the object and starts the Uipath process in which duplicate vehicles are identified and marked for delete



#Logic to determine which vehicle needs to be deleted
![image](https://user-images.githubusercontent.com/45364158/168572874-a22732dc-1268-4d34-a8d0-3ea4f7c1e6dc.png)
