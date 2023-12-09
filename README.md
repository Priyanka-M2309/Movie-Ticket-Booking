# Movie Ticket Booking

- The Movie Ticket Booking System is a Python console application designed to simulate the ticket booking process for a cinema. 
- The system allows users to select a city, choose a movie from the available options, view movie details, and book tickets.
- It also provides the option to pre-book food along with the ticket.
- The application includes features such as displaying movie information, viewing trailers, selecting show timings, choosing seats, and making payments (Note : there is no API or Real Payment Process is include).

# Key Features:

1. City and Movie Selection:
       - Users can select their city from a list of available cities.
       - The system displays a list of currently showing movies based on the selected city.

2. Movie Details and Trailer:
       - Users can view detailed information about the selected movie, including ratings, duration, genre, and a brief description.
       - An option is provided to watch the movie trailer before proceeding with the booking.

3. Ticket Booking:
      - Users can choose the show timing from available options.
      - Seat classes and their corresponding prices are displayed, and users can select the desired number of seats for booking.

4. Food Pre-Booking:
      - Users have the option to pre-book food items from a menu.
      - The system calculates the total food bill, applies taxes, and displays the final payment details.

5. Booking Confirmation:
      - After completing the payment, users receive a booking confirmation with details such as booking number, movie name, tickets booked, show time, screen, and payment type.

6. Additional Features:
      - The application utilizes the Colorama library to enhance the console output with colored text.
      - Random booking numbers are generated for each transaction to simulate real-world booking systems.

# Technologies Used:
  - Language: Python
  - Libraries: Colorama, OpenCV (for trailer simulation), Pandas (for displaying tables)


# Notes:
- The project is structured with a Movie_ticket class, making it modular and easy to extend with additional movies or features.
- The project showcases usage of libraries for colorful console output and tabular data representation.




