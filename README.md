# MovieNest OTT Platform

MovieNest is a modern, responsive single-page web application that serves as an Over-The-Top (OTT) streaming platform interface. It is designed to be hosted on AWS (Amazon EC2) with static assets like movie posters and trailers securely stored in Amazon S3. 

*Note: This repository marks the starting project of my AWS cloud computing journey.*

## Features
- **AWS Integration:** Media files (posters and trailers) are served directly from an Amazon S3 bucket, with the application hosted on an Amazon EC2 instance.
- **Responsive UI:** Clean, dark-themed UI that mimics premium streaming services.
- **Search Functionality:** Real-time search to instantly filter available movies.
- **My List:** Add or remove movies to your favorites with a dynamic counter.
- **Interactive Ratings:** Rate movies directly on the card with a 5-star interactive rating system.

## Project Structure
```text
MovieNest-OTT-Platform/
│
├── MovieNest.html                       # The main single-page application (HTML/CSS/JS)
├── MovieNest_Demo.mp4                   # Full video demonstration of the project
├── README.md                            # Project documentation
│
├── Demo Screenshots/                    # UI screenshots of the web app
│   ├── Front_Web.png
│   ├── Front_Web2.png
│   └── Searching Movie.png
│
├── Sample Posters and Trailer/          # Local copies of media files (hosted on S3)
│   ├── mv1.jpg, mv1.mp4                 # Movie 1 assets
│   ├── mv2.jpg, mv2.mp4                 # Movie 2 assets
│   ├── mv3.jpg, mv3.mp4                 # Movie 3 assets
│   └── mv4.jpg, mv4.mp4                 # Movie 4 assets
│
└── screenshots/                         # AWS architecture & implementation screenshots
    ├── EC2 Instance.png
    └── S3 Bucket(Store Posters and Trailer.mp4).png
```

## Future Enhancements
- Integration of a database like DynamoDB to store user preferences and ratings.
- Expanding the frontend logic for user profiles and continuous playback.
