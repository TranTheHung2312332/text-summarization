# Bài tập lớn Phân tích và khai phá dữ liệu văn bản PTIT

## Cách sử dụng Dataset (Đã chia)

```
from datasets import load_from_disk

dataset = load_from_disk("vietnamese_summarization_split")

train = dataset['train'].to_pandas()
```