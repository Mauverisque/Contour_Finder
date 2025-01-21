# Contour-Finder

This is a rich client app that:
* Detects red objects on the images
* Draws contours of the objects on a layer above the image

It allows the user to:
* Load images
* Select contours of interest
* Save them to the database
* Load previously saved contours from the database

App's GUI is created using Qt6 framework. The database used is PostgreSQL (connected via pqxx API).
