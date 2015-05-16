# JSON Airports

At [Blue Bay Travel](http://bluebaytravel.co.uk) we needed a list of Airports and their basic informations to provide autocompletion within our internal applications. We searched high and low to find something, but only had a MySQL table from somewhere, so we created this file.

The JSON file, airports.json contains an array of airports and some basic information, incliding:

- Name
- IATA (was previously named code)
- ISO code
- Continent
- Size (if known)
- Type (airport, heliport, seaboats)
- Status (0 = closed, 1 = open)

# Contributors
- José, for adding `lat` and `lon` values.

# License
MIT - [http://jbrooksuk.mit-license.org](http://jbrooksuk.mit-license.org)
