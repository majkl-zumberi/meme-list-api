# meme-Json-rest-api
url for access REST api: http://my-json-server.typicode.com/majkl-zumberi/meme-list-api

You can use GET, POST, PUT, PATCH and DELETE. Changes aren't persisted between calls.

# GET ENTIRE DB
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/db

# GET SINGLE MEME (id)
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes/1

# GET ALL MEMES
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes

# FILTER MEMES BY GENRE
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes?subreddit=dankmemes

# PAGINATION & LIMIT 
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes?_page=1&_limit=5

# SORTING
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes?_sort=title&_order=asc

# GLOBAL SEARCH
http://my-json-server.typicode.com/majkl-zumberi/meme-list-api/memes?q=fact
