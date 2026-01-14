# Update Book Record

```python
from bookshelf.models import Book

book - Book.pbjects.get(title="Things fall apart")
book.tittle = "Rich dad poor dad"
book.save()
