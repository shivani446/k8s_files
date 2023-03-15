### Podcastwala
Your very own Podcast web app built with Laravel 5. This web app enables you to manage RSS feeds for your favorite podcasts and listen to the episodes in a seamless UI. New episodes published by podcasts are automatically updated on a daily basis. Mark the items you have listened to as read and much more. 


### Features
 * Manage RSS feeds for your favorite podcasts
 * New episodes published by podcasts are updated automatically
 * Mark episodes you have listened to as read
 * Search for episodes by title and description
 * Mark all previous episodes in a podcast as read
 * Mark your favorite episodes, accessible via the ```podcast/favorites``` link

 Note: manually update new episodes by navigating to route ```podcast/auto-update```

### Install Instructions
To install Podcastwala you can clone the repository:

```
$ git clone https://github.com/modestkdr/Podcastwala.git.
```

next build the container using 

```
$ docker compose up --build 
```
now go into the container using command

```
$ docker exec -it <cotainer_id> bash
```

run the migrations:

```
$ php artisan migrate
```
 BOOM!!!!! its ready in your localhost...
### License
Podcastwala is licensed under the MIT license. If you find something wrong with the code or think it could be improved, I welcome you to create an <a href="https://github.com/modestkdr/Podcastwala/issues">issue</a> or submit a pull request!

