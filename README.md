# bank_marketing_CaseStudy
Objective:
The objective is to predict if the client will subscribe (yes/no) to a term deposit, by building classification model using Machine learning algorithms

Data:
The data is related with direct marketing campaigns of a banking institution.The marketing campaigns were based on phone calls.often,more than one contact to the same client was required,in order to access if the product(bank term deposit) would be(orn not) subscribed.

Parameter    Description
age          Age of the clients(numeric)
job          Marital status of clients(categorical)
marital      Martial status of clients(categorical)
education    Education level of clients(categorical)
default      has credit in default(categorical: yes and no)
balance      average yearly balance in euros(numeric)
housing      has housing loan?(categorical:yes or no)
loan         has personal loan?(categorical yes or no)
contact      contact communication type(categorical:unknown,telephone,cellular)
day          last contact day of the month(numeric)
month        last contact month of year(categorical)
duration     last contact duration,in seconds(numeric)
campaign     number of contacts performed during this campaign and for this                  client (numeric)
pdays        number of days that passed by after the client was last contacted              from a previous campaign
previous      number of contacts performed during this campaign(numeric)
previouscampaign  numeric(-1 means client was not previously contacted)
poutcome      outcome of the previous marketing                 campaign(categorical:unknown,other,failure)
deposit       has the subscribed a term deposit?categorical yes or no
