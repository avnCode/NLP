# NLP

#Transformer based Translation of English to Nepali.

Here, I have used Google/mt5-small and fine tuned it on Parallel corpus.
I Created paired data using English and Nepali translation of Bible. 
31574 pair of training data was used. 

<img width="188" alt="data" src="https://user-images.githubusercontent.com/111170719/235434110-84737431-7bb6-44ea-bf56-895eace89472.png">

#Finally the above translation model was integrated with OpenAi's Davinci-003 to work as a translation chatbot, which gives answer in Nepali  when asked any english question.
Here I have used templete to instruct Davinci model to be named as #Avnish.
So when asked what is your name it replies in Nepali.

<img width="412" alt="Screenshot 2023-05-01 145159" src="https://user-images.githubusercontent.com/111170719/235434318-9e0be48a-f6dd-4429-a3d4-f75d98a397b3.png">

