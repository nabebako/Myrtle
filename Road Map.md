# Phase 0 - Project Setup

1. ~~Initialize git repo~~
2. ~~Set imports~~
3. ~~Configure venv~~
4. ~~Upload git repo to Github~~
5. Add a readme

# **Phase 1 - Research**

1. Conduct a survey on stock price prediction
2. Generate possible blueprints of the model
3. Gather revelent data from trusted soruces

# Phase 2 - Development

1. Experiment with multiple methods and proceede with most sastifying model
   1. Construct and train models based on generated blueprints
   2. Evaluate modles by conducting accuracy tests
   3. Readjust blueprints to improve accuracy and precision
2. Conduct tests across multiple markers to indicate the model's reliability
3. Finalize the model

# Phase 3 - Market Data API Integration

1. Integrate Alpaca's Market Data API
2. Determine the necessity for on-site sotrage bucket and proceede accordingly
3. Prepare the dataset from Alpaca to be compatible with the model inputs

# Phase 4 - Automation

1. Create data pipeline from Alpaca's API to the model's inputs
   1. Automate data import from Alpaca or on-site data bucket
   2. Automate data cleaning and labeling
2. Determine the necessity for scheduled Alpaca's API request and proceede accordingly
   1. Create CRON jobs to automatically pull new data from Alpaca
   2. Process incoming data using automated data cleaning and labeling
   3. Store processed data on an on-site storage bucket
   4. Reroute data request from the model to the on-site storage bucket

# Phase 5 - API Creation

# Phase 6 - Frontend Application (React)

# Phase 7 - Deployment
