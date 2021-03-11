# BoostMeNot
BoostMeNot is an addon designed purely for cleaning up your trade chat of all the spam that is people selling boosts. While trying to sell in Trade chat it became unbearable to try and scour through and see actual people buying and selling when all I could see was message upon message of people selling boosts. This is the solution to that problem.

It works on the same principles as an email spam filter, keywords with a weight assigned to them and any messages that go over a certain threshold are hidden from view. From testing this with a friend it drastically cleaned up Trade chat while still preserving messages I would actually want to see.
The threshold is configurable from the AddOn options page and anyone can add or remove keywords via the Blacklist.lua file.

# Options
![image](https://user-images.githubusercontent.com/16262127/110866325-e311f700-82bc-11eb-8f75-8d5f69472274.png)

In the options you can enable and disable the AddOn, change the threshold and also turn on developer mode.

Developer mode allows you to see all messages and what theyve been rated, messages are in the format [Channel][Name][Rating] Message
You can also toggle this so it only shows message that pass your current threshold.

![image](https://user-images.githubusercontent.com/16262127/110866758-8c58ed00-82bd-11eb-8957-4bf6bba21d09.png)
