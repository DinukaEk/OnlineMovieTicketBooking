# 🎬 Online Movie Ticket Booking

A web application to browse movie listings, select showtimes, choose seats, and book tickets online. Built with [Your Technology Stack].

## 🚀 Key Features

- 🧑‍💻 **User Authentication**  
  Users can register, log in, and view booking history.

- 🎥 **Movie Browsing & Showtime Selection**  
  Browse available movies and showtimes by theatre.

- 💺 **Seat Selection**  
  Interactive seat map to choose preferred seats.

- 🧾 **Booking & Payment**  
  Reserve tickets and simulate payment.

- 👤 **Admin Dashboard**  
  Admins can manage movies, shows, and theatres, and view all bookings.

## 🧩 Tech Stack

- **Backend**: [Flask / Node.js / Django / ASP.NET / PHP] (update as applicable)  
- **Database**: [MySQL / PostgreSQL / MongoDB / SQL Server]  
- **Frontend**: HTML, CSS (Bootstrap), JavaScript  
- **Others**: Any additional libraries or tools you used

## 🛠️ Prerequisites

- [Technology runtime] (e.g., Python 3.x, Node.js, PHP, .NET)  
- Database installed and running (e.g., MySQL, PostgreSQL)  
- Optional: XAMPP, WAMP, or server stack for PHP versions

## 🔧 Installation & Setup

1. **Clone the repo**  
   ```bash
   git clone https://github.com/DinukaEk/OnlineMovieTicketBooking.git
   cd OnlineMovieTicketBooking
   ```

2. **Install backend dependencies**
   ```bash
     # Example for Python:
    pip install -r requirements.txt
    # Node.js example:
    npm install
   ```

3. **Configure environment/database**

- Create a database (e.g., movie_booking_db)
- Update the config file (.env or config.php) with DB credentials

4. **Import database schema**
   ```bash
     # For MySQL
     mysql -u user -p movie_booking_db < schema.sql
   ```

5. **Run the application**
   ```bash
     # Python:
     python app.py
     # Node.js:
     npm start
     # PHP (via XAMPP/WAMP):
     Place in `htdocs`, start Apache/MySQL, visit localhost
   ```

6. **Access in browser**
   Visit http://localhost:PORT/ (e.g., :3000, :8000, or default server port)


🗂️ Project Structure
```
OnlineMovieTicketBooking/
├── server/                  # Backend source files
├── public/                  # Frontend files (HTML, CSS, JS)
├── database/                # SQL schema or seed scripts
├── .env                     # Configuration file (contains DB credentials)
├── README.md                # Project documentation
└── package.json             # (or requirements.txt, composer.json, etc.)
```

📋 Usage

1. Register or log in as a user.
2. Browse movies and showtimes.
3. Select desired seats on the seat map.
4. Complete a booking and payment simulation.
5. View your booking history under “My Bookings”.

Admins can log in with the admin account and manage listings.

🔮 Future Enhancements
- Integrate with a real payment gateway (Stripe / PayPal)
- Implement seat availability concurrency control
- Email booking confirmation
- Add user reviews/ratings, search, and filter features
- Mobile responsive UI

✅ Contributing
- Contributions are very welcome!
- Fork the repo
- Create a feature branch: git checkout -b feature-name
- Commit your changes: git commit -m "Add new feature"
- Push branch: git push origin feature-name
- Submit a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more details.
