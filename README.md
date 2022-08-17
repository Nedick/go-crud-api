# Build a CRUD API with Golang

```
                     ROUTES       FUNCTIONS      ENDPOINTS      METHODS
                
 [Database]     |-->[GET ALL]----[getMovies]---->[/movies]----->[GET]<----|
     |          |                                                         |
     X          |-->[GET BY ID]--[getMovie]----->[/movies/id]-->[GET]<----|
     |          |                                                         |  For Testing
[Movies Server]---->[CREATE]-----[createMovie]-->[/movies]----->[POST]<---|---[POSTMAN]
Localhost: 7171 |                                                         |
                |-->[UPDATE]-----[updateMovie]-->[/movies/id]-->[PUT]<----|
                |                                                         |
                |-->[DELETE]-----[deleteMovie]-->[/movies/id]-->[DELETE]<-|
```

# Requirements
- [go](https://go.dev/doc/tutorial/getting-started)
- [Gorilla Mux](https://github.com/gorilla/mux)
- [Postman](https://www.postman.com/)