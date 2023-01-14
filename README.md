# PruebaTecnica

1. En el proyecto hay dos carpetas una con el Front End y la otra con Back End.
  Back End.
  Instalar las dependencias con - npm install este estará en un puerto de servidor especificado en el archivo ".env"
    
     La base de datos que se uso es MONGODB y esta base de datos esta en la nube (mongoodb atlas) la url con el usuario y password esta en el archivo .env
     
   Se tiene un endpoint POST llamado /customerCard para poder ingresar la información de la base de datos
   Se tiene un endpoint GET /getAllCustomerCard para obtener los datos de la base de datos
   
   Se remite la colección de postman para poder realizar dichas peticiones
   
2. Back End.
  Instalar las dependencias con - npm install y despues de iniciar el back end se podra realizar el registro de las tarjetas. 
  
    Las tarjetas que pueden ser iniciadas es 
      Las tarjetas Visa siempre comienzan con el número 4.
      Las tarjetas Mastercard empiezan con el número 5.
      Las American Express siempre empiezan con 3.
      Las Discovery Card con 6 
      Las JCB con 2131
