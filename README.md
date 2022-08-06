## Mood based clustering of songs using spotify

Everyone loves listening to music. It is far more than just a pleasant sound to the ear. The scientific reason why people love music so much is because it causes dopamine to be released from the brain. Talking about myself, just like everyone, I too like to listen to music. No matter what mood I am in, there is a song that goes with it. Whether i feel upset or want to brighten my day up, music is always there for me.

Spotify is one such platform on which you can listen to music and play millions of songs and podcasts for free. I have been using Spotify since 2-3 years now and haven't used any other platform since then. Being an avid Spotify user, one feature which I feel is lacking is Mood based Spotify playlists, where in I can just listen to songs by simply clicking on playlist related to whatever mood I am in. Thus, I tried clustering the songs according to various moods using my spotify listening data.


<img src="http://media.idownloadblog.com/wp-content/uploads/2016/06/Spotify_logo_horizontal_black.jpg" width="450" height="200">

## About Dataset
The dataset is obtained by using the Spotify API. Following steps are required to obtain the dataset. 
1.) After logging in to your spotify account, go to your profile section and click on **Privacy Setting** and then make a request to download the data.
2.) Clicking on the request button will initiate the process of data gathering. Spotify usually takes 4–5 days to email your data. 
3.) Once you receive a mail from Spotify, the contents will be in the form of zip folder, download and extract it. All of your information provided by Spotify will be in JSON format.
4.) Now the last step would be to scrape the data.
