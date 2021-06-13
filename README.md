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

For TSP instances with 20 nodes:

python PGTSP20.py

For TSP instances with 50/100 nodes (default 50 nodes):

python PGTSP50_100.py

# How to test it?
Run the policies that have been trained in this article :

python TestLearnedAgent.py --load_path best_policy/policy-TSP20-epoch-189.pt --n_points 20 --test_size 1 --render 

where load_path can be replaced with one of the policies in /best_policy.
