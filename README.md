1) Install Dotnet 6.0 SDK
   USE SDK DOWNLOAD
     https://download.visualstudio.microsoft.com/download/pr/47f095fd-7aa8-4def-82d0-57897cf32202/f063bf11d48ab31bb6f87a6d582a57a8/dotnet-sdk-6.0.422-win-x64.exe

  
2) Install mongodb and make sure it is running at standard MONGO port 27017

  https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-7.0.9-signed.msi
  
3) download and install promo
   
  https://github.com/trcsolution/met-cap/blob/main/TRCPromoInstall.msi
  
   in setup needs to enter 2 arguments
   
     - STRAPI BASE URL
     
     - STRAPI TOCKEN, could be generated in strapi

 4) Open windows services and start TRCPromo service

![image](https://github.com/trcsolution/met-cap/assets/80454708/7d9da8ab-ea67-429a-b25b-85b78eb06861)


