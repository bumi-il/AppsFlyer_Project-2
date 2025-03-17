
# 2️⃣ Request Structure

## 2.1 - Input Parameters
Parameter :            Description 
---------------------------------------------------------------------------		                              
`description` :        The ticket description as written by the user.      
`current_categories` : The currently assigned categories (comma-separated).
`categories_bank` :    The list of available categories (comma-separated). 
`articles_bank` :      The list of available articles (separated by `~~~`).

## 2.2 - Example Request
```
description        = I can't log into Okta. I am certain the password is correct.  
current_categories = General IT Issue, Okta 
categories_bank    = General IT Issue, Okta, Login Issues - Okta, Hardware Issues - Laptop, Software Issues - VPN  
articles_bank      = Okta Login Troubleshooting article content here ~~~ 
```
