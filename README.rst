Fleming Custom Taxi Environment Based on OpenAI Gym
***************************************************

Installation
============

Install in your working directory with:

.. code-block::

    git clone https://github.com/FlemingDL/gym_fleming.git
    cd gym_fleming
    pip install -e .

In your python file enter:

.. code-block::

    import gym
    import gym_fleming
    env = gym.make('taxi_fleming-v0')