# ONLINE-MUSIC-PLATFORM-
🎶 Online Music Platform (Java)

The Online Music Platform is a Java-based application that simulates a simple digital music service.
It demonstrates strong usage of Object-Oriented Programming (OOP) principles and the Java Collection Framework to efficiently manage songs, playlists, and user accounts.

This project is designed to showcase real-world software development concepts, making it ideal for learning, portfolio inclusion, or academic submissions.

🌟 Key Highlights
🧱 Complete OOP Implementation

The platform is built using all core OOP concepts:

Encapsulation:
All class fields (song details, user data, playlist content) are privately stored with controlled access through getters and setters.

Inheritance:
Common media behavior is implemented in a base class like Media, with child classes such as Song, Podcast, or Instrumental.

Polymorphism:
Media items implement a play() method that behaves differently depending on the media type.

Abstraction:
Abstract classes or interfaces like Playable define the essential actions for audio objects.

📚 Use of Java Collection Framework

The project uses multiple collection types to manage data effectively:

ArrayList → Stores songs, playlists, and user collections.

HashMap → Maps user IDs to user accounts, song IDs to song objects, etc.

HashSet → Handles unique genres, liked songs, or tags.

Collections make searching, adding, and organizing content fast and efficient.

🎧 Platform Functionalities
✔ User Operations

Create an account and maintain a personal music library

Browse the complete list of songs

Search songs by title, artist, genre, or album

Like or unlike music

View listening history (if implemented)

✔ Playlist Management

Create multiple playlists

Add or remove songs from playlists

View playlist details

Play entire playlists sequentially

✔ Playback Simulation

Use polymorphism to simulate playing different media types

Display song details while playing

🛠 Technologies Used

Java

OOP Concepts (Inheritance, Encapsulation, Polymorphism, Abstraction)

Collection Framework (ArrayList, HashMap, HashSet)

Modular and maintainable class architecture

📂 Project Structure (Example)
/src
   /model
      Song.java
      Podcast.java
      Media.java
      Artist.java
      Playlist.java
      User.java
   /service
      MusicLibrary.java
      PlaylistService.java
      UserService.java
   /main
      Main.java

🎯 Purpose of Project

This project is ideal for:

Learning advanced Java programming

Understanding how to structure large OOP applications

Demonstrating portfolio-level Java skills

Academic submissions and practical lab projects
