This code simulates the behaviour of insects in the presence of a light source. This project is loosely based on the pygame simulation implemented in the paper Visual social information use in collective
foraging. For the sake of this project we assume these insects to be moths

First n number of moths are created(n=400, value can be changed), each moth is given a different position and a different velocity.
The behaviour of these moths is dependend on their state - EXPLORATION,SOCIAL RELOCATION,EXPLOITATION 
These states are determined by value u and w that collect personal behaviour and social behaviour respectively
If moth is present in exploration state is continues with its given velocity
If moth is present in social relocation state, it takes on a weighted velocity of its neighbours, with moths having exploitation state a larger weightage
If moth is present in exploitation state, it moves towards the light source given that the number of moths already in its vicinity are less than a certain number, and once in its area the moth starts spiralling around the light source.

PS - WILL HAVE TO DOWNLOAD MOTH PNG FOR THE CODE TO WORK
