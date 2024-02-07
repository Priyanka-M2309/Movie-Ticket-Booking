# Movie Ticket Booking

- The **Movie Ticket Booking** is a Python console application designed to simulate the ticket booking process for a cinema. 
- The application includes features such as displaying movie information, viewing trailers, selecting show timings, choosing seats, and making payments
  (Note : there is no API or Real Payment Process is include).

## Key Features

- **City and Movie Selection:** 
  - Users can select their city from a list of available cities.
  - The system displays a list of currently showing movies based on the selected city.
    
- **Movie Details and Trailer:**
  - Users can view detailed information about the selected movie, including ratings, duration, genre, and a brief description.
  - An option is provided to watch the movie trailer before proceeding with the booking.

- **Ticket Booking:**
  - Users can choose the show timing from available options.
  - Seat classes and their corresponding prices are displayed, and users can select the desired number of seats for booking.

- **Food Pre-Booking:**
  - Users have the option to pre-book food items from a menu.
  - The system calculates the total food bill, applies taxes, and displays the final payment details.

- **Booking Confirmation:**
  - After completing the payment, users receive a booking confirmation with details such as booking number, movie name, tickets booked, show time, screen, and payment type.

- **Additional Features:** 
  - The application utilizes the Colorama library to enhance the console output with colored text.
  - Random booking numbers are generated for each transaction to simulate real-world booking systems.

## Usage

1. Run the application.
2. Select a city, choose a movie from the available options, view movie details / Trailer (optional).
3. Select show timing, choose seat preference in available options and confirm the Booking.
4. After confirm booking, Pre-book food (optional). 
5. Make Payments and Confirm the ticket booking.

## Dependencies

The project uses the following language & libraries:

- Language: Python
- Libraries: Colorama, OpenCV (for trailer simulation), Pandas (for displaying tables)

