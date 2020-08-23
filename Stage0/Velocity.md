# Velocity

## Feature

This module gives ball velocity depending on collisions.

## Acceptance Criteria

### Scenario: Give current ball velocity

  Given the initial velocity and the time elapsed

  When a collision occurs

  Then invert horizontal velocity if it is a collision with a vertical wall
  
  And invert vertical velocity if it is a collision with a horizontal wall
