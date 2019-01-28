
# RU OK
Mental health app to check in and track your sentiments daily. Identify those times when you're consistently feeling down and do something about it. Resources are available to vent and seek help during the darkest of times. Be heard. Feel better.

# TEAM
Solomon
Giselle

Dr. FeelGood Inc.'s mission is to provide an easy to access starting point for mindfulness. We lay out some simple tools for staying on track in that tunnel called life, and gently steering towards that light at the end of it.

# TECH


## Starting the app locally

Start by installing front and backend dependencies. While in this directory, run the following commands:

```
yarn install
cd client
yarn install
cd ..
``

After both installations complete, run the following command in your terminal:

```
yarn start
```

That's it, your app should be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.

## Deployment (Heroku)

After confirming that you have an up to date git repository and a Heroku app created, complete the following:

1. Build the React app for production by running the following command:

```
yarn build
```
> Note: A yarn build will be required to register any new Post requests from any front-end JavaScript to to prevent any proxy server errors.

2. Add and commit all changes to git

3. Push to Heroku

If all previous steps were followed correctly, your application should be deployed to Heroku!

