KarmaVille
===============

A skeleton was given to us with a massive seed file with Users and their KarmaPoints. Users had many karma points, with over 1 million KarmaPoints in the database and each with a user_id. Before each view was rendered, EACH USER'S KarmaPoint total was calculated, making the load time long. Our job was to make the load time reduce by 80% by working ONLY with the database and the models (couldn't change view or controllers). We also had to ensure all of our RSpec tests continued to pass without modifications.

This was completed during Phase3. 

#### Created: 
Monday, October 14th 2013 (Week 8 of Dev Bootcamp)

#### Contributers/Pairing Partners: 
Ryan Menzer, Kevin Berry

#### Purpose: 
This app was to show that database structure and load times are important. It allowed us to see the value of indexing specific columns and adding table columns through migrations in order to improve the speed and load time of the database query. It also taught us that it is important to only request the data that is needed with specific ActiveRecord commands (pluck, select, etc.) instead of making requests for all the data and then parsing out what you need afterwards with Ruby. We were instructed not to use caching (redis, memecaches, fragcaching).

#### Focussed Skills:
  - PostgreSQL
  - Ruby
  - Rails
  - ActiveRecord
  - RSpec
