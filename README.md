# spotifyDataAnalysis
Collection of Jupyter notebooks for analysing spotify data

# Spotify Data
1. Go to [privacy settings](https://www.spotify.com/uk/account/privacy/) in your spotify account
2. Download your data (bottom of the page). It should contain about 1 year worth of data, spotify doesn't seem to llow to download more than that...
3. Wait for the email from spotify, in my case it took about 3 days.
4. Your streaming history will be available in JSON format, in 1 or more files, depending on how many tracks you have listened to.

# Spotify Credentials
You can follow the first few steps in the spotify [Web API Tutorial](https://developer.spotify.com/documentation/web-api/quick-start/). After that you should have your spotify ID and secret available. This is requried to fetch additional track information.

# Dependencies between notebooks
`GenerateData.ipynb` has to be run before any other notebooks, as it will generate a `pkl` file with a pandas dataframe with your data, which will tehn be used for data visualisation purposes.
