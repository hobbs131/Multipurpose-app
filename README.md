# Full-stack-multipurpose-site
- Backend
  - Fully specified REST backend built with Node.js, Express.js, and MySQL
  
- Frontend
  - Multiple page application created using HTML, CSS, and JavaScript
- Deployment
  - Deployed to heroku at ths131.herokuapp.com
  - login: admin | password: admin
  
- Features:
  - User authentication (login) and logout
  - Events page
    - Table which contains information about events such as day, time, number, etc
    - Can insert events into the table through add events page
  - Add Event page
    - insert new event into database. Changes reflect on the Events page.
  - Stock page
    - Uses alphavantage API to get stock data for companies available in the dropdown list. Uses AJAX to do a GET request ot the TIME_SERIES_DAILY endpoint of the alphavantage API.
  - Admin page
    - Add users
    - Delete users
    - Update user name/password