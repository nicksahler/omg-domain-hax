# What is this?  
A neat github pages vulnerability (of sorts) where unclaimed, forwarded domains can be claimed by anyone on github - and then can't be claimed back (if they try, they receive an email saying "this CNAME was already claimed")

# To find vulnerable domains
I just kinda googled [this](https://www.google.com/?gws_rd=ssl#q=allintitle:%22site+not+found+%C2%B7+github+pages%22).
There are probably cooler ways, but this led me to other crawlers that found vulnerable sites. 

# What you should do

Either bother github to force domain ownership validation through TXT, or just don't leave your stuff forwarded to github without claiming it with a gh-pages CNAME thingy.

# TO DO
- a
- b
- c
