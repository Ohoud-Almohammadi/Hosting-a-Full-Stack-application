# Hosting a Full-Stack application

---

In this project i developy a Full-Stack application  to a aws cloud service so that it is available to customers to register and login. 


# Udagram

This udagram application is a simple application that includes all the major components and functions of a Full-Stack web application.



### Dependencies

```
- Node v14.15.1 (LTS) or more recent. 

- npm 6.14.8 (LTS) or more recent.

- AWS CLI v2

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
1. In AWS, provision a s3 bucket for hosting the uploaded files. 
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd project-starter-master/udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api with`npm run start`and in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd project-starter-master/udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.



## Running application
  [The app is accessible via the link here](http://mybucket495892423351.s3-website-us-east-1.amazonaws.com/)
  
![working application](https://user-images.githubusercontent.com/114148856/210177255-42ca5a47-78f8-4145-bb41-f6f80f74ccf0.png)







## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
