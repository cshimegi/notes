# How to diagnose if an api response is slow?

- check if the api is really slow by another tools like postman
- check if the problem is at browser
- check if the problem is at service
- guess the possible where the problem happens
- add logs to trace why the problem happens


# How to diagnose if a SQL response is slow?
- compare ideal execution time with actual one and check if the SQL is really bad with performance by DB tools like exection plan
- compare another SQL approach with current one
- if the problem is not at DB, check if the problem is somewhere at service that deals with SQL process
- guess the possible cause
- add logs to trace why it happens