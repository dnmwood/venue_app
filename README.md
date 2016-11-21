MVP: 
index page with list of venues
as a user access a venue page via homepage
as a user see what time shows are starting
where they're starting
how much a show costs at the door
see what bands are playing at each event

Backlog:
as a user i can see photos
as a user i can see venue reviews
option to buy ticket


```
+-----------------------------------------+
|                                         |                        +------------------------------------+
|                                         |                        |                                    |
|                   Venue                 |                        |                                    |
|                                         |                        |                                    |
|                                         |                        |                                    |
|                                         |                        |                                    |
|                                         |                        |                                    |
|                                         |                        |           Bands                    |
|                                         |              +--------^+                                    |
|                                         |              |         |                                    |
+--+-------------------------+------------+              |         |                                    |
   | has many                |            ^              |         +---+------------------------+-------+
   |                         |            |              |             |            has many    |
   |                         |            |              |             |                        |
   |                         |            |              |             |                        |
   |                         |            |              |             |                        |
   |                         | belongs to |              |  belongs to |                        |
   |                         |            |              |             |                        |
   |                +--------v------------+--------------+-------------v+                       |
   |                |                                                   |                       |
   |                |                                                  <------------------------+
   +---------------^+                                                   |
                    |                Shows                              |
                    |                                                   |
                    +---------------------------------------------------+
```