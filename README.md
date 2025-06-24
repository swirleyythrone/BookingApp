🎟️ Go Cinemas Booking CLI App
A Command-Line Interface (CLI) application written in Go (Golang) for booking tickets to Go Cinemas. It allows users to book movie tickets, validates user input, and simulates sending a confirmation ticket asynchronously using Goroutines.

📌 Features
✅ Book Movie Tickets

✅ Input Validation (names, email, ticket count)

✅ Display All Booked Users’ First Names

✅ Asynchronous Ticket Sending using Goroutines and WaitGroup

✅ Concurrency Handling for smooth performance

🚀 Why Go (Golang)?
⚡ Feature	🔎 Why Go?
High Performance	Compiled language → Fast execution
Concurrency	Built-in goroutines for efficient parallelism
Easy Syntax	Readable and beginner-friendly
Cross-Platform	Compile once → run anywhere (Windows, macOS, Linux)

📂 Project Structure
bash
Copy
Edit
go-cinemas-booking/
├── main.go        # Application source code
└── README.md      # Project documentation
▶️ Getting Started
✅ Prerequisites
Install Go → https://go.dev/dl/

🔧 Run the Program
bash
Copy
Edit
git clone https://github.com/yourusername/go-cinemas-booking.git
cd go-cinemas-booking
go run main.go
✨ Example Usage
sql
Copy
Edit
Welcome to Go Cinemas booking application
We have total of 50 tickets and 50 are still available.
Get your tickets here to watch your favorite movies!

Enter your first name: Aryan
Enter your last name: Sharma
Enter your email address: aryan@example.com
Enter number of tickets: 2

Thank you Aryan Sharma for booking 2 tickets. You will receive a confirmation email at aryan@example.com
⚙️ Technologies Used
Golang → CLI, concurrency, WaitGroup

fmt, time, sync packages → Core Go standard library

🗓️ To-Do / Future Improvements
 Store bookings in a persistent database (e.g., SQLite, PostgreSQL)

 Email integration for real confirmation mails

 Admin CLI to view/manage bookings

 Add cancellation or update booking features

 Seat selection feature

🛡 License
This project is licensed under the MIT License. See the LICENSE file for details.
