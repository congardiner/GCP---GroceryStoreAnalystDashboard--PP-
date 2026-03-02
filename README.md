






## Submission Criteria:

- Link to Github Repo: https://github.com/congardiner/app_challenge_fa25
- GCP Cloud URL: https://app-challenge-fa25-387093992096.us-west3.run.app/ 
- All comments enclosed within the vocab response section of the readme.md file.
- I've had no issues with cloning the repo, building the docker image, or deploying to GCP Cloud Run at this time of writing (I had a number of issues initially, as GCP was extremely cumbersome to use due to constant lagging and timeouts, after changing my yaml and the initial setup within GCP to accommodate for more memory and vCPUs, it has been smooth sailing since then).
- I made sure to address the requirements as I understood for each of the questions, with particular reference to the stores (all Idaho based stores) and their respective data. There is a bit of a lag window when loading the app on Google Cloud, I've enabled 8GB of memory to help with this, alongside with 2 vCPUs for performance; once it has initially loaded, the performance is decent from there on out.