# reddit-chatgpt-bot
Building own chat gpt bot with reddit data
From this link: https://www.youtube.com/watch?v=EE1Y2enHrcU

## Retrieve data from reddit
Get your api key from https://www.reddit.com/prefs/apps

Give your api a name and set `redirect url` to your own machine, like in the image:
![image](https://user-images.githubusercontent.com/29816118/226233086-0febcace-db07-47ab-b01a-043b34dba90d.png)

## Get your openAI chatgpt key
https://platform.openai.com/account/api-keys

# Notes
Usage of chatGPT api key costs per token. When you generate your first key, you will get US$ 18 to spend in one month, sou you can test the API.
I did not commit my `index.json` file created because its size was greater than 100 MB, size limit for files on github repos.

I made some changes to the code as the function from `llama_index` was not working as showed in the tutorial, so after some search I found the `gpt_index` package with basically the same functions and a workaround for the errors I was getting.

You can find more details here: https://beebom.com/how-train-ai-chatbot-custom-knowledge-base-chatgpt-api/