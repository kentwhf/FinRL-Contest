# Data-centric Stock Trading Task
This template includes all the essential source files for the Stock Trading task in the FinRL ICAIF contest. Below, you'll find detailed descriptions of each component.

## Folder Structure

├── Finrl-contest 
│ ├── results # PPO logs
│ ├── trained_models # Trained PPO weights
│ ├── train_data.csv # Source data file
│ ├── train.py # Source file for training using the default PPO model
│ ├── test.py # Source file for testing the contestants' submitted PPO model

## Instruction
To install the necessary dependencies, please ensure you are using Python 3.10 as your interpreter.
```
pip install -r requirements.txt
```

## Deliverable
We encourage contestants to curate their own dataset. To ensure a smooth testing phase, participants should design their data curation pipeline to seamlessly incorporate previously unseen, hidden test data (provided in a basic format as `train_data.csv`). For instance, we will use `test.py` to assess the performance of your submitted model.

```
python3 test.py --start_date 2022-01-01 --end_date 2022-12-31 --data_file test_data.csv
```
