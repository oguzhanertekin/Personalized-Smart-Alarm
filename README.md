# Personalized-Smart-Alarm
#(AI Model with Python)
Initially, our goal was to deduce sleep cycles with a machine learning model and a personalized sleep cycle pattern. With our personalized smart alarm project with this pattern, we aimed to understand whether the person is sleeping efficiently and to adjust the wake-up time in accordance with the person's sleep cycle. In this project, we collected sleep data for 60 days with a smart watch to learn about a person's sleep cycle. Using this data, we obtained the person's sleep cycle. Although we tried to develop a model with the data we obtained from the smart watch we have, proper sleep cycle patterns and a consistent model were not formed. Therefore, we developed a model that predicts sleep quality score based on sleep cycles, total sleep time, and total Rem/NonRem sleep time.



Sleep consists of two basic parts: rapid eye movements (REM) and non-rapid eye movements (NON-REM). These two parts follow each other all night long. Depending on the dream content, all muscles in the body are paralyzed during the REM period of eye movements. If the individual wakes up before the consciousness settles during that time, he/she feels as if he/she will not be able to get up. The most important feature of this stage is that the brain functions are as high as in wakefulness. Everything learned during the day is taken from the cache and archived and filed just like the operating system on the computer. NON-REM sleep consists of light sleep and deep sleep. Sleeps awakened before any cycle is completed are generally considered unproductive sleep.

Although we wake up at the exact time we want with the alarms we use today, we do not always wake up efficiently. For this, we planned to make a special alarm application for a user after knowing about the sleep cycles by tracking the sleep for a certain period of time.

However, with the measurements we made with the smart wristbands we have, we realized that sleep is very variable and that there is no pattern for these cycles. Therefore, at this stage, we turned our project into a project in the form of scoring the quality of a sleep entered. According to our research, we considered the sleep quality as GOOD if the sleep quality score is between 80-100, and the sleep quality is MEDIUM if it is between 50-79, otherwise is BAD.


