# shopify-ruby-giftbasket 

## Warning ⚠️ 

This is an outdated code example which is intended to complement [this guide](https://help.shopify.com/en/api/tutorials/build-a-shopify-app-with-ruby-and-sinatra).

If you are interested in learning how to create Shopify applications using Sinatra, please see [`shopify-basic-sinatra`](https://github.com/jamiemtdwyer/shopify-basic-sinatra).


## Getting Started
This is an example Shopify application written in Sinatra solely for the purposes of introducing new developers to the Shopify API.

This example uses a `.env` file to store the application credentials. After cloning the repository, you'll need to create a file named `.env` in the same folder. The contents of the file should be as follows:
```
API_KEY=YOUR_API_KEY
API_SECRET=YOUR_SECRET_KEY
```

where `YOUR_API_KEY` and `YOUR_SECRET_KEY` are the values of your application's API key and secret key respectively.

To get started with this example:

1. Create the `.env` file as described above.
2. `bundle install` to obtain all of the necessary dependencies
3. `ruby app.rb` to run the example application.
