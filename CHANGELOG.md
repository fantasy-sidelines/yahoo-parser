## v6.0.0 (2023-11-22)

### Fix

- added game_key field to roster_position_df in LeagueParser

## v5.0.4 (2023-11-22)

### Fix

- game_key null constraint in database correction

## v5.0.3 (2023-11-22)

### Fix

- added game_key to stat categories league end point

## v5.0.2 (2023-11-22)

### Fix

- drop position_types out of dictionary

## v5.0.1 (2023-11-22)

### Fix

- position_type vs position_types

## v5.0.0 (2023-11-22)

### Feat

- **stat_categories**: list of position_types instead of a string, csv parsing issue

## v4.0.0 (2023-11-22)

### Feat

- **roster**: eligible_positions_nested data

## v3.0.0 (2023-11-22)

### Fix

- **player_pct_owned**: convert eligible_positions from list to string

## v2.0.3 (2023-11-21)

### Fix

- **column**: column renaming to match tables

## v2.0.2 (2023-11-21)

### Fix

- **parser**: column did not exist, needed renaming

## v2.0.1 (2023-11-21)

### Fix

- **logger**: null logger errors

## v2.0.0 (2023-11-19)

### Feat

- refactoring and dependency adjustment

## v1.1.0 (2023-11-18)

### Feat

- added enviornment variable usage for writing data to parquet

## v1.0.1 (2023-10-15)

### Fix

- **mapping**: column name mapping to match postgres

## v1.0.0 (2023-10-09)

### Fix

- replace use of kwargs with defined parameter

## v0.1.1 (2023-10-08)

### Fix

- **build**: update cicd process for release
- **logging-handler-scope-issue**: Corrected 'Logger' object has not attribute 'handler' AttributeError

## v0.1.0 (2023-09-03)

### Feat

- **initial**: creating a package to parse josn response from yahoo api

## v0.0.0 (2023-09-03)
