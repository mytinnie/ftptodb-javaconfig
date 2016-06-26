# ftptodb-javaconfig
Use case: Upload files from FTP server to Database

Technology used: Java, Spring Boot, Spring Batch, Spring MVC, Spring Integration, Spring Data, AngularJS/REST

Description:
- Use Spring Batch to upload a file from FTP server (interval or cron):
2 steps: load file from remote to local, local to database
- Option: MVC to upload via web boweser
- Option: Spring Integration to monitor new file from remote site
- Add AngularS/REST to browse uploaded records from database
