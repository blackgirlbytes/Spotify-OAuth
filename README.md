# Spotify OAuth API
For a class assignment, my task was to use an OAuth API using the jQuery AJAX calls. I used Spotify's API to retrieve user profile information. 

![spotify](https://user-images.githubusercontent.com/22990146/36953385-41a04294-1fe8-11e8-9684-cd3c55094218.png)
Link to project: http://recruiters-love-seeing-live-demos.com/

alt tag

How It's Made:
Tech used: HTML, CSS,JavaScript, jQuery, AJAX 

I kept this application simple because the point was to showcase my API troubleshooting skills. In HTML, I had one heading 1, two buttons, one empty image tag, and one empty heading 2 tag. In my CSS, I used Oswald font and green background I found from flat UI color picker. Following that, I went to my Javascript file, and I read the documentation necessary to learn Spotify's API.This is where it got tricky.I put a link that had the authorization endpoint for the user in my button tag. If my user successfully logged in, the link would redirect my user back to my site and provide my user with an access token. In the javascript, I did a click function, so that when I clicked the second button, it would send the access token to the server, and the server would come back with information about the user. The information I received had the user email, number followers, country, and display name.

Optimizations

Because this was a quick homework assignment, I did not get to do all that I wanted. The styling is poor. I would definitely center everything and improve the UI. Additionally, if I had more time, I would use a cooler endpoint to uncover more interesting information like playlists or recommended songs for the user. 

Lessons Learned:
I learned about using headers. I spent about one whole day trying figure out how to use OAuth APIs, learning how to understand documentation, which was definitely a feat. It was very interesting to learn how 
headers: {
       'Authorization': 'Bearer ' + accessToken works
It was also interesting to learn that there was a way target the address bar using the built in objects and properties called windows.location.hash 
