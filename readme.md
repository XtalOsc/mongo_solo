Prime Mongo Shell Peer Challenge
=================================

Now that you've learned some of the basics of querying MongoDB via the mongo shell, use that information to query a collection of bios. Remember to switch off with your partner half-way through this exercise.

Check out these docs for more advanced find queries https://docs.mongodb.org/getting-started/shell/query/#specify-conditions-with-operators

Instructions
------------
Setup
------

* Load the data using this command `mongoimport --db challenge --collection bios --drop --file bios.json`
* Start the Mongo shell with mongo.
* Connect to the challenge database using the mongo shell command use challenge

Queries
-------

Create a file, queries.js that will contain the queries that correctly address the criteria in the steps that follow.

* Find documents that have awards.
* Find documents that don't have awards.
* Find documents that have contribs for OOP or UNIX.
* Find documents with "Turing Award" awards.
* Find documents with IDs between 3 and 7.
* Find documents with awards that were awarded before the year 2000.
* Find documents with birth dates, but no death dates.
