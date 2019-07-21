# tumblrConsumer
tumblr consumer of my all personal data to be processed and classified.

## details

- retrieves my whole tumblr data from beginning to date, 
- process and prune it and save 
- while doing this provide monitor(with resume, delay kinds of functionalities) with a dashboard which will basically contains a progress bar and detail widgets.

## tech stack 

1. Uses websocket to send the record bundle which sized 20 per request to the client so not using long polling or subsequent ajax calls
2. Spring boot, rest, jpa hibernate for backend and a mysql db
3. `Flyway` migrations and also hibernate ddl autocreation and seeding/loading initial data
4. will use LDA for topic modeling probably implemented in Python.
