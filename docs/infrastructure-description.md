# Infrastructure Description

## Database
Postgres Relational Database is provided using AWS RDS


![image](https://user-images.githubusercontent.com/59806790/211573381-b2b6c8d2-c66d-44f2-9050-6bbfc4e92122.png)

## API
Backend API is hosted using AWS Elastic Beanstalk

Create Environment and Application:
![image](https://user-images.githubusercontent.com/59806790/211600122-4e328c18-600f-4bb9-af94-bed95aba21fb.png)
![image](https://user-images.githubusercontent.com/59806790/211600453-0bd040b6-a0c0-49d1-9464-b52831d4745f.png)

Deploy API and Validate:
![image](https://user-images.githubusercontent.com/59806790/211648462-a9fa1039-6a9a-4f6c-9120-7ef363b596ea.png)
![image](https://user-images.githubusercontent.com/59806790/211636416-9904465b-ce42-4d02-a4bd-f29aaed5f726.png)



## File Storage
Front-end files developed using Angular framework, front-end files and images are hosted in ASW S3 bucket

Create Bucket:
![image](https://user-images.githubusercontent.com/59806790/211578291-6767cfcf-44e1-4ed8-a33b-c3eb865df38c.png)

Make it publicly accessible: 
![image](https://user-images.githubusercontent.com/59806790/211579023-2306bb1b-9682-4bed-bd69-63c0c65f8e48.png)

Enable Static Web Hosting:
![image](https://user-images.githubusercontent.com/59806790/211579441-016ec502-b51c-431a-92f9-48c0765af1ae.png)

Upload Files:
![image](https://user-images.githubusercontent.com/59806790/211596363-8377a2c7-bc70-42dd-b6c0-8d27a2ac2e6d.png)

Access Home Page:
![image](https://user-images.githubusercontent.com/59806790/211595821-95107fab-0d19-4e10-8762-f6f5806ef67e.png)

Application is accessable via this link: [Udagram](http://udagram-app-532763768151.s3-website-us-east-1.amazonaws.com) 

### Using The Application

Click `REGISTER` in home page to sign up:
![image](https://user-images.githubusercontent.com/59806790/211641112-3bcf17ab-170a-40fa-b162-445134e5aabb.png)

Fill the form and click `REGISTER`:
![image](https://user-images.githubusercontent.com/59806790/211641139-dda09cad-7a22-4d9d-a2e5-d65e8d629703.png)
![image](https://user-images.githubusercontent.com/59806790/211641173-ba7bd26d-de60-4be7-a679-46dcf930ffde.png)

You signed up and you can see your email on the screen
![image](https://user-images.githubusercontent.com/59806790/211641203-47a464cd-4c91-4c8a-8dbd-a3fe90edc685.png)

Click `LOG OUT` 
Then `LOG IN`
![image](https://user-images.githubusercontent.com/59806790/211689113-ef2dbd9c-1ac2-4ff3-b77d-53ba8eb24a6b.png)
![image](https://user-images.githubusercontent.com/59806790/211689095-95ae667a-05f3-4e88-9256-f1c966d83b7b.png)
![image](https://user-images.githubusercontent.com/59806790/211689052-44dd6817-7ba8-4094-b18f-27a3821c02b2.png)


## Continues Integration & Continues Delivery CI/CD
Continues integration and continues delivery CI/CD are applied using CircleCi 
