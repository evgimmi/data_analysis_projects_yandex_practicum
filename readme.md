{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Telecom: Finding Clients With Non-Optimal Plans"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Task\n",
    "\n",
    "Find clients who overpay for their current plans \n",
    "\n",
    "\n",
    "- Carry out exploratory data analysis.\n",
    "- Find clients with non-optimal plans. Only look at active clients. Think about how you can offset the risk of a considerable reduction in revenue should all users switch to plans that are more profitable for them.\n",
    "- Test statistical hypotheses."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "\n",
    "\n",
    "### Pricing\n",
    "\n",
    "All prices are given in generic monetary units.\n",
    "\n",
    "- `Basic price of plan A` — 5000\n",
    "- `Basic price of plan B` — 2000 \n",
    "- `Basic price of plan C` — 1000\n",
    "- `Incoming calls for all plans` — free\n",
    "\n",
    "- `Internal calls for all plans` — a limit of 2000 free minutes per month, beyond which:\n",
    "\n",
    "- `Plan A` — 0.1 units/minute\n",
    "- `Plan B` — 0.15 units/minute\n",
    "- `Plan C` — 0.3 units/minute\n",
    "\n",
    "Outgoing (not internal) calls:\n",
    "- `Plan A` — 0.4 units/minute\n",
    "- `Plan B` — 0.5 units/minute\n",
    "- `Plan C` — 0.7 units/minute\n",
    "\n",
    "The client also pays 100 units for each operator (irrespectiv of plan).\n",
    "\n",
    "### Description of the data\n",
    "\n",
    "us\n",
    "\n",
    "The zipped dataset `telecom_dataset_us.csv` contains the following columns:\n",
    "\n",
    "- `user_id` — client account ID\n",
    "- `date` — date the statistics were retrieved\n",
    "- `direction` — call direction (`out` for outgoing, `in` for incoming)\n",
    "- `internal` — whether the call was internal (between a client's operators)\n",
    "- `operator_id` — operator identifier\n",
    "- `is_missed_call` — whether the call was missed\n",
    "- `calls_count` — number of calls\n",
    "- `call_duration` — call duration (excluding wThe Taiting time)\n",
    "- `total_call_duration` — call duration (including waiting time)\n",
    "\n",
    " \n",
    "\n",
    "The dataset `telecom_clients_us.csv` has the following columns:\n",
    "\n",
    "- `user_id`\n",
    "- `tariff_plan` — client's current plan\n",
    "- `date_start` — client's registration date\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
