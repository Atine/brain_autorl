export PYTHONPATH=${PWD}/../../
export LD_LIBRARY_PATH=/home/mil/chou/.pyenv/versions/miniforge3-4.10.3-10/lib:$LD_LIBRARY_PATH
python rl_darts/algorithms/ppo/run_ppo.py
