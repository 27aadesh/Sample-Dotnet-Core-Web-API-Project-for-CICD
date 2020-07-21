<img src="https://github.com/27aadesh/Sample-Dotnet-Core-Web-API-Project-for-CICD/blob/master/screenshots/netcore.png" width="100" height="100"></img>
# Sample Dotnet Core Web API Project for CICD

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

This is a sample dotnet core web api project code which can be used to create CICD using Jenkins, Azure Pipelines, and other CI tools for learning purposes. 

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

Dotnet SDK is Required to run the project
Link: https://dotnet.microsoft.com/download/dotnet-core/3.1

### Installing

The below steps need to be performed to run this application:

1. Restore the Packages using the below command
'''
dotnet restore
'''

2. Build the code using dotnet publish
```
dotnet build -c release -o target/
```

3. publish the code using dotnet publish
```
dotnet publish -c release -o target/
```

4. Go to 'target' directory
```
cd target
```

5. Run the entrypoint dll
```
dotnet samplewebapi.dll
```

## Usage <a name = "usage"></a>

This project is just used for learning CICD. 
