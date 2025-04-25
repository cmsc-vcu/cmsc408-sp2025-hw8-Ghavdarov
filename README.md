# cmsc408-sp2025-hw8

## Homework 8 - World Bank Indicator Analysis

Unlike previous assignments, this assignment has a pre-made database which we must gather information from using SQL. The database is of a World Bank whose goal is to reduce poverty and promote economic development. This World Bank also conducts research and analysis which will be done by us (the student).

## Overview

1. First things first, you must connect to the database.

    - This is done by utilizing the MySQL extenstion in VScode and connecting using the same credentials in a .env
      that can be found in previous assignments. The only difference is that the 'hw#' part must be changed to 'hw8'.
    - Make sure to look for a .env-sample file.

2. Now clone the repo and cd your way into the reports folder.

3. Before getting started, you must prep poetry.

    - First, run the poetry install command and get everything you need from the poetry.lock file
    - Second, run the poetry shell command to get it primed for the main event.

4. Finally, Starting procedures.

    - Quarto throws a fit when you try to preview the report.qmd file using the keybind, not sure why. It might work for you, but it didn't for me.

    - Run this command to prime poetry for the run: poetry run quarto render report.qmd

    - After that, run this command to open it: quarto preview report.qmd

    - You should be all set unless you didn't connect to the database properly.

## Additional notes

- When testing the blocks of the report.qmd file on VScode, it gave me an error, might not for you. Regardless, when you run it with quarto it should open just fine error-free.

- For some reason, the Table of Contents only shows everything up to task 2. Again, not sure why, it just does.


