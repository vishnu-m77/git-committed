# git commit automation with backdated commits

A Python script that creates 1-3 commits per day from a specified start date to today, ensuring all commits are backdated with sequential timestamps. This is perfect for generating a realistic Git history or simulating daily contributions for a GitHub streak.

## Features

- Automatically generates backdated commits from a specified start date to today, default start date is Jan 1st, 2023.
- Ensures 2-3 commits per day with sequential timestamps to maintain a clean Git history.
- Modifies a file (`changes.txt`) to include unique changes for each commit.
- Commits include timestamps set using `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE`.

## Setup

1. Clone this repository:

```bash
git clone https://github.com/Caparino/git_committed
cd git_committed
```

2. Run the script to generate commits:

```bash
python git_committed.py
```

## Usage

The script will schedule and commit the change to git. You can modify the script to use any start date, any range of random commits per day, or use a different file to store the number.

By running this you will be able get a fancy streak on your github profile and get a job.

![How to get a job](get_a_job.jpg)

Inspired by ![@Shogun89's fancyjob](https://github.com/Shogun89/fancy_job)
