# Phoenix

Continous Integration and Playlist automation for Spotify

## Goal

Goal of this project is to automate the process of playlist management based on rules, actions and triggers like a CI does for software.

For example imagine a user that puts every track he likes into a single playlist. Over the time he puts over 10.000 tracks into this playlist and one day he decides to split it up on multiple playlists. The manual selection of tracks and moving them into a new playlist would be a cumbersome process. This is one usage example where Phoenix comes into play. It is capable of selecting tracks based on track metrics and defined rules and performes actions on them like moving.

Another example would be a user that has a fixed workflow for managing and sorting tracks into his playlist collection. He stores every track that he likes into a playlist called "Quality Assurance", once in a month he goes through this playlist, removes tracks he had skipped always and adds tracks he actively listens to into a genre specific playlist. Phoenix could automate the process by keeping track about the users playback and triggers on specific theresholds like *played 5 times in a week* an action which inserts this track into a suitable playlist.

## Features

\#\# TODO \#\#
* What about albums and interprets?
* How does the pipline work? Trigger -> Selector -> Rule -> Action ?

### Triggers

When a workflow should be executed?

* **Manual Trigger**
  
  A Workflow can be triggered manual
* **Time-Based Interval Trigger**

  Workflow can be triggerd in time-based intervals like once a day, once a week, every monday

* **Playback-Based Trigger**
  
  Playback-based trigger that executes on playback history like count of plays, play rate. Can be specified with time for example "5 plays in 5 days"

### Actions

* **Move Position in Playlist**

  Moves the track position in playlist

* **Insert into Playlist**

  Insert the track into a playlist

* **Add to Liked Songs / Library**
  
  Add to liked tracks