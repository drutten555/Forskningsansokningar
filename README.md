Code in main uses OpenAI's GPT to extract scores and remarks from feedback documents per funder.

Requires API-key.

### funderScores.ipynb

Takes feedback pdf files from funders, extracts categories and scores, stores them (with easy export to Excel) and creates bar plots of category importance with success rate. Use for one funder at a time.
  
Requires .env file with folder paths and that data is organized per funder. For each funder, folders for granted and rejected pdf files, as well as their txt counterparts, e.g. "granted" and "grantedtxt" for one funder.

### funderRemarks.ipynb

 Takes files as above, identifies and summarizes written feedback remarks. Creates categories based on these remarks, then assigns boolean values of the categories to each filename depending on if its content matches with the categories provided. Possible to predefine other categories instead of letting LLM identify them. Creates simple plots to visualize frequency of said categories.
  
As above, .env file with paths required. 
