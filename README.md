# CS50-Commerce

## Table of contents
- [Description and requirements](#description-and-requirements)
- [Preview](#preview)
- [Installation](#installation)

## Description and requirements
Design an eBay-like e-commerce auction site that will allow users to post auction listings, place bids on listings, comment on those listings, and add listings to a “watchlist.”

All requirements can be viewed here: https://cs50.harvard.edu/web/2020/projects/2/commerce/

## Installation
To set up this project on your computer:
1. Download this project
    ```
    gti clone https://github.com/kevogaba/commerce.git
    ```
2. Install all necessary dependencies
    ```
    pip install -r requirements.txt
    ```
3. Make migrations
    ```
    python manage.py makemigrations
    ```
4. Migrate
    ```
    python manage.py migrate
    ```

---
NOTE: Working on deployment to Heroku
