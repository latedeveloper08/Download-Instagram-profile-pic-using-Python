# Download-Instagram-profile-pic-using-Python
Instagram is a photo and video-sharing social networking service owned by Facebook, Python provides powerful tools for web scraping of Instagram. In this repository I will be providing the python code for downloading the profile picture in instagram.
This code creates an instance of instaloader.Instaloader() and then uses the download_profilepic() method to download the profile picture of the given Instagram username. The downloaded image will be saved with the name specified by the username variable.


# Requirements
#requests:

pip install requests

#concept:

For a given user profile, open view-source and find “profile_pic_url_hd” . To find press ctrl+f and type “profile_pic_url_hd” the link with it is our data or profile pic. 
The link will look like : 
 

https://scontent-bom1-1.cdninstagram.com/vp/d2df9b2d162969e87200984ee763cc27/5DC590F2/t51.2885-19/s320x320/61851740_845288152518430_7068999703693623296_n.jpg?_nc_ht=scontent-bom1-1.cdninstagram.com


Make sure you have installed the instaloader library using pip install instaloader before running the code. Also, replace "example_username" with the actual Instagram username from which you want to download the profile picture.

