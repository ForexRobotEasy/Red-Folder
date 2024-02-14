# Forex Robot Easy ReadMe File

This ReadMe file provides a brief overview of the code for the Forex Robot Easy, developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/red-folder-forex-software-revolutionize-your-news-trading-strategy/).

## Table of Contents
- [Introduction](#introduction)
- [Libraries](#libraries)
- [Global Variables](#global-variables)
- [OnStart Function](#onstart-function)
- [Helper Functions](#helper-functions)
- [OnTimer Function](#ontimer-function)
- [OnStop Function](#onstop-function)

## Introduction
The Forex Robot Easy is a trading robot that automates trading based on predetermined criteria and news event parameters. The code provided here is a sample code that demonstrates the basic structure and functionality of the robot.

## Libraries
The code includes the following necessary libraries:
- Trade: Provides classes and functions for trading operations.
- Expert: Contains the Expert class for creating trading robots.
- Timeseries: Includes classes and functions for handling time series data.

## Global Variables
- `CTrade trade`: Trade class object used for executing trades.
- `CTimeseries series`: Timeseries class object used for handling time series data.

## OnStart Function
The `OnStart` function is the main entry point of the code and is executed when the Expert Advisor is started. It performs the following tasks:
1. Initializes the `trade` and `series` objects.
2. Subscribes to the necessary events.
3. Enters into the main trading logic loop, which checks for new trading signals and news event trading opportunities.

## Helper Functions
The code provides several helper functions that are used in the trading logic:
- `IsNewSignal`: This function checks for any new trading signals. You need to insert your code to check for new trading signals and return `true` if there is a new signal, `false` otherwise.
- `ExecuteTrade`: This function executes trades based on predetermined criteria. You need to insert your code to execute the trade.
- `IsNewsEventTime`: This function checks if it's time for news event trading. You need to insert your code to check if it's time for news event trading and return `true` if it's time, `false` otherwise.
- `ExecuteNewsEventTrade`: This function executes trades based on pre-set news event parameters. You need to insert your code to execute the news event trade.

## OnTimer Function
The `OnTimer` function is triggered by a timer event and is used to update timeseries data and any necessary data.

## OnStop Function
The `OnStop` function is executed when the Expert Advisor is stopped. It is used to clean up and close any open trades.

**Note:** ForexRobotEasy is not the official developer of this product. This code serves as a sample code that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/red-folder-forex-software-revolutionize-your-news-trading-strategy/).
