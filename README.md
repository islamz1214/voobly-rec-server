# voobly-rec-server

Simple API to provide filenames.

## Setup

Create a .env file in the root directory and paste the following:

    CORS_ORIGIN=[ex. http://localhost:8080]
    FILE_PATH=[ex. /home/zahidulislam/Desktop/voobly-rec-scraper/downloads]

    
## Run

```shell
$ npm install
$ node index.js
```

## Results

If testing locally, go to http://www.localhost:3000/rcx and you should see all the files names from the FILE_PATH location.
