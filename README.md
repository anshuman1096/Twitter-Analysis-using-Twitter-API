# Twitter-Analysis-using-Twitter-API
Fetching trending tweets for Pune,India region using WhereOnEarth ID and twitter API

# Twitter API Access

Twitter implements OAuth 1.0A as its standard authentication mechanism, and in order to use it to make requests to Twitter's API, you'll need to go to https://dev.twitter.com/apps and create a sample application.

Choose any name for your application, write a description and use `http://google.com` for the website.

Under **Key and Access Tokens**, there are four primary identifiers you'll need to note for an OAuth 1.0A workflow: 
* consumer key, 
* consumer secret, 
* access token, and 
* access token secret (Click on Create Access Token to create those).

Note that you will need an ordinary Twitter account in order to login, create an app, and get these credentials.
The first time you execute the notebook, add all credentials so that you can save them in the `pkl` file, then you can remove the secret keys from the notebook because they will just be loaded from the `pkl` file.

The `pkl` file contains sensitive information that can be used to take control of your twitter acccount, **do not share it**.

# Screenshots
![Twitter trends](https://user-images.githubusercontent.com/47148773/55680868-131c2700-593d-11e9-8392-dc65a5134211.JPG)

![trends formatted](https://user-images.githubusercontent.com/47148773/55680881-43fc5c00-593d-11e9-8570-77671f80c27d.JPG)
