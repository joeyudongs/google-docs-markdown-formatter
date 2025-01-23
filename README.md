# Google Docs Markdown Formatter

This project provides a Google Colab notebook that converts markdown meeting notes into a well-formatted Google Doc using the Google Docs API.

## Setup
1. **Open the Notebook**  
   Open the `.ipynb` file in Google Colab (either from your cloned repo or by navigating to the file on GitHub and clicking “Open in Colab”).

2. **Install/Upgrade the Dependencies**  
   Run the **first cell**:
   ```python
   !pip install --upgrade google-api-python-client google-auth google-auth-httplib2 google-auth-oauthlib
   
3. **Restart the Runtime**
After the packages install, you may see a message like “You must restart the runtime in order to use newly installed versions.”
Go to `Runtime → Restart runtime...`, then re-run the notebook cells.

4. **Run the Main Script**
Run the second cell containing the code.
When prompted, follow the authentication flow. Once complete, a link to your newly created Google Doc should appear in the console output.


## Dependencies
- google-api-python-client
- google-auth
- google-auth-httplib2
- google-auth-oauthlib

## Usage
1. Make sure your `markdown_notes` variable is set to the desired meeting notes.
2. Run the notebook cells in Colab.
3. A link to the newly created Google Doc will be printed in the console output.

