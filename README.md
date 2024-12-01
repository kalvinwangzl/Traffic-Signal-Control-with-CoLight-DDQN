# Requirments:
python=3.6, tensorflow=2.4, pandas, numpy

CityFlow requires a Linux environment. So we run the code in Windows Subsystem for Linux (WSL).

# Command to run training

## MaxPressure

To train MaxPressure with Pressure:

`python run_maxpressure.py`

To train MaxPressure with Efficient Pressure:

`python run_efficient_maxpressure.py`

To train MaxPressure with ATS:

`python run_advanced_maxpressure.py`

## MPLight

To train MPLight with Pressure:

`python run_mplight.py`

To train MPLight with Efficient Pressure:

`python run_efficient_mplight.py`

To train MPLight with ATS:

`python run_advanced_mplight.py`

## CoLight

Before training CoLight, if you want to train CoLight-DQN, replace the content of models/colight_agent.py with models/colight_agent_dqn.py. If you want to train CoLight-DDQN, replace it with models/colight_agent_ddqn.py

To train CoLight with Pressure:

`python run_colight.py`

To train CoLight with Efficient Pressure:

`python run_efficient_colight.py`

To train CoLight with ATS:

`python run_advanced_colight.py`

# Command to run evaluation

To run evaluation:

`python summary.py`

# Reference
