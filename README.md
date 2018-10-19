# README

These are CSV files for Anki. Getting data in and out via the Anki application is inefficient, tracking changes even more so. Anki imports from and exports to CSV, so both problems are easily solved.

Each subdirectory contains the CSV and header file for a deck. The header file is for reference only--Anki doesn't use it. The default deck type is Basic, with two fields: Front and Back. The type for any deck is described in the header file.

Regardless of the type of deck, the steps should be the same for the first import.

## Organization

Subdirectories correspond to sub-decks. For example, `linux/lvm` would look like this in `Anki`:

    ```text
    - linux
        lvm
    ```

## Importing a tab-separated deck

    File > Import ...
        find your CSV file
        choose it > Ok
    on the Import dialog,
        check the Type
        if you're not using it, leave the `Deck` as `Default` for now
        `Fields separated by:` should be set to `Tab`
            this should already be set, if the file uses tabs
        check the `Field mapping` looks correct then Import

## Importing a comma-separated deck

    TBD
