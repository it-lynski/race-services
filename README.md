This project pulls together a set of small services to administer a race event.

In particular the event is a sprint event with heats, e.g. quarter-, semi-finals and finals.

Pattern:
https://blog.rendle.io/doing-one-thing-with-microservices/

# Services include:
## Users
Provides a user database, and means for authorizing and validating a jwt token
https://github.com/it-lynski/sprint-users

## Race-configuration
Provides a configuration for a specific race as well as a default configuration that can be used as a template
https://github.com/it-lynski/sprint-race-config

## Athletes
Provides lists and details of all the athletes that are attending in a particular race.
https://github.com/it-lynski/sprint-athletes

## Races
Provides a list of races as well as information about every race, including
* Date and time
* Classes
* Heats
* Athletes
* Results
https://github.com/it-lynski/sprint-races

# Clients
In planning:
* web admin client
* web athlete client (responsive)

# Documentation
Check the following for adding apidoc to projects:
https://github.com/vkomulai/express-apidoc-demo
