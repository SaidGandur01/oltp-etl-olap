# oltp-etl-olap

Step 1: Identify Key Entities
Let's identify the primary entities based on the typical content of a Spotify dataset. Common entities might include:

Songs
Artists
Albums (if album data is available)
Playlists


Step 2: Define Attributes for Each Entity
For each entity, define the attributes that are necessary. For example:

Songs
Song ID (primary key)
Song Name
Album ID (foreign key if album data is available)
Artist ID (foreign key)
Duration
Release Date
Popularity
Artists
Artist ID (primary key)
Artist Name
Albums
Album ID (primary key)
Album Name
Release Date
Playlists
Playlist ID (primary key)
Playlist Name
User ID (foreign key if user data is available)

Step 3: Determine Relationships Between Entities
A song can be in multiple playlists.
An artist can have multiple songs.
An album can have multiple songs.
A playlist can have multiple songs.
A user can have multiple playlists.

Step 4: Create SQL Statements for Table Creation