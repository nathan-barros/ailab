# AI LAB

AI LAB ("the lab") is a Python library dedicated to easy AI model development
in a wide variety of contexts. The lab lets you generate an untrained neural
network in a single line of code or even automate the process of creating models
during an evolution simulation. The lab provides structure for AI development while
you can focus on defining the problem and how AI can solve it.

## Author's Note
...

## Installation
Use the standard Python package manager [pip]
(https://pip.pypa.io/en/stable/) to install the lab.

'''bash
pip install foobar
'''

## Usage 

1. Define the problem, the desired solution, and a measure of success.
2. Determine how digital systems can interact with the problem.
3. Generate an untrained AI model which meets the previously defined items.
4. Collect training data (if necessary) and train the AI.
5. Test the AI on untrained example problems.
6. Continue developing the model (if necessary).


### Neural Networks
```python
from ailab import NeuralNetwork as NN

# define some network architectures
arch_types = [
    (1,1),       # 1 input node -> 1 output node
    (1,1,1),     # 1 input -> 1 hidden node -> 1 output
    (1,2,1),     # 1 in -> 2 hid -> 1 output
    (3,2,3),     # 3 -> 2 -> 3
    (9,12,12,9), # 9 -> 12 -> 12 -> 9 (Tic Tac Toe Network)
]

# generate those networks
net1 = NN(arch_types[0])
net2 = NN(arch_types[1])
net3 = NN(arch_types[2])
net4 = NN(arch_types[3])
net5 = NN(arch_types[4])

```

## Documentation

## Contibuting

## License

[MIT] (https://choosealicense.com/licenses/mit/)
