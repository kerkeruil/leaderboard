# Leaderboards for Assignment 1 - Part 1
This directory contains one leaderboard table for each method run in the assignment.
Click one of the markdown files listed above to see the corresponding leaderboard. For example, [BM25_1.md](BM25_1.md)

You can check the commit log to see when the leaderboard was last updated. This should happen about once per hour, assuming a group's results have changed.

## Troubleshooting
If you cannot find your team name in the tables, check the `known_teams.txt` file. Your team is likely missing from this file. Please create a private issue on Piazza letting us know that your team needs to be added.

If your team name is listed with a metric value of -999, this means we did not find the corresponding `.trec` file in your repository. For example, if your team is listed with -999 in `BM25_1.md`, this means we did not find a `BM25_1.trec`.

If you see a -999 and believe this is incorrect, please check the commit log to see whether the leaderboard was simply last updated before the `.trec` file was created. If you still believe the -999 is incorrect after checking this file, it may be due to force pushing to your git repository. This prevents our `git pull` from succeeding. Please create a private issue on Piazza letting us know, so we can checkout a clean copy of your repository.
