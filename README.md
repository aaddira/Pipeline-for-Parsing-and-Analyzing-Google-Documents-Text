This code is used to parse text from Google Documents for a The Grand Bargain, a nationwide project to solve critical issues in the United States through deliberative dialogue.
Google Docs are created in a specific format for collaborative workshops, where participants vote on policy proposals and revise them. 
The code parses text from Google Docs into a Pandas dataframe that is later writte into a Google Spreadsheet. 
Statements that receive approval rate below 75% are filtered out. The remaining statements are analyzed for sentiment and keywords using NLP libraries.
The code requires using Google Drive credentials to write the spreadsheat and Google Doc.
