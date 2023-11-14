Udagram

AWS Cloud Setup

RDS - Database Host: 

RDS - Database Port: 5432

RDS - Database Name: 

S3 Endpoint - Frontend: 

Elastic Beanstalk URL - Backend: 


Environment Variables

Setup the following variables in the .env file or in the cloud environments:

- PORT                = 5432
- POSTGRES_HOST       = <Database_IP_Address>
- POSTGRES_DB         = <Database_Name>
- POSTGRES_USERNAME   = <Database_Username>
- POSTGRES_PASSWORD   = <Database_Password>
- URL                 = <Url>
- JWT_SECRET          = <your secret>
- AWS_REGION          = <us-east-1>
- AWS_PROFILE         = <Profile>
- AWS_BUCKET          = <Bucket_Name>