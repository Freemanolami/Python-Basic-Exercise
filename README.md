# Python Order Processing Script

This repository contains a Python script designed to process product orders efficiently, handle errors, and apply discounts based on total order value. This versatile program is structured to validate input data, calculate costs, and maintain a clear error log.

## Overview

The Order Processing Script helps manage orders by:

1. Ensuring valid product data (product name, quantity, and price).

2. Calculating total costs for each order with optional discounts.

3. Logging invalid data or errors for later review in error_log.txt.

4. Printing details of successfully processed orders in an easy-to-read format.

This script is ideal for small businesses, developers, or anyone looking to automate and streamline order handling.


## Features 

Data Validation:

1. Detects missing or invalid product, quantity, and price values.

2. Reject orders with negative or zero quantities and prices.

Discount Application:

1. Automatically applies a 10% discount for orders exceeding the threshold of $1000.

2. Customizable discount settings allow for flexibility.

Error Logging:

1. Logs detailed error messages for invalid orders to error_log.txt.

2. Ensures skipped orders do not disrupt processing.

Detailed Output:

1. Provides comprehensive order summaries, including pricing and discounts.

2. Skipped orders are flagged clearly in the terminal.
