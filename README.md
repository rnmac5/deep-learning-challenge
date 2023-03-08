# deep-learning-challenge

https://drive.google.com/drive/folders/1j0ZoZa2P4Kd3AO7BIRL5ppFTqvnxosfq?usp=share_link


All h5 files are in the google drive, as well as the analysis.


Overview: The purpose of this analysis is to know if applicants will be successful if funded by Alphabet Soup. The project was run multiple times with multiple outcomes to see if the likelihood would increase.
Results:


Data Preprocessing
The “Is Successful” column is our target, as it most precisely tells us if the funding has succeeded or failed.
“Classification Type” and “Application Type” are the features of the model that when narrowed down to the most useful data, can better show a more concise analysis. 
The “EIN” and “Name” columns were dropped because they are both strings that would not contribute to the value of the data.
Compiling, Training, and Evaluating the Model
My first run I used 80 and 30 because I thought it would be a good starting point. My second run I used 8 and 3 because I thought that maybe using smaller integers will help narrow my chances at success. My third run I used 25 and 15, as I thought it was a middle ground between my other two runs.
With my first model I was able to reach 74.1%, the best outcome of the three. With my second model I was only able to reach 73.5% and with my third model I was only able to reach 73.7%. As a passing model would at least have to be over 75%, none of my models passed.
I tried adjusting the numbers to get better results but to no avail. I believed if I used smaller numbers I would have a better outcome but this was not the case. 


Summary:Overall this model and my many attempts failed. If I were to run it again I would try higher numbers, as my highest  numbers gave me the best results. I’m not sure if this would solve all the problems but it would be a start.

