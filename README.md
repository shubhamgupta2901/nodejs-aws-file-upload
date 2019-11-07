
* Reference: [Uploading a File to Amazon Web Services (AWS) S3 Bucket with Node.js
](https://medium.com/@Keithweaver_/uploading-a-file-to-amazon-web-services-aws-s3-bucket-with-node-js-133b0a1af2b9)
* Video tutorial to set up AWS IAM user and bucket policy here: [AWS S3 with Node.js - Amazon Web Services End to End Guide Dec 2017](https://www.youtube.com/watch?v=joXy_OTCO_E)

* Run command ```npm run start:dev```. This will start the server.
* Call api via postman with url: ```http://localhost:8080/api/upload``` and ```form-data``` in request body with parameters ```element1``` and ```element2```. Attach a file to value of ```element2```.

* Code written in ```server/routes/api/file.js```. Provide values of ```BUCKET_NAME```, ```IAM_USER_KEY``` and ```IAM_USER_SECRET```. 
