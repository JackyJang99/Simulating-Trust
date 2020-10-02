# Simulating Trust

This project is a blind implementation of Nicky Case's [explorable explanation](https://ncase.me/trust/) on game theory.
For the code, check out [gitlab](https://gitlab.com/Vanguard-/simulating-trust).
  

## What It Does

 **Simulating trust** is a simulation project focused on 2 agent game theoretic encounters, with the purpose of exploring how specific strategies fare for a given game (which is defined by the payoff matrices).

## How It Works
To know how things work, please take a look at the [wiki](https://gitlab.com/Vanguard-/simulating-trust/-/wikis/home).
Sample use can be found in the [notebook](https://gitlab.com/Vanguard-/simulating-trust/-/blob/master/src/working_nb.ipynb). The unrendered cell is shown below.

## Requirements and limitations
Plotly, pandas, and numpy are required to run the code.

  
The `__call__` method for `Sandbox.plot` only works inside of a Jupyter environment since it is designed to be a convenience method.

![Screenshot](assets/call_method_v1.png)



