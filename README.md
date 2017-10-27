# upload
File Upload API with Spring Boot Rest
API used to upload file and write in file system. Create a directory in the drive with C:/UploadedFile Run maven install to build the app Run As Spring boot Application
To test using postman plz follow the below steps. 
URL:- http://localhost:9090/fileupload/upload 
Method:- POST 
Body-> form-data-> Key(file) -> Type(File) -> Choose Files(file to be uploaded) 
Leave Headers -> Content-Type value empty in case of postman, postman will take care automatically.
