# Who's the Heaviest?

# Backstory
I recently finished a data science program, and I've been working with some individuals on starting some new projects. However, I always wanted to do something smaller in scale to practice on my own.<br>I play a game called *league of Legends* with some buddies from high school. To explain it simple, it pits two teams of 5 against each other, with the goal of destroying the enemy base. Our friends always joke about who is the main factor in our loses, or in other words, who is the <ins>**heaviest**</ins>. I realized recently that I have the skillset to find the actual answer to that!

# The Project
I'll be using Riot Game's API to grab data regarding the games I've played with my friends. From there, I have different  plans on what I'll do with the data
- General analysis, including my win rate on my own and my winrate with different combinations of friends (currently here)
- ~~More in-depth analysis, determining with what type of characters do we struggle with, and what characters work best for us~~ Update: After looking at the inital data, there might not be enough data to make that work for all of us. Instead, I'll do it based on only myself instead.
- A predictive model that determines whether or not we'll win a match based on the characters/ types of characters that we are playing as and playing against

Later on down the road, I'm considering  the idea of making a website that can allow anyone do have the same analysis done for them and their friends.

## Update: April 26th
As I've mentioned up above, there isn't enough data to do the type of analysis I would have liked, so I'll be pivoting it so that the analysis is focused on myself instead.
Also, I'm currently trying to find a way to:
- get new match data automatically and either save it as a JSON file or store it in a databse
- have the analysis and future predictive model update automatically with the new data
- create a dashboard with that predictive analysis OR have it create an updated datafolio whenver new data is recieved.

This is all new to me, so this might take a bit longer than I'd like. If you have any hints of how to achieve this, or know of tools that could help, feel free to send me a message!
