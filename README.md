Overview
This Java application allows users to view, search, add, and delete movie summaries stored in an Oracle database. Users can also view details about each movie, including its title, genre, release date, summary, and an associated image. The application features a graphical user interface (GUI) built using Java Swing.

Features
User Authentication: Users must log in with a valid username and password to access the application.

Movie Search: Users can search for movies by title.

Add Movies: Users can add new movies to the database by providing details such as title, genre, release date, summary, and an optional image URL.

View Movie Details: Users can view detailed information about each movie, including its genre, summary, and an associated image.

Delete Movies: Users can delete movies from the database.

Dynamic UI: The application features a gradient background and dynamic loading of movie images from URLs.

Prerequisites
Before running the application, ensure you have the following installed:

Java Development Kit (JDK): Version 8 or higher.

Oracle Database: The application connects to an Oracle database. Ensure you have the necessary credentials and the database is running.

Oracle JDBC Driver: The ojdbc driver must be included in your project's classpath.
Usage
Login:

Enter the username and password to log in. The default credentials are:

Username: loginpage

Password: 123

View Movies:

After logging in, the application will display a list of movies from the database.

Search Movies:

Enter a search term in the search bar and click the "Search" button to filter movies by title.

Add a Movie:

Click the "Add" button and fill in the required details to add a new movie to the database.

Delete a Movie:

View the details of a movie and click the "Delete" button to remove it from the database.

Code Structure
Movie.java: The main class containing the GUI and database interaction logic.

Gradient Background: The background of the login panel is rendered using a gradient paint.



Dynamic Image Loading: Movie images are loaded from URLs provided in the database.

Dependencies
Java Swing: Used for building the graphical user interface.

Oracle JDBC Driver: Used for connecting to the Oracle database.


License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Thanks to Oracle for providing the JDBC driver.

Thanks to the Java Swing team for the GUI framework.
