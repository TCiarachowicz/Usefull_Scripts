# Usefull_Scripts

## conda
conda list -n dl_torch --json > dl_torch-packages.json

## python

<code>
import torch
tensor = torch.rand(5, 3)
print(f'Test tensor successfully created:\n{tensor.size()}')
cuda = torch.cuda.is_available()
print(f'CUDA available: {cuda}')
print(f'Torch version: {torch.__version__}')
</code>
