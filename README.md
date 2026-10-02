# Movie Theater Ticket Kiosk

This is a small practice project for my software engineering course. It models a self-service kiosk in a movie theater where a customer can look at the movies and showtimes, pick an open seat, pay for a ticket, and get a confirmation. The one rule the kiosk has to enforce is that the same seat can never be sold twice.

No code is written here. The repo is only used to practice GitHub, issue tracking, project boards, and UML diagrams in diagrams.net.

## Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The kiosk is on and showing the list of movies and showtimes, and the chosen showtime still has at least one open seat.

**Main Steps:**
1. The customer picks a movie and a showtime from the list.
2. The kiosk shows the seats for that showtime and marks which ones are open.
3. The customer selects an open seat.
4. The kiosk checks that the seat has not been sold yet and holds it for this customer.
5. The kiosk asks for payment and the customer pays.
6. The system confirms the payment went through.
7. The system creates the ticket and marks the seat as sold.
8. The kiosk shows a confirmation with the movie, showtime, and seat.

**Postcondition:** The customer has a confirmed ticket and the seat is marked as sold, so it cannot be bought again.
