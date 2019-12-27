# Sentimental-Analysis-using-live-Tweets
In this project I have tried to find the Sentiment related to recent tweets.
When running the script through console please paste  twitter app credentials(remove the current text and simply paste credentials) in the file named 'credential_file.txt'(every credential should be separated by newline and in order: consumer_key, consumer_secret, access_token, access_token_secret) and the search query for tweets in a file named 'query.txt' in single line.
We can use a different file name as well but then you have to pass those file names as arguments while running script as:
python get_tweets.py --credential_file <your credentials file name> --query <query file name> --num <number of tweets we want your script to parse>
Everytime before running the script, please move the old .json file somewhere other than current working folder, so that any desireable data could be preserved from our last search.
