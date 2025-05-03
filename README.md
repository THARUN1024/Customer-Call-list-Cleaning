## Overview

This project cleans and processes a customer call list from an Excel file using Pandas. The dataset includes customer details like names, phone numbers, addresses, and status. The script makes sure the data is consistent, removes duplicates, formats phone numbers, and filters out unnecessary records.

## Actions Taken

- Removes duplicate customer records
- Cleans last names by removing unwanted characters (`123./`)
- Formats phone numbers to a standard `XXX-XXX-XXXX` format
- Splits the address into separate columns: `Street Address`, `State`, and `Zip Code`
- Standardizes customer status values like `Paying Customer` and `Do Not Contact` to `Yes` or `No`
- Removes invalid phone numbers and customers who are marked as "Do Not Contact"
- Fills in missing values with an empty string

