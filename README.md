# Sample Javascript/React

GH-Search is a project built using github's rest api and react that allows us to search and gather information about various github users.

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/Prayagrajacharya/GH-Search.git
   ```  


3. **Start the Application**:  
   1. Create a .env file in the root directory

   2. Add the following lines to the .env file
   ```bash 
   REACT_APP_GITHUB_URL = "https://api.github.com"
   REACT_APP_GITHUB_TOKEN = "<add your github access token here>
   ``` 

   3. Start the project using: 
   ```bash
   npm start
   ``` 


## ✨ Features  
- Search for user
- Get their repository information