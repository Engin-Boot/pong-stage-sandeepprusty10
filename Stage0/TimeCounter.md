# Time Counter

## Feature

This module keeps a count of real time elapsed and updates the Velocity and BallPosition modules every 50 milliseconds.

## Acceptance Criteria

### Scenario: Return real time elapsed from the start of the game

  Given the initial time as 0 s

  When current time is required

  Then return the current time from the start of the game

### Scenario: Update the Velocity and BallPosition modules every 50 milliseconds

  Given the initial time as 0 s
  
  When the time elapsed crosses a multiple of 50 milliseconds
  
  Then update the Velocity and BallPosition modules
