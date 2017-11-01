# email-chooseroo

The email chooseroo is intended to replace the older mailto: functionality built into most modern browsers, but only works for a dedicated mail application installed locally. While this feature was fine when Outlook was still the main way to access web mail, most users use a web-based service like Gmail on their home desktop or laptop. Phones still use dedicated apps, so this isn't meant so much for them (but it still needs to be friendly to them!). 

# Q&A 

Q: Why?
A: I got tired of clicking an email that was supposed to be link but didn't open in my email.

Q:What's the magic behind this?
A: I wanted it to not involve server-side processing, and also be simple enough that a high-school football coach could figure it out. It uses JavaScript to *try* and look for an email on the previous page (presumably where it's located), and copy that into an email for the user. No, it doesn't yet really work. 
