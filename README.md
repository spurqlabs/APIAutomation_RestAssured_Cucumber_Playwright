Create a Maven project with the following folder structure: 

 
 
loanbook-api-automation 

│ 

├── .idea 

│ 

├── src 

│   └── test 

│       └── java 

│           └── org 

│               └── Spurlabs 

│                   ├── Core 

│                   │   ├── Hooks.java 

│                   │   ├── Main.java 

│                   │   ├── TestContext.java 

│                   │   └── TestRunner.java 

│                   │ 

│                   ├── Steps 

│                   │   └── CommonSteps.java 

│                   │ 

│                   └── Utils 

│                       ├── APIUtility.java 

│                       ├── FrameworkConfigReader.java 

│                       └── TokenManager.java 

│ 

├── resources 

│   ├── Features 

│   ├── headers 

│   ├── Query_Parameters 

│   ├── Request_Bodies 

│   ├── Schema 

│   └── cucumber.properties 

│ 

├── target 

│ 

├── test-output 

│ 

├── .gitignore 

├── bitbucket-pipelines.yml 

├── DealDetails.json 

├── FrameworkConfig.json 

├── pom.xml 

├── README.md 

└── token.json 
