Topic:Casino Game Fairness Analysis

Project Overview

This project is developed for the Simulation & Modeling Lab Course.
The main objective of this project is to analyze whether a casino game is fair or unfair using simulation, probability theory, and statistical analysis in Python.

The project simulates an unfair casino dice game where the probability of losing is intentionally higher than winning. Multiple statistical techniques are applied to evaluate fairness, player loss patterns, and casino profit growth.

Features:

Monte Carlo Simulation

Unfair Casino Dice Game

Probability Distribution Analysis

Chi-Square Test

T-Test Analysis

Uniform & Normal Distribution Visualization

Statistical Summary

Player Profit/Loss Tracking

Casino Profit Growth Visualization

Graphical Analysis using Matplotlib & Seaborn

Technologies Used:

Python,Google Colab, NumPy, Pandas,Matplotlib,Seaborn,SciPy

Rules:

A dice roll between 1-5 results in a player loss

A dice roll of 6 results in a player win

Betting System:

Initial Money = 1000

Bet Per Round = 50

Total Rounds = 500


Outcome	Probability:

Loss	5/6

Win	1/6

The casino is intentionally designed to be unfair.

Statistical Methods Used:

1. Monte Carlo Simulation

Used to simulate hundreds of casino rounds and observe long-term outcomes.

2. Chi-Square Test

Used to determine whether the observed outcomes differ significantly from expected fair outcomes.

3. T-Test

Used to analyze whether player earnings significantly differ from zero.

4. Probability Distribution
Uniform Distribution
Normal Distribution
5. Descriptive Statistics
Mean
Standard Deviation
Variance
Win Rate
Loss Rate
Visualizations

The project includes multiple visualizations:

Dice Roll Frequency
Money Trend Over Time
Uniform Distribution Graph
Normal Distribution Graph
Casino Profit vs Player Loss Graph
Expected Result

The simulation demonstrates that:

The player continuously loses money over time
The casino continuously gains profit
Statistical tests confirm that the game is unfair
P-value becomes very small, rejecting fairness assumptions


Conclusion:

This project successfully demonstrates how simulation and statistical modeling can be used to analyze casino game fairness. The unfair probability design results in consistent player losses and increasing casino profits, which is validated through statistical testing and graphical analysis.
