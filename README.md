# Determining-arbitrage-strategies-in-the-presence-of-liquidity-risk
A project to find arbitrage strategies taking into account the liquidity risk with the implementation of functionality in Python

# Technical Statement 


## Objective:

The objective of this technical task is to design and implement a Python program that defines arbitrage strategies for financial markets while taking into account the presence of liquidity risk. The program aims to identify arbitrage opportunities within the given market and assess liquidity risk as a critical factor in the decision-making process.

## Description:

### Data Input and Simulation:

The program should be able to take input data such as market exchange rates, bid-ask spreads, and initial portfolio balances for various financial instruments.
It should simulate market data, including exchange rates and spreads, which will be used for identifying arbitrage opportunities.

### Liquidity Risk Assessment:

Develop a mechanism for assessing liquidity risk. Liquidity risk assessment should take into account market conditions, historical data, and any other relevant factors.
Implement a method for classifying liquidity as "Low," "Medium," or "High" based on the assessment.

### Identification of Arbitrage Opportunities:
Create a function or algorithm that identifies potential arbitrage opportunities within the market. The opportunities may involve cross-currency exchange rates, options, or any other financial instruments suitable for arbitrage.
Consider bid-ask spreads and liquidity status while identifying these opportunities.

### Execution of Arbitrage Strategies:
When an arbitrage opportunity is identified and liquidity risk is deemed acceptable, the program should execute arbitrage strategies.
These strategies may include buying and selling financial instruments to profit from price differentials.

### Output and Reporting:

The program should provide clear and concise output, indicating whether arbitrage opportunities were found and whether they were executed.
Display information on liquidity risk assessments and the resulting portfolio balances after arbitrage transactions.


## Literature review

1. The Harrison–Pliska arbitrage pricing theorem under transaction costs, Kabanov Yu. M., Stricker Ch.

**Overview**

The presented article extends the Harrison-Pliska arbitrage pricing theorem to a model of a foreign exchange market with multiple assets in discrete time and transaction costs. The authors investigate the absence of arbitration and provide the necessary and sufficient conditions for this. They also prove the hedging theorem without additional assumptions. The article concludes with a discussion of the differences between their approach and other articles on this topic.

The text is dedicated to arbitrage in the frictionless market. It introduces the concept of convertible assets and classifies assets into equivalence classes based on their convertibility. The text then defines sets of attainable wealth and hedged requirements. It presents the conditions for refusal of arbitration and demonstrates their equivalence in terms of strict and weak arbitration possibilities. To illustrate the concepts, an example of a single-period model with two assets is given.

The article deals with the problem of hedging conditional claims in financial markets, taking into account transaction costs. The authors prove several theorems related to the existence of non-arbitrage and a set of hedging strategies. They also consider generalizing the model and discuss the implications of different transaction cost structures.

**Useful links**

1. https://medium.datadriveninvestor.com/calculating-risk-management-statistics-in-python-756ab3cb1851
2. 