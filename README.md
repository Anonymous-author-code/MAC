# MAC
The source code of the paper 
Dependencies:

Python 3.6.4
Torch
Numpy
Matplotlib
Apex
tqdm
pyconcorde
# How to train it?
To train the model you can run:

For TSP instances with 20 nodes:

python PGTSP20.py
For TSP instances with 50/100 nodes (default 50 nodes):

python PGTSP50_100.py

# How to test it?
To use the learned polcies reported in the paper you can run:
python TestLearnedAgent.py --load_path best_policy/policy-TSP20-epoch-189.pt --n_points 20 --test_size 1 --render 
where load_path can be replaced with one of the policies in /best_policy.
