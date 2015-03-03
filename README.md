# CS4341-Busters
I ain't 'fraid of no ghosts.

Q1 - Q5 all run and pass under the command
python autograder.py -q q1/q2/q3/q4/q5 --no-graphics

However, we ran into an issue where q5 will pass its tests but will not give us credit 
due to a TimeoutFunctionException. However, we have checked our code (See inference.py in the observe 
and elapsedTime functions under ParticleFilter) and can verify that the chunks should 
produce valid answers.