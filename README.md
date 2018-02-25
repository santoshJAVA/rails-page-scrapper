# page_scrapper
Scrapes a URL and stores the contents. It provides a RESTful API to index a page's content.

# Installation instructions

- git clone
- Go to root directory of page_scrapper
- `bundle install`
- Configure database.yml as per your local settings
- Create database by executing command `rake db:create`
- Perform database migrations by `rake db:migrate`
- To execute the API calls start the rails server by `rails s`

API for Scrapping new URL.
URL:
/api/v1/scrapper.json

Method:
POST

Parameters:
Name	Type	
url	  String

API for get scrapped data.
URL:
/api/v1/scrapper.json

Method:
GET

Parameters:
No Parameters Required.