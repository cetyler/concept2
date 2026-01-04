# Concept 2 Scripts

A collection of scripts to help get workout data and generate reports.
I got the initial script from
[Matt Martin](https://github.com/mattmartin14/dream_machine/tree/main/concept2).

## Quick Install

I use `uv`.
To download the workouts:

- Rename `env_sample` to `env`.
- Put in your username and password to https://log.concept2.com/ into `env`.
- Run `uv run c2_workouts_dl.py --help` to get the options.

When running help you will get the following:

```bash
usage: c2_workouts_dl.py [-h] [--limit LIMIT] [--parallel-fetches PARALLEL_FETCHES] [--season-year SEASON_YEAR]

Download Concept2 workout logs.

options:
  -h, --help            show this help message and exit
  --limit LIMIT         Limit the number of workouts to download.
  --parallel-fetches PARALLEL_FETCHES
                        Number of parallel downloads.
  --season-year SEASON_YEAR
                        The season year to download workouts from.
```

If you decide to use pip, open `c2_workouts_dl.py` and at the top will have the
packages to install.
