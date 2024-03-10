# Description
This is my first project that I published in Github. I created a Youtube-Downloader App which let the user to download video from youtube based on their format choice. 
On how it works, the app will get the video information based on search query of the user and show it to the user. User can download the video with the help of yt-dlp library.
Thanks to [yt-dlp-android](https://github.com/yausername/youtubedl-android), [yt-dlp](https://github.com/yt-dlp/yt-dlp), and ytdlnis[https://github.com/deniscerri/ytdlnis] this project can be published.

#  Implemented feature
*  Search videos with query and pagination
*  Add to favorite video
*  Download video to preferred format
*  Video player to see the preview of selected video
*  List of queueing and current donwloading video
*  List of downloaded video

# Additional information
In this project I also try to implement some concept like MVVM Pattern, a singleton pattern, also a bit of clean architecture (still not clean enough, especially in the presentation layer). 

#Things to improve
There are things to improve on this project, even though this project is able to serve its purpose to download youtube video, I have yet to add many things. So here is the things that are going to be improved.
*  Add a Worker manager to let user to see download progress
*  Add a notification when changing video
*  Improve the video player especially on the design and the button functionality
*  Add a search by id and also search history.
