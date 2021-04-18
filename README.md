# DORABHAI WEB-DEVELOPER HIRING

## ASSIGNMENT-01 TECH STACK-(MEAN/MERN/LAMP,AWS)

1. Create a webpage for uploading files to AWS S3 (Simple Storage Service) using the AWS S3 SDK. You can use any of the SDK available in NodeJS/PHP.
2. The uploads should support files greater than 2 GB.
   **Hint:- Use AWS Multipart uploader available in SDK to split the file into chunks and upload to S3.**
3. Create a progress bar denoting the file upload progress in the webpage.
4. Push the code base to your private repo and don't mention the ACCESS KEYS/SECRET KEYS in the codebase as exposing those would risk the company's cloud account.
5. **After completion of the above mentioned task please give access to the following to your private repository:-** 
    1. dorabhai
    2. aroopkumargochhayat

### DELIVERABLES
1. Github link to your website's codebase

## ASSIGNMENT-02 TECH STACK-(MEAN/MERN/LAMP)

1. Import the SQL database dump provided in the repository and create a dependent dropdown menu based on the data provided. SQL:- [SQL_Dump](https://github.com/dorabhai/hiring/blob/master/dorabhai2_hiring.sql)
2. If you're using MEAN/MERN stack, try connecting to the mysql database and create the dependent dropdown by using appropriate SQL queries.
3. If you're using LAMP stack, try using JQuery/AJAX to do the same.
4. Push the SQL dump and codebase to your private repository.
5. **After completion of the above mentioned task please give access to the following to your private repository:-** 
    1. dorabhai
    2. aroopkumargochhayat
### DELIVERABLES
1. Github link to your website's codebase

## ASSIGNMENT-03 TECH STACK-(MEAN/MERN/LAMP,AWS)

***THIS ASSIGNMENT IS A MERGER OF THE ABOVE TWO ASSIGNMENTS***

1. Import the available SQL dump from the repository
2. Create a webpage (form) to get metadata of uploaded file/video and insert it to notes table
3. The metadata should consist of:- 
    1. note_name
    2. file_path
    3. numberofPages
    4. teacher_email(optional)
4. Add a file option to browse files from PC to be uploaded
5. On submit the webpage the following actions should take place strictly in order:-
    1. The file should first get uploaded to AWS S3.
    2. The corresponding progress bar should denote status of uploads.
    3. Upon sucessful upload confirmation only then the form metadata to be inserted into the database.
6. Implement exception mechanisims to handle bad/unsucessful uploads.
7. **After completion of the above mentioned task please give access to the following to your private repository:-** 
    1. dorabhai
    2. aroopkumargochhayat

### DELIVERABLES
1. Github link to your website's codebase
2. SQL Dump