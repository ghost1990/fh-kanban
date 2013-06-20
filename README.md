# Team project 2013
Build a Swing application to manage a kanban board. This application provides the basic functionality for the kanban process.

## Maven
### Test application
```shell
mvn test
```
### Build application
```shell
mvn install
``` 
### Run application
```shell
mvn exec:java
```

## Requirements
### Testing
+ Tests for all major parts of the application
+ Application is registered at tracis-ci

### Features
+ Create new kanban boards
+ Open board
+ Save board
+ Save board as…
+ Export backlog to csv, pdf
+ Warn user if modifications have not been saved
+ Preferences dialog for colors, name of board, columns, wips
+ Classes of Service (CoS) (Fixed date, standard, intagible, expedite)
+ Cards can be created, edited and deleted
+ Card properties (uuid, headline, description, size, value, created, started, finished)
+ Validate on wip limits
+ Move cards between adjacent columns (supress invalid moves (backward, skipping columns,...))
+ Full text search backlog and board by headline, description, CoS, size, value
+ Store board as xml
+ Edit dialog for card
+ Backlogs displays cards in 3 columns grid 
+ Backlog can be sorted by creation time (default), headline, value, size
