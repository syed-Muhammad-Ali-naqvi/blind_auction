## Bidding Game

# Overview

This Python program is a simple bidding game where multiple users can place their bids, and the program determines the highest bidder. The game is designed to provide a fun and interactive way for users to engage in a simulated auction.

# Features

Allows multiple users to participate in a bidding process.

Automatically tracks and compares bids to determine the highest bidder.

Simple and user-friendly interface.

Option to clear the console for a clean display after each bid (if using the Replit environment).

# Prerequisites

To run this program, ensure the following:

Python 3.x is installed.


# How to Play

The program will prompt the first user to enter their name and bid amount.

After each bid, the program will ask if there are more bidders.

If yes, the next user can enter their name and bid.

If no, the program will determine the highest bidder and display the results.

The game ends when no more bidders are present.


# Function: find_highest_bidder

This function takes the bidding_record dictionary as input and determines the highest bid and the corresponding winner.

Iterates through the dictionary.

Compares each bid amount to find the highest bid.

Displays the winner and their bid amount.

# Main Logic

The program runs in a loop until no more bidders are left.

After each bid, the program:

Adds the bid to the bids dictionary.

Prompts whether more bidders are present.

If not, the game ends, and the highest bidder is announced.
