# Customer Call List Cleaning with Pandas

## Project Overview
This project processes and cleans a customer call list from an Excel file using Pandas. The dataset contains customer details such as names, phone numbers, addresses, and customer status. The script ensures data consistency, removes duplicates, formats phone numbers, and filters out unwanted records.

## Features
- Removes duplicate records
- Cleans up last names by stripping unwanted characters (`123./`)
- Formats phone numbers to `XXX-XXX-XXXX` format
- Splits the `Address` column into `Street_Address`, `State`, and `Zip Code`
- Standardizes `Paying Customer` and `Do_Not_Contact` values (`Yes` or `No`)
- Removes invalid phone numbers and customers marked as "Do Not Contact"
- Fills missing values with an empty string
