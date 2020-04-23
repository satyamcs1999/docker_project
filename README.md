It is a Docker-based project that uses the concept of Infrastructure as a Code that could be implemented using Docker-Compose by using ".yml/.yaml" file. It uses PAT(Port Address Translation) for outside accessibility (LAN Network)and usage of Volume for permanent storage of data that includes login details etc.

It requires Docker images for setup i.e.for frontend, "ownCloud" is used and "MariaDB" database for storage of data. The infrastructure created can be launched using "docker-compose up".

ownCloud is a self-hosted open source file sync and share server. Like Dropbox, Google Drive, Box, and others, ownCloud lets you access your files, calendar, contacts, and other data.

Version used:
 ownCloud : 10.0-apache
 MariaDB  : 10.5
 Docker-Compose : 3
