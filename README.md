# Email autoresponder
An archive of the bi1yeu's personal py script for automated replies to recruiter emails. It uses the OpenAI GPT-3 API to extract details from sent emails, to utilize in the reply function. For Indepth details and updates about it, refer to this article: [autoresponder for rectruiters emails](https://matthewbilyeu.com/blog/2022-09-01/responding-to-recruiter-emails-with-gpt-3)


The script will:

- get all emails in a specified recruitment folder
- send a personalized response to each one
- append the response to the Sent folder
- move the thread to a done folder

## Sample usage in action:
- Pulling details from sent emails
![image showing sample inbox email](https://matthewbilyeu.com/blog/assets/recruiter_mail/recruiter_mail.png)

- Using details from emails sent e.g name to automate the replies
![image showing utilization of details acquired to automate replies](https://matthewbilyeu.com/blog/assets/recruiter_mail/openai_playground.png)

## Installation

``` sh
pip install -r requirements.txt
```

## Usage

Copy the `.env.sample` file to `.env`, and fill out the configuration environment variables.

``` sh
source .env && python recruiter_rm.py
```
