# IOT-Interfacing-LM35-sensor-to-tweet-temperature-alerts
The Project consisted of interfacing an LM35 sensor with BOLT Module to send a Tweet alert using Tweepy when a temperature crosses a threshold value.

1. You will need to have an account on Twitter Developer Platform --  https://developer.twitter.com/

2. Install the Tweepy Library:-
sudo pip3 install tweepy (Linux)
pip install tweepy (Windows)

Store all the credentials in a separate file since it is sensitive data which should not be shared with anyone. Hence it is a good practice to avoid using credentials in code directly. Also store the Bolt Device ID and Bolt Cloud API key in this file.

**Contents of conf.py file**
consumer_key = "Consumer Key (API Key) for Twitter App"
consumer_secret = "Consumer Secret (API Secret) for Twitter App"
access_token = "Access Token for Twitter App"
access_token_secret = "Access Token Secret for Twitter App"
bolt_cloud_api_key = "API key of your Bolt Cloud. You can find in API section on Bolt Cloud"
device_id = "ID of your Bolt Device"

3. Run the TempTwitter.py file.
