Alias:
torch.chunk()

# Parameter
- input: tensor
- chunks: number of return
- dimL dimension along which to split

# Example
---
```python
torch.arange(11).chunk(6)

(tensor([0, 1]),
 tensor([2, 3]),
 tensor([4, 5]),
 tensor([6, 7]),
 tensor([8, 9]),
 tensor([10]))
 
 
torch.arange(12).chunk(6)

(tensor([0, 1]),
 tensor([2, 3]),
 tensor([4, 5]),
 tensor([6, 7]),
 tensor([8, 9]),
 tensor([10, 11]))
 
 
torch.arange(13).chunk(6)

(tensor([0, 1, 2]),
 tensor([3, 4, 5]),
 tensor([6, 7, 8]),
 tensor([ 9, 10, 11]),
 tensor([12]))
 
```