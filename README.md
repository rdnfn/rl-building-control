<p align="center">
<img src="https://github.com/rdnfn/rl-building-control/raw/main/rl_building_control_logo.jpg" width="200"/>
</p>
  
# rl-building-control
A curated list of awesome projects for applying reinforcement learning (RL) to building control.

Before diving into the projects, it's worth mentioning some alternative names that are often used to refer to some form of building control: 
- *building optimisation* (BO)
- *building energy optimisation* (BEO)
- *building energy management* (BEM)
- *energy management* (EM)
- *energy management system* (EMS)
- *home energy management* (HEM)
- *home energy management system* (HEMS)
- *smart building energy management* (SBEM)
- *demand-side management* (DSM)
- *building automation and control system* (BACS)
- ...

With so many names it can be difficult to find what you are looking for – this list aims to help with this!

## Environments

The following projects provide standarised RL environments that allow you to control a simulated building. Each environment gives access to a number of controllable devices in the simulated building, for example heating/cooling systems (HVAC), electric vehicle (EV) chargers and home batteries.

- [BOPTEST](https://github.com/ibpsa/project1-boptest) ([second github](https://github.com/ibpsa/project1-boptest-gym)) <kbd>gym</kbd>
- [CityLearn](https://github.com/intelligent-environments-lab/CityLearn) <kbd>gym</kbd>
- [Energym](https://github.com/bsl546/energym)
- [GridLearn](https://github.com/apigott/CityLearn)
- [Gym-Eplus](https://github.com/zhangzhizza/Gym-Eplus) <kbd>gym</kbd> <kbd>last-commit-over-a-year-ago</kbd>
- [ModelicaGym](https://github.com/ucuapps/modelicagym) <kbd>gym</kbd> <kbd>last-commit-over-a-year-ago</kbd>
- [RL-EmsPy](https://github.com/mechyai/RL-EmsPy)
- [RL Testbed for EnergyPlus](https://github.com/IBM/rl-testbed-for-energyplus) <kbd>gym</kbd>
- [Sinergym](https://github.com/jajimer/sinergym) <kbd>gym</kbd> <kbd>pip-installable</kbd>
- [Beobench](https://github.com/rdnfn/beobench)[^1] <kbd>gym</kbd> <kbd>pip-installable</kbd>

> *Tags:*
> - <kbd>gym</kbd>: implements OpenAI Gym interface
> - <kbd>pip-installable</kbd>: uploaded to PyPI (enables `pip install <package>`)
> - <kbd>last-commit-over-a-year-ago</kbd>: last commit on linked repo was over a year ago

[^1]: Disclaimer: I created/contributed to this package.

## Agents

- [VectorInstitute/MBRL-HVAC-Energy-Optimization](https://github.com/VectorInstitute/MBRL-HVAC-Energy-Optimization) - reference solution for training a Model-Based Reinforcement Learning (MBRL) agent to control an HVAC system.


## Further resources

- General RL lists:
  - [kengz/awesome-deep-rl](https://github.com/kengz/awesome-deep-rl)
  - [tshrjn/env-zoo](https://github.com/tshrjn/env-zoo)
  - [clvrai/awesome-rl-envs](https://github.com/clvrai/awesome-rl-envs)
- Practical RL advice:
  - [williamFalcon/DeepRLHacks](https://github.com/williamFalcon/DeepRLHacks) ([corresponding talk](https://www.youtube.com/watch?v=8EcdaCk9KaQ))


## Contact

Did you find a mistake or something missing on the list? Either raise an issue in this repo or reach out to `contact-gh (at) arduin.io`. Thanks for your help!
