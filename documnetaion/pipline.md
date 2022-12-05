# orbs
    Required dependcies to run jops  

# jobs 
## build
1. install frontend dependencies
2. install backend dependencies 
2. lint FrontEnd  
3. build frontend 
4. build backend

## deploy (needs to be approved)

1. install deployment specfic dependcies 
- Elastic BeanStalk CLI
- AWS CLI
- Node.js

### Deployment 

#### front
1. build the project
2. copy final dist files into S3 (this bucket has the ability to serve static websites)  

#### front
1. build the project
2. deploy final dist files into EB (EB internally uses S3 to deploy the final dist file into EB enviroment)  





    

deploy by entering environment variables install enviroment (node, AWS cli and EB cli ) then start deploying frontend and backend

Footer

workflow
     jobs will be done in it, build job then we hold and wait for user's approval and then deploying the app.

