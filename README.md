# Google Docs Markdown Formatter

This project provides a Google Colab notebook that converts markdown meeting notes into a well-formatted Google Doc using the Google Docs API.

## Setup
1. Open the `.ipynb` file in Google Colab.
2. Run the first cell to install required libraries:
!pip install --upgrade google-api-python-client google-auth google-auth-httplib2 google-auth-oauthlib

3. Run the second cell to execute the main script.
4. Authenticate with Google when prompted, and wait for the script to create a new Google Doc.

## Dependencies
- google-api-python-client
- google-auth
- google-auth-httplib2
- google-auth-oauthlib

## Usage
1. Make sure your `markdown_notes` variable is set to the desired meeting notes.
2. Run the notebook cells in Colab.
3. A link to the newly created Google Doc will be printed in the console output.

