# Venture Capital Funding Analysis
---

# Technologies

```python
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```
---

# Analysis Information

Original Model:
Hidden layer 1: 16, relu
Hidden layer 2: 12, relu
Output layer: linear
Loss: 0.6414
Accuracy: 0.7284

Alternative Model 1:
Hidden layer 1: 28, relu
Hidden layer 2: 8, relu
Output layer: linear
Loss: 0.6249
Accuracy: 0.7280

Alternative Model 2:
Hidden layer 1: 40, relu
Hidden layer 2: 14, relu
Output layer: linear
Loss: 0.6025
Accuracy: 0.7268

---

# Contributors

This Analysis is brought to you by `billybishop21`

---

# License

MIT License

Copyright (c) 2021 `billybishop21`

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---