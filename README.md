# Learning Seed in Python

```python
import random
import numpy as np
import torch

seed = 444

random.seed(seed)
np.random.seed(seed)
torch.manual_seed(seed)
```

## Credits

- [pytorch | REPRODUCIBILITY](https://pytorch.org/docs/stable/notes/randomness.html)
