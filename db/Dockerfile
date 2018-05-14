# What we do here: We use the official Postgre docker image and extend it.
# We then add a sql file to the entrypoint provided by the image.
# This entrypoint gets executed on init.

FROM postgres

# Create the db on init of the container.
ADD create.sql /docker-entrypoint-initdb.d
