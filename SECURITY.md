Hi,

While reviewing public GitHub repositories, I noticed that your repository appears to contain an email address and what looks like a Gmail App Password in source code.

Repository:
(https://github.com/garimacodes/Cold_Email_Automation/blob/7ad1fc8f9a5be32298131885c1d21cd8a260bb9a/Cold_Email_Automation.ipynb#L832)



Example (partially redacted):
EMAIL_ADDRESS = ********@gmail.com
EMAIL_PASSWORD = ********

If this credential is still active, I recommend:

1. Immediately revoking/rotating the App Password.
2. Removing the secret from the repository.
3. Rewriting Git history if the credential has been committed previously.
4. Moving secrets to environment variables or a secrets manager.

I'm sharing this through a pull request because I could not find a dedicated security contact method. I have not attempted to access the account or perform any unauthorized actions.

Regards,
Er. Amarendra Prakash
