# Sheephead Decider

**Sheephead Decider** is a Rust-based tool designed to assist players in determining the best possible next move in a game of Sheepshead. The program uses a branch-and-bound algorithm to explore all possible game states, factoring in known and unknown information, and simulates possible outcomes to recommend the optimal play.

## Table of Contents
- [Overview](#overview)
- [Features](#features)

## Overview

Sheepshead is a trick-taking card game with a high degree of complexity due to the variability in unknown information and player actions. **Sheephead Decider** addresses this by running a brute-force branch-and-bound exploration of all possible game states given the maximum amount of knowable information. The goal is to determine the most effective strategy based on simulated outcomes.

## Features
- **Simulate all possible game states**: Explore hands dealt to all players, picked or passed for each player, trick history, and scoring scenarios.
- **Branch-and-bound exploration**: Efficiently narrows down possible moves by pruning invalid or suboptimal strategies.
- **Recommendation engine**: Provides statistical information regarding each of the immediately available options.
