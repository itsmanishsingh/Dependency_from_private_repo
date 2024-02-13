# Dependency_from_private_repo

STEPS TO ADD DEPENDENCY FROM PRIVATE REPOSITORY 

 

Steps to install private repository dependency using Yarn. 

 

 a. Generate Personal Access Token on GitHub 

    - Go to your GitHub account settings and navigate to "Developer settings" > "Personal access tokens." 

    - Click on "Generate new token" and select the necessary permissions for accessing private repositories (e.g., `repo`). 

    - Copy the generated personal access token. 

 

 b. yarn add https://<username>:<access-token>@github.com/your-username/your-private-repo 

 

   For example: 

      Username -> Mukund 

      access-token -> ghp_t9yHXNlmkTakn8kyoId0ohmGoNhzPM3Y 

      yarn add https://Mukund:ghp_t9yHXNlmkTakn8kyoId0ohmGoNhzPM3Y@github.com/Mukund/Yarn-react-cache-buster.git 

 

c. Check package.json file 

    Private Repository got added in the dependency. 

   ![package.json](/assets/Picture1.png)
 

 

d. Check node module  

   - repo structure of that particular private repository has been updated. 
   ![Node_Module](/assets/Picture2.png)
          

e. In yarn.lock file version of that particular repository has been updated. 
   -   ![yarn.lock](/assets/Picture3.png)
 
