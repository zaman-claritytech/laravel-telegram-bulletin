# laravel-telegram-bulletin
A prototype to create an automatic news feed for users in Telegram

## Requirements:
- users should be able to see and read content from sample data
  - sample data should be in rss/json format
  - sample rss: https://cointelegraph.com/rss
  - sample json: https://jsonplaceholder.typicode.com/posts
- owners can configure and aggregate different data sources
  - other sample rss: https://www.coindesk.com/arc/outboundfeeds/rss
  - other sample json: https://jsonplaceholder.typicode.com/comments
- cleaning up telegram feed if 
- owners should be able to create their own content and blast to all users using the bot
  - can be in rss/json
- owners can do selective blast by categories or unique user id
- owners should be able to schedule the content publishing
- owners can manage a feed via web interface
