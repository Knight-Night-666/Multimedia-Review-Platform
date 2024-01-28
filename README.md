# Movie Review Platform

This is a full-stack web application that allows users to browse movies, watch trailers, publish text reviews, and read reviews written by others. 

## Features

- Browse movie catalog with details like title, genre, release year, etc.
- Play movie trailers and teasers embedded from YouTube
- Publish text reviews on movies and rate them on a 5-star scale 
- Like/dislike reviews written by other members
- View ratings and read reviews published for movies
- RESTful APIs for movie and review management operations

## Tech Stack

**Frontend:** ReactJS 

**Backend:** Spring Boot 

**Database:** MongoDB

## API Reference

Base URL: `https://api.movie-reviews.com/`

**Movies**  

Get all movies  
`GET /api/v1/movies`

Get single movie 

`GET /api/v1/movies/:movieId`

**Reviews**

Publish review   
`POST /api/v1/reviews`

## Deployment

Automated using a CI/CD pipeline with:

- Version Control: Git, GitHub
- Build & Test: Maven, JUnit  
- Containerization: Docker
- Orchestration: Docker Compose
- Configuration Management: Ansible

## License

This project is licensed under the MIT license - see [LICENSE](LICENSE) file for details.

## Contributors

- [Prakhar Rastogi](https://github.com/Knight-Night-666)
- [Shreyansh Rai](https://github.com/shreyanshrai)
