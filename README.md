# Test-technique-Cartelis-

There are two files: a Gsheet.ipynb which could be opened by Jupyter Notebook and a .json file which has to be placed in the same folder as the Gsheet.ipynb.

This script is based on the Google Sheet API, but it is not automatic. Too run the file, you have to create a project on https://console.developers.google.com/ and then enable the Google Sheet API, then create service acount key, choose 'JSON' as key type and finally download the .json file. Open the .json file, find the email adress like 'XXX@XXX.iam.gserviceaccount.com'. Share the Google Sheet that you want to deduplicate with this email adress.

And then, open the Gsheet.ipynb via Jupyter Notebook, modify the name of .json file and the name of Google Sheet.

Finally, you can run the code.
