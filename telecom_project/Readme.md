# Telecom Project

### Task

Find clients who: 

- Overpay for their current plans 
- Need bigger plans, since they'll be more advantageous

- Carry out exploratory data analysis.
- Find clients with non-optimal plans. Only look at active clients. Think about how you can offset the risk of a considerable reduction in revenue should all users switch to plans that are more profitable for them.
- Test statistical hypotheses.

### Pricing

All prices are given in generic monetary units.

- `Basic price of plan A` — 5000
- `Basic price of plan B` — 2000 
- `Basic price of plan C` — 1000
- `Incoming calls for all plans` — free

 `Internal calls for all plans` — a limit of 2000 free minutes per month, beyond which:

- `Plan A` — 0.1 units/minute
- `Plan B` — 0.15 units/minute
- `Plan C` — 0.3 units/minute

Outgoing (not internal) calls:
- `Plan A` — 0.4 units/minute
- `Plan B` — 0.5 units/minute
- `Plan C` — 0.7 units/minute

The client also pays 100 units for each operator (irrespectiv of plan).

### Description of the data

The zipped dataset `telecom_dataset_us.csv` contains the following columns:

- `user_id` — client account ID
- `date` — date the statistics were retrieved
- `direction` — call direction (`out` for outgoing, `in` for incoming)
- `internal` — whether the call was internal (between a client's operators)
- `operator_id` — operator identifier
- `is_missed_call` — whether the call was missed
- `calls_count` — number of calls
- `call_duration` — call duration (excluding wThe Taiting time)
- `total_call_duration` — call duration (including waiting time)

 

The dataset `telecom_clients_us.csv` has the following columns:

- `user_id`
- `tariff_plan` — client's current plan
- `date_start` — client's registration date


#### Used Libraries:
- Pandas, numpy, scipy, plotly, seaborn

#### tags:
- data analysis, ML, Python, SQL, Git, Pandas, Numpy, Matplotlib, seaborn, Sklearn, Tableau, Spark,  R, sci-py, Research, Kaggle, Algorithms, Research, Kaggle



