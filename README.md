# Inventory Cost Optimization & Demand Forecasting of Proximus Ada's Mobile Devices Shop Distribution (MDSD) Supply Chain

> This proposal is announced as the 2nd best (runner-up) winning solution of our Hackathon Project with Proximus Ada at Vlerick Business School, Leuven, Belgium, from 8-12 April 2024. My team consists of Jean-Louis Swart and Aizaz Ali Khan. Myself represented Politecnico di Milano Graduate School of Management.

## Proposed workflow: Demand-Anticipating Policy

The mobile devices shop at Proximus need to overcome problem related to understock, overstock, and terminal costs, caused by uncertainty in tomorrow's demand. In our proposed workflow, we design a new policy model that reacts to the demand for particular products (iPhone, Samsung, Xiaomi). To minimize the cost, we need to fix the Demand forecasting model with ARIMA that captures seasonality of demand fluctuations. Then using our new policy model we take this forecasted demand as the input to our policy and succeed to minimize cost by 56%. 

![image](https://github.com/yohanesnuwara/Proximus-SupplyChain-Optimization/assets/51282928/a5884dc1-7c4d-402d-8454-47c8f8776d98)

## Summary of results

## Future improvement

* Distribution model to each shops
* Policy Evaluation carried out per week
* Policy model taking the product lifecycle into consideration (Launch, Maturity, End-of-life/EOL phase): the idea that our team proposed is giving different Restock with respect to where the product phase is currently at e.g. multiply 2 restocks when product is launching phase, multiply 3 when maturity, and no multiply when EOL. But because time of hackathon was limited, we did not execute this idea
* Improve these processes with Reinforcement learning
