## Active Record Sinatra boilerplate

###Before (OOP app)

```
         _________________________________________________________________
        |                                                                 |
        |   3.App                  )\._.,--...,'``.                       |
        |                        /,   _.. \   _\  (`._ ,.                 |
        |                       `._.-(,_..'--(,_..'`-.;.'                 |
        |                        |    4.Router    |                       |
        |                        |________________|                       |
        |                                |                                |
        |                         _______\/_______                        |
        |     _________          |                |                       |
        |    | 1.Model |         |  5.Controller  |                       |
        |    |_________|         |________________|                       |
        |            \             /            \                         |
        |             \___________\/_        ___\/______________          |
 ___    |             |              |      |                   |         |
|CSV|<--------------->| 2.Repository |      | 6.View(puts,gets) |         |
'---'   |             |______________|      |___________________|         |
        |_________________________________________________________________|
```

###Now (ActiveRecord x Sinatra)

```
               _________________________________________________________________
              |                                                                 |
              |   Sinatra                )\._.,--...,'``.                       |
              |                        /,   _.. \   _\  (`._ ,.                 |
              |                       `._.-(,_..'--(,_..'`-.;.'                 |
              |                        |    app.rb =    |                       |                      
              |                        |    Router +    |                       |                      
              |                        |   Controller   |                       |
              |                        |________________|                       |
              |                          /            \                         |
              |              ___________\/_        ___\/______________          |
 ________     |             |              |      |                   |         |
|  DB    |<---------------->|   2.Model    |      |   6.View(html)    |         |
|  +     |    |             |______________|      |___________________|         |
|  Seed  |    |_________________________________________________________________|
'--------' 
```

### Plan:
[ ] As a user I can list all the restaurants
[ ] As a user I can see one restaurant's details
[ ] As a user I can add a restaurant