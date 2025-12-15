return a `device` type instance. Contains: device("cuda", 2): device and index.

# usage
~~~python
gpu_generator = torch.Generator(device='cuda:0')
# or
cpu_generator_str = torch.Generator(device='cpu')

gpu_generator = torch.Generator(device=image.device)

# or
device = torch.device("cuda", 0)
gpu_generator = torch.Generator(device = device)
~~~