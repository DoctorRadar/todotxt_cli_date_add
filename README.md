# todotxt cli date add

## Description

A todo.txt add override that prepends the task w/ the creation date.

## Installation

- In your actions directory (default `.todo.actions.d`) create a new directory called `add`.
- Clone the repo into the new directory `git clone https://github.com/DoctorRadar/todotxt_cli_date_add.git ~/.todo.actions.d/add/`
- Set the script to be executable `chmod + x ~/.todo.actions.d/add/add`

## Assumptions
Assumes that you have added the `todo.sh` script to your path. If not, edit the script to change the reference to `todo.sh` to whatever alias you have used.

## Usage

Type `todo.sh add This is my new task`

Results in the line

`nn YYYY-MM-DD This is my new task`

be added to the `todo.txt` file where `nn` is the task number and `YYYY-MM-DD` is the creation date.
