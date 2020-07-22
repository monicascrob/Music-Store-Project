# Music-Store-Project

SQL project - analyzing music store sales data
The goal for this project is help the decision makers of the store deal with their daily business questions. 

# Add new artists to the store
The Chinook record store has signed a deal with a new record label. Select the first three albums that will be added to the store out of these 4:
 - Regal/Hip-hop
 - Red Tone/Punk
 - Meteor and the Girls/Pop
 - Slim Jim Bites/Blues
The record label wants their albums to be advertised in the USA, so we will need to write a query to find out which genre sell the most tracks in the USA.

# Sales support agents' performance
Each custumer gets assigned to a sales support agent after making their first purchase. 

Analyze the purchases of customers belonging to each employee to see if one is performing better than the other.

# Analyze the sales data by country
Calculate data for each country on the total number of custumers, total value of sales, average value of sales per customer and average order value.

Use the country value from the customer table and ignore the country from the billing address in the invoice table.

Countries with only one custumer, should be grouped as "Other".

# Should the store change their purchasing strategy?
Currently, the store allows customers to either purchase a whole album or pucrhase a collection of one or more individual tracks.

The management is considering to change that strategy to save money, and purchase only the most popular tracks from each album from record companies instead of every track.

We need to find out what percentage of purchases are individual tracks vs whole albums, so they have a better understanding of the effect that this decision would have on the overall revenue.

We'll be working with a modified version of a database called Chinook. The Chinook database contains information about a fictional digital music shop - a mini-iTunes store.

The Chinook database contains information about the artists, songs, and albums from the music shop, as well as information on the shop's employees, customers, and the customers purchases. This information is contained in eleven tables:

employee
customer
invoice
invoice_line
playlist
playlist_track
track
media_type
genre
artist
album
The database schema is included in the folder under the name chinook-schema.svg.

You can check more about our database here: https://github.com/lerocha/chinook-database
