# Repository Analysis Report Generator Data Collection Tool
This tool is used to collect statistical information from one or more GitHub repositories.  This information is then added to an excel spreadsheet which the CAST Team will use to generate a report.  

## Usage
The script is designed to run on the command line using 3 parameters, --token, --owner and --url. Used to identify the token, the repository owner and the github URL.

    main [-h] -t TOKEN -o OWNER [-u URL]

* TOKEN - GitHub personal access token.  
* OWNER - GitHub owner of the repositories being analyized.
* URL - this is an optional parameter used to identify the location of the GitHub REST API and not the location of the web site. It has a default value of https://api.github.com/.

## Get your personal access token on GitHub 
* Go to your professionnal Github account 
* In the upper-right corner of any page, click your profile photo, then click Settings
* In the left sidebar, click on Developer settings
* In the left sidebar, click on Personal access tokens
* Click Generate new token
* Give your token a descriptive name
* Click Generate token

## Output 
An excel spreadsheet containing information about the modifications to the GitHub repositories. This file will be used by the CAST Team to create a PowerPoint deck.


