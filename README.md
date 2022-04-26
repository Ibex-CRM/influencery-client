# Welcome to the Influencery Client

The purpose of this project is to display data pulled from the Influencery API and allow users to search for influencers.... unfortunately, we messed up and the API isn't finished and we weren't able to test the search function either.

To get started;

```
# clone the repository to your local machine
# then run the following

> npm install
make sure the rails server is running on localhost:3000 before running the next command.
> npm start
> press 'y' then 'enter' and this should now be running on localhost:3001
```

You'll see that the project is not pulling in data from the API... fix the API first.

The end goal is to have a list of influencers that are being pulled from the API and have a useable search/filter that can find influencers by their name, platform and the tags they have.

1. Add the Influencers primary_tag to src/influencer/Card.js just and rename the "Tags" label "Secondary Tags" (within the FieldTitle component).
2. Connect up the search so that by typing in the searchbar you filter down the influencers (by handle, platform, and tags).
3. Connect up the dropdown so that a specific platform can be selected and influencers are filtered accordingly. (we have included some commented out code that you can use if you would like)
4. Extra points for any additional features you can add to make this a more useful project (hint. currently we are doing nothing with the influencers follower count. we also may want to prioritize primary tag matches over secondary ones).

Notes:
13 of the profile picture images are returning 404.
1 of the profile picture images is returning a 403 but I can access the url in the browser.
There is the Webpack/another bundler config. Images can be loaded from public folder for now.
