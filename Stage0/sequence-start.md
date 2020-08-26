# Interaction Sequences

## Startup Sequence

The InputPoll module takes the starting time,initial score,initial position and velocity as input.

The Velocity,TimeCounter and ScoreCounter modules use the InputPoll module to update.

## Movement Initiation

The Velocity module gives the ball velocity and BallPosition module gives the ball position.

The TimeCounter module keeps a count of time and updates the Velocity and BallPosition modules every 50 milliseconds.

The Velocity module also changes ball direction when a collision occurs and the CollisionAlarm module tells the Velocity module when a collision happens.  

## One score

The ScoreCounter module keeps count of the scores of the two players and invokes the DeclareWinner module.

The ScoreAlarm module tells ScoreCounter when to increment a score.

The BallPosition module gives the ball position to ScoreAlarm.
