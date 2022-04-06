# Auto-Signup
The Auto Signup Project for Spamming (Not actually to be used)

The idea came to me from a buddy I met traveling in Colombia. He had a bad experience with a tour company who took a lot of money from him and gave him poor service.
In an act of revenge, he decided to create an Excel Macro that would send requests for information to the company's site. I told him i could expound on that by creating
a script in python that would create random email addresses but in a way that seemed more natural than just replacing one or two characters. 
The idea is to use one of several email address configurations in order for the spam bot to be submitting realistic looking names infinitly. 

I must express that this is all experimental and I have no intention of using this code for nefarious purposes.


Components of the code:

1: Random name generation - Using packages in python get a randomized first and last name
2: Email Domain names - The ideas is not to use just one email domain, but many email domains (yahoo, google, hotmail, icloud, ect.)
3. Concatination and configuration - Create several configurations of email generation using:
 -1. A first name or part of a first name
 -2. A delimiter
 -3. A last name or a part of a last name
 -4. a domain name
4: Randomization - randomize selecting a configuration to be used in the fourm submission
5: Access and submit - Accessing the site and navigating to the submission field, submitting the email address and hitting enter
