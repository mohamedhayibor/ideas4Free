# Simple and dumb emails

A way where money is like some sort of “gas” that will allow you to send emails to "important"** people.

### Target users

People drowning in emails and need money for their expertise: Professional Lawyer, Consultant, Insider in an industry, Creatives.

Scope: For only professionals who barely have time for email. (There's already plenty of alternatives for others)

Anyone needs gas in order to send their email.

1. The more important the person, the higher it cost to send an email
2. The more characters in the email, the more it would cost to send the email
3. The cost will increase quadratically based on the receiver's unread emails
4. The can use more gas to put his/her mail on top of the receiver's unread emails

The receiver can send back the amount of gas sent if he/she wants to.

There is no upper-bound as to how much it can cost to send someone an email.

Newly sign-ups will have basic amount of gas that will quickly end with inconsiderate use. Then they can link to other sources: credit card, Paypal to buy gas with.

## Why

Life is short, the last thing you want is someone blabbing about things you don’t care about and unconsiderately taking your time. We currently have good spam filters but we are suffering from people with good intentions taking needlessly our time. A president, high official or rock-star should not be afraid in giving his/her email to the public. Market pressure will make it so that only the important ones are sent out.

> This eco-system forces users to be concise, short and considerate.

### Goal

Checking mails should be fun and earn you money. Ultimately, you shouldn’t be afraid to give out your email publicly.

#### Technical scope

> simple ui, no cc or Bcc

- The system will be a closed one. For instance gmail or hotmail will not be able to send or receive mails from it. In another words, it will ignore the SMTP protocol altogether.
- Users will have to present their real names and at type of government ids in order to sign up. (To implement when abuse cases start to arise). But have the option to use their real or made-up pseudonyms. They can switch whenever they want. (The important part is that they are real and can only get one account ever and that there is no way for them to abuse the system). Less freedom, but "Trust will be the most important asset to never compromise on". 
- To mitigate phishing, tracking and malware attacks: there will be no attachments, link hyper-texting. Just plain text. There is plenty of other alternatives if the user wants to share something else.

### Vision for the Future:

- Building the most robust “Trust” system in the world: with maximum security, it should take an outsider or insider (maintainer) more than their lifespans to decrypt the plain text. The only thing we will need are some metrics (length...) to calculate the amount of gas it takes to send an email.
- You can send an email to anyone but has to pay the cost (the ultimate regulator).
- As the size of the Network grows, the more valuable the “gas” currency
- A user must be able to raise the gas amount to any level for any sender to de-incentivize them to send meaningless emails. (individual empowerment)

[MailRank Trust and reputation algorithm](https://pdfs.semanticscholar.org/1dd8/7e86c2651ca2c8edff182b6e95029ddc022c.pdf)

** important in an algorithmic sense. Read MailRank's paper above.