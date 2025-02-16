#Add a Movie
POST /movies
Content-Type: application/json
{
  "title": "Inception",
  "genre": "Sci-Fi",
  "releaseYear": 2010
}
#Add a Review
POST /movies/1/reviews
Content-Type: application/json

{
  "reviewerName": "Pranvi",
  "comment": "Mind-blowing movie!",
  "rating": 5
}
#Update a Review
PUT /reviews/1
Content-Type: application/json

{
  "comment": "One of the best movies ever!",
  "rating": 5
}
