
RevPlay -- Full-Stack Music Streaming Web Application
RevPlay is a full-stack, monolithic music streaming web application that
provides music discovery, playlist management, favourites, listening
history, and artist tools through a web interface. It supports two main
roles: Listener and Artist.

The application is designed to let listeners explore music and manage
their personal libraries, while artists can maintain their profiles,
upload music, manage albums, and view engagement statistics.

Project Overview
The application uses a Spring Boot backend and a relational SQL
database. It provides REST APIs for application features and supports
role-based access for listener and artist workflows. The web application
includes an integrated music player and responsive user interface.

Features
Listener
Authentication and Profile
Register with an email address, username, and password.
Log in to an account.
View and edit profile information, including display name,
biography, and profile picture.
View account statistics such as total plays, favourite songs, and
listening time.
Music Discovery and Search
Browse the available music library.
Search for songs, artists, albums, and playlists using keywords.
Browse by categories such as genre, artist, and album.
Filter songs by genre, artist, album, or release year.
View song details, including title, artist, album, duration, genre,
and release date.
View artist profiles and album details.
Music Player and Playback
Play songs using the integrated web music player.
Use play, pause, next, previous, and seek controls.
View the currently playing song and playback progress.
Manage the playback queue.
Use repeat and shuffle modes.
Adjust playback volume.
Favourites and Playlists
Add songs to favourites and remove them.
Create, update, and delete playlists.
Set playlist visibility to public or private.
Add, remove, and reorder playlist songs.
Browse public playlists and follow or unfollow them.
Listening History
View recently played songs.
View listening history with date and time.
Clear listening history.
Artist
Artist Profile Management
Register and log in as an artist.
Create and manage an artist profile.
Add biography, genre, profile picture, and banner image.
Add social media and website links.
Preview the artist profile as listeners see it.
Music and Album Management
Upload songs with metadata and audio files.
Upload album artwork.
Create albums with a name, description, release date, and cover art.
Add songs to albums and remove songs from albums.
View and update uploaded songs and created albums.
Update song and album information.
Delete songs and albums, subject to the application's rules.
Set song visibility to public or unlisted.
Analytics and Insights
View dashboard metrics such as total songs, plays, and favourites.
View play counts for individual songs.
Sort songs by popularity.
See users who have favourited songs.
Review listening trends over time.
View top listeners.
Technology Stack
The project portfolio identifies the following technologies:

Area Technologies

Backend language Java
Backend framework Spring Boot
Database SQL
Build tool Maven
Testing JUnit 4
Logging Log4j
Version control Git

The application also includes a web frontend and an integrated web music
player. Add the exact frontend technologies and database product/version
here if they are part of this repository.

Architecture
RevPlay is described as a monolithic web application. Its backend
exposes REST APIs to support authentication, music discovery, playlists,
favourites, listening history, artist management, and analytics.

The application uses role-based access to distinguish Listener and
Artist capabilities. A relational database stores application data such
as users, music metadata, playlists, favourites, and listening activity.

Getting Started
Prerequisites
Install the tools and services required by the actual repository:

Java Development Kit (JDK) compatible with the project.
Maven.
A supported SQL database.
Git.
A web browser.
Setup
Clone the repository:

git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_DIRECTORY>
Create the application database.

Execute the database schema and seed scripts provided in the
repository, if applicable.

Configure the database connection and other environment-specific
settings in the application's configuration.

Review the Maven dependencies and build the application:

mvn clean install
Start the Spring Boot application using the command configured for
this project. For a standard Maven Spring Boot setup, this is
commonly:

mvn spring-boot:run
Open the frontend using the URL and port configured for the
application.

Configuration note: Confirm the actual Java version, database
name, configuration file, server port, frontend start command, and any
required environment variables before using these instructions. Never
commit passwords, API keys, or other secrets.

Testing
JUnit 4 is listed as the project's testing technology. Run the available
tests with:

mvn test
Add details of integration tests, test data, or any additional test
tooling only if they are present in the repository.

Documentation and Design Artifacts
The project deliverables described in the portfolio include:

Entity Relationship Diagram (ERD).
Application architecture diagram.
README documentation.
Testing artifacts.
Add links to these documents or diagrams here once they are committed to
the repository.

Project Responsibilities
The project work described in the portfolio includes:

Designing and developing a full-stack monolithic music streaming
application with Listener and Artist roles.
Implementing authentication and authorization using Spring Security,
including encrypted passwords.
Building REST APIs for music upload, playlist management,
favourites, listening history, and artist analytics.
Designing a normalized relational database schema.
Implementing multi-criteria search and filtering for songs, albums,
artists, and playlists.
Integrating a web music player with queue management, shuffle,
repeat, and playback controls.
Building responsive dashboards with music and engagement statistics.
Managing source control and project documentation.
Future Enhancements
Potential enhancements, subject to project scope, include:

Add more automated unit and integration tests.
Improve search performance and database indexing.
Expand observability and application logging.
Add deployment automation and production monitoring.
Author
Medaboina Mallikarjuna

Java Developer

Before publishing, verify that the implementation, technologies,
diagrams, endpoints, database setup, and run commands match the current
repository. Clearly identify which parts you personally implemented if
this was a collaborative project.

