
# Qat the Cat: an educational game


<!-- TABLE OF CONTENTS -->

## Table of Contents

* [About the project](#about-the-project)
	 * [Built with](#built-with)
* [How to play](#how-to-play)
	* [Goal of the game](#goal-of-the-game)
	* [Movement](#movement)
	* [Splitting Qat](#splitting-qat)
* [Screenshots](#screenshots)



<!-- ABOUT THE PROJECT -->

## About the project

The aim of the project is to:

* Create a demonstration of a game as a proof of concept,
* Showcase the accessibility of the IBM Qiskit API,
* Inspire interest and awareness in quantum computing,
* Expose players to basic topics in quantum mechanics (namely, superposition and quantum gates).

### Built with

* [Qiskit](https://qiskit.org/)
* [Python](https://www.python.org/)
* [PyGame](https://www.djangoproject.com/)

<!-- HOW TO PLAY -->


## How to play

### Goal of the game

Your goal when playing is fairly simple: move Qat the Cat around a grid map, from its initial position to a given final position.

### Movement 
As we said, movement is the main mechanic of the game. In order to move Qat, you must manipulate the state of two qubits, |q_1, q_0⟩, in such a way that each possible basis state corresponds to one of the four cardinal directions:
* |00⟩ corresponds to moving _up_,
* |01⟩ corresponds to moving _right_,
* |10⟩ corresponds to moving _down_,
* |11⟩ corresponds to moving _left_.

In order to do this, you are given a list of quantum gates: _X_, _H_, _CNOT_ and _I_. You must first choose what qubit(s) you want to act on, and then the gate(s) that you want to apply.

Once that the state of the two qubits is the one you desire, you must click on the Qat button in order to move in the corresponding direction.

### Splitting Qat

In Quantum Mechanics, one system may be in a _superposition_ of two states. For example, a qubit may be in the state |0⟩, |1⟩ or a superposition of both, denoted by
a |0⟩ + b |1⟩.

When we are using two qubits, like we are for moving Qat, we may have a state that looks like
1/sqrt\[2\] (|00⟩ + |11⟩), meaning that Qat will split into two Qats with an equal _probability amplitude_.


## Future of the project

We intend to revamp the User Interface, in order to make the game more intuitive and easier to play, by:

* Including tutorials, links to Qiskit and guides,
* Adding an option to display the quantum states and probability amplitudes,
* Embedding circuit diagram in game window.

The next step will be to design and implement more levels, growing in difficulty and complexity.

Finally, some other ideas we might implement in the future are:

* Adding a co-op mode,
* Adding a new mechanic for designing more difficult stages, consisting on _"portals"_ that teleport Qat from one cell of the map to another.


## Screenshots

Please, keep in mind that this is a pre-alpha version made in 24 hours during a Hackathon, so expect a lot of improvements in the near future!

![](https://raw.githubusercontent.com/NandiBee/QCamp/master/Final_3/2.PNG)

![](https://raw.githubusercontent.com/NandiBee/QCamp/master/Final_3/3.PNG)

![](https://raw.githubusercontent.com/NandiBee/QCamp/master/Final_3/4_img.PNG)
