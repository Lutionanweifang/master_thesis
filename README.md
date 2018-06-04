See 'dev_branch2' for actual project code

# master_thesis
Towards Decentralised Grids:
masters Thesis Dirk van den Biggelaar 2017-2018 for the degree of Systems and Control engineer at the TU Delft, the Netherlands.

This is a microgrid model with a distributed trading alghorithm running that coordinates the charging/discharging of batteries to stablise the grid. The algorithm is hierarchial in nature, roughly following a reversed-Stackleberg game as framework, but not closed-form. This causes the agents to converge together untill certain margins are met. Batteries are adapting their demand/surplus over time by using a prediction model to anticipate on scarcity/abundance of produced energy within the grid, dependant on weather patterns, the production capacity of agents and the energy consumption of their houses. 

Charging/discharging is reimbursed by minting/burning tokens on a smart-contract, currently deployed on an Ethereum test-network. Minimal information is exchanged between agents. The minimum of information that is really needed is logged in the public ledger, to etch-in-rock the promises agents made when exchanging information. This promise-keeping mechanism counters artificial raising of prices in the grid and helps keep stability by ensuring that demand/supply is kept true. Also the smart-contracts serves as a time-staming server to assist distributed optimization in an asycnhronous network.

See high-level diagram of project structure

