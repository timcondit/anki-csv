# Contributing

Contributions are welcomed and encouraged!

## Suggested pattern for adding a deck

Create a new branch under `decks`, e.g.,

    timc@Tims-MacBook-Pro ~/Z/s/a/decks> git checkout -b decks/database
    Switched to a new branch 'decks/database'

Add your files (at least the pair)

    timc@Tims-MacBook-Pro ~/Z/s/a/decks> git add database/sqlite/sqlite.csv
    timc@Tims-MacBook-Pro ~/Z/s/a/decks> git add database/sqlite/sqlite.md

Then commit and push as usual

    timc@Tims-MacBook-Pro ~/Z/s/a/decks> git commit -m "add database/sqlite"
    [decks/database 68d572a] add database/sqlite
     2 files changed, 5 insertions(+)
     create mode 100644 decks/database/sqlite/sqlite.csv
     create mode 100644 decks/database/sqlite/sqlite.md

    timc@Tims-MacBook-Pro ~/Z/s/a/decks> git push origin decks/database
