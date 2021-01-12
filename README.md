# image-processing-auto-grader-test
Test submission for Image Processing Auto Grader Semester

## Works for SEM only
## Works with google drive public zip files ONLY

## Submission Format:
Take a look at the [Dummy Submission](https://drive.google.com/file/d/1pymbF9G1J4eJZ20kEgRSI_Jbw1GHpRVQ)

- Zip file with your team name (ex. **`SEM-04.zip`**)
- The zip contains **ONLY ONE** folder with your team name (ex. **`SEM-04`**)
- Inside that folder you should have at least these:
1. Files : **`main.py` `Dockerfile` `docker-compose.yml` `requirements.yml`**
2. Folders: **`output-results` `video-report`**
- Inside **`output-results`** you should have **ONLY ONE** folder with your team name **`SEM-04`** , which contains all txt files with your output for the public dataset (from **`01.txt`** to **`32.txt`**)

### In **`docker-compose.yml`** you should change only your team name


# How to use:
- Fork this repo
- Change **`SUBMISSION_DOWNLOAD_LINK`** environment variable with yours
- Do not forget to make the link public and any one can view
- Commit and Push
- It will download your submission and test it with auto grader against [public test](https://drive.google.com/file/d/19Q0H_ptIdAvEbFzgfRRJV312lVoBjfRL)
- If all is good you will get green success mark

## Notes :
- In The end of **`Run autograder`** step logs, you will find all console outputs by your submission
