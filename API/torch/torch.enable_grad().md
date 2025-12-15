>[!tip] Tags
> #torch #pytorch #gradient #grad
# torch.enable_grad()

# How
~~~python
x = torch.tensor([1.], requires_grad=True)
with torch.no_grad():
    with torch.enable_grad():
        y = x * 2
y.requires_grad
y.backward()
x.grad
@torch.enable_grad()
def doubler(x):
    return x * 2
with torch.no_grad():
    z = doubler(x)
z.requires_grad
@torch.enable_grad()
def tripler(x):
    return x * 3
with torch.no_grad():
    z = tripler(x)
>>> z.requires_grad
True
~~~

## What
context controller, enable gradient

## When
When you want to express "here need gradient" apparently.

