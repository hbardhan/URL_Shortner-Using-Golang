URL Shortener 🔗🚀
A simple and efficient URL shortener built using Golang. This project allows users to shorten long URLs into concise, easy-to-share links.

Features
✅ Generate short URLs for long links
✅ Store and retrieve shortened URLs efficiently
✅ Redirect users to the original URL when accessing the short link
✅ RESTful API for easy integration
✅ Optimized performance with Golang

Tech Stack
Backend: Golang
Database: (Mention if you're using SQLite, PostgreSQL, Redis, or any other storage)
Frameworks/Libraries: (List any Golang packages like gorilla/mux, gin-gonic/gin, etc.)
Installation & Setup
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
Install dependencies:
bash
Copy
Edit
go mod tidy
Run the application:
bash
Copy
Edit
go run main.go
API Endpoints
Shorten URL
POST /shorten

Request
json
Copy
Edit
{
  "url": "https://example.com/long-url"
}
Response
json
Copy
Edit
{
  "shortened_url": "http://localhost:8080/abc123"
}
Redirect to Original URL
GET /{short_code}
Redirects to the original URL if the short code exists.

Contribution
Feel free to contribute by submitting issues or pull requests!

License
This project is licensed under the MIT License.
