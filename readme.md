# Postman Install
- unpack: tar -xvf postman-9.23.3-linux-x64.tar.gz

# Newman CLI Install 
npm install -g newman

# Open Postman
-  cd Postman
- ./Postman 
- Import Postman Collection
    - File:Settings:Data
    - Import CSS.Animations.postman_collection.json
      ![Request Collection](ImportCollection.png "Request Collection")
      
# Run Postman Collection
- Open '...' menu on the CSS Animations collection and select 'Run Collection'
![Postman Test Run](RunCollection.png "Test Plan Structure.")
 -Select Options and click "Run CSS Animations" 
![Postman Test Run Options](RunOptions.png "Test Plan Structure.")
- Click View Summary after test run
![Postman Test Summary](ViewSummary.png "Test Plan Structure.")
  
# Run Newman CLI on Postman Collection
- newman run CSS.Animations.postman_collection.json
- View the results output on the command line
![Newman Test Runner](NewmanTestRunnerResult.png "Newman Test Runner")

# Environment
- npm version 7.10.0
- node version v14.16.0