# Retrieve Book Record

```python
from bookshelf.models import Book

book = Book.objects.get(tittle="Things fall apart")
book.tittle, book.author, book.publication_year
