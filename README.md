
# COVID-19 Tracker

This is a small python script to get COVID-19 update through notification system. It keeps track of Covid-19 cases, deaths and recovery. This tool solely relies on [Worldometer](https://worldometers.info).   


## Installation

Requires python3 to be installed on your computer.

```python
git clone https://github.com/r3alix01/CovidTracker.git
cd CovidTracker
pip3 install -r requirements.txt
```
    
## Usage

```python
python3 /path/to/CovidTracker.py
```
If you face any error while running this tool in your Linux System. Run this command

```python
sed -i -e 's/\r$//' CovidTracker.py
```


## For Best Use

 - WINDOWS

The best way to run this tool to get frequent updates without running this tool manually all the time is to create a task in Windows Task Scheduler. For additional guides, follow [this guide](https://www.windowscentral.com/how-create-automated-task-using-task-scheduler-windows-10). Or, simply run this command once 

```python
pythonw /path/to/CovidTracker.py
```

- LINUX

For Linux system creating a cronjob will get rid of manually re-running the tool. For creating a Cronjob, follow [this guide](https://towardsdatascience.com/how-to-schedule-python-scripts-with-cron-the-only-guide-youll-ever-need-deea2df63b4e)
