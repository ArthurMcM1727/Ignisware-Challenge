# Ignisware-Challenge
A Api challenge for the Ignisware DevOps internship

##
### Functional Requirements
- Interacts with the Star Wars API: Retrieve information about starships.
- Packages the solution: Build a Docker container based on the latest Ubuntu image.
- (Optional) Automates the process: Set up a GitHub Actions workflow to build and push the Docker image. 

##
### Problem statement: 
- You're challenged to create a script that retrieves information about starships from the public Star Wars API. Your solution should:
    - Fetch data from the API.
    - Extract relevant information (e.g., name, model, manufacturer, starship class).
    - Display the retrieved data in a readable format.
    - Handle pagination for retrieving all starships.
    - Implement proper error handling to deal with potential API issues.

##
### Github repo link: 
`https://github.com/ArthurMcM1727/Ignisware-Challenge.git`

##
### suggested project design
```
<your-repo-root>
    Dockerfile # Dockerfile to build the Ubuntu image with your script
    script.<ext> # Your script file (e.g., script.py if using Python)
    README.md # Instructions on building/running the container, an explanation of your approach, and bonus deployment considerations
    .github/
        workflows/
            docker-build.yml # (Optional) GitHub Actions workflow file for building/pushing your Docker image
```