# Query Optimization Checker - Colab Tool

## Setup within Google Colab  
**STEP 1:** Download File  
**STEP 2:** Update config.py with your CLIENT_ID / CLIENT_SECRET / GOOGLE_CREDENTIALS for Search Console API (Google Cloud)  
**STEP 3:** Upload files to Google Drive  
**STEP 4:** Tool should be ready to use!

## How to Use Once Setup  
Deep Dive into tool setup / functionalty can be found here https://moz.com/blog/page-level-query-analysis-at-scale-with-google-colab-python-the-gsc-api-video-instructions-included


## File Structure
```bash
< PROJECT ROOT >  
   |  
   |-- api/  
   |    |-- google/                              # API / OAuth Flow - Google Cloud OAuth Package   
   |    |       |-- __init__.py                  # API / OAuth Flow - OAuth Flow Definition 
   |    |-- google_search_console/               # API / OAuth Flow - GSC API Package   
   |    |       |-- __init__.py                  # API / OAuth Flow - Initializes `google_search_console` Package  
   |    |       |-- errors.py                    # API / OAuth Flow - Error Handles for GSC API  
   |    |       |-- gsc.py                       # API / OAuth Flow - GSC API Request
   |    |-- __init__.py                          # API / OAuth Flow  - Defines `api` Package  
   |    |-- config.py                            # API / OAuth Flow - Defines Data Request Criteria  
   |-- Query Optimization Checker.ipynb          # CORE SCRIPT - Core Script  
```

## Repo Visualization
![Visualization of the codebase](./diagram.svg)
