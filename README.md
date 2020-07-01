# customer data simulation
This file contains handy functions to simulate data for e.g. generate a list of random numbers, strings, IDs, generate random numbers by specific distribution etc.

Additionally there is a wrapper class which can be used to generate
  - customer demographics data
  - customer transaction data
  - a campaign (marketing data)

# Other inputs
  - A city to state mapping file is used as an input to generate geographic information for customers for reference see file us_city.csv
  - Presently code outsources a list of customer ids from an external location, this can be simulated within the code as well
 
 
 # Output
  - A transaction file with customer demographics & item purchased data
  - A campaign file with details of offers given to customers
