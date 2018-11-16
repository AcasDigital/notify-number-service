# notify-number-service
A simple single php file to serve a Notification Reference number via REST

The database is the main Aurora production cluster

The database connection is performed by an inlude file located in /home/ubuntu/database.inc

# URL query parameters:

data=1: Return the contents of the number table

save=[DATA]: Saves the data to the number table


# Return a number

t=individual or t=group

s=service eg s=dev=tell.acas.org.uk

Example: http://52.49.126.109?s=dev-tell.acas.org.uk&t=individual
