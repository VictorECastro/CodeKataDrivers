# CodeKataDrivers
Code Kata Exercise for Drivers History

This project consists in 2 different projects

1. Web site, which is created using HTML with Javascript to consume the Rest API project
2. REST API project developed with ASP.NET Core 5 Web API

Instructions to deploy:
Web Site

1. Download the website folder and create a virtual directory in IIS
2. Set the website directory as physical directory for virtual directory
3. Set default.html as default document for virtual directory
4. It is important that web sites open from localhost since this url is allowed in the REST API

REST API

1. Download RestAPI folder
2. Open published folder and add an application in IIS.
3. Set published folder as physical directory for the application.
4. configure in web site default.html file the url for the rest api in settings -> url (line 101) api resides in http://server/api/process
5. Test REST API call with postman, you can use drivers postman collection included in FilesAndPostman folder.
6. once the url is configured and API tested you can start using the program.

Open web site
Select a text file (included in the FilesAndPostman folder)
Process request and you will see the results.

