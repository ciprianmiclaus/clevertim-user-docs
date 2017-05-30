What is CSV?
============

CSV is a very common file format that is used by many systems to import and export tabular data. CSV stands for **comma separated values**.
It stores the data in a human readable text file, structuring the data into columns with headlines (e.g. like the columns you would have in a spreadsheet), with each row of data storing the values separated by commas.

Here's an example of a simple CSV file contents:

::

| Name,Age
| Alex,30
| Mary,20
| John,16
|

This file has two columns: Name and Age. It is used to hold information about people, in particular their name and their age.
As for the actual data, the file holds information about three individuals and their ages: Alex (30 years old), Mary (20 years old) and John (16 years old).

The beauty of the CSV format, and the secret for its widespread use lies in its simplicity and readability. Readability refers to being able to be read easily by humans but also, because values are separated by commas,
machines (i.e. software) can *read* (or parse) the file and easily be able to *infer* that:

* Alex, Mary, John are Names
* 30, 20, 16 are Ages
* Alex and 30 refer to the same person


