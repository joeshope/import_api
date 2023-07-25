# import_api

Creates a JSON in current directory for Step 4 of [Snyk API Import Tool](https://github.com/snyk-tech-services/snyk-api-import). The JSON contains all repository IDs from Groups and Subgroups as well as their default branch.

REQUIRED:

FILENAME - This should match your imported-targets.log file's location

How to use:
- Clone repo
- Navigate into directory
- Run pip3 install -r requirements.txt
- Run using the above argument

example: <pre><code>python3 log_to_json.py --filename="imported-targets.log"</code></pre>

Save the import-projects.json file to use with the [Snyk API Import Tool](https://github.com/snyk-tech-services/snyk-api-import)
