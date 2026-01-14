# Delete Book Record

```python
from bookshelf.models import Book

book = Book.objects.get(title="Rich dad poor dad")
book.delete()
Book.objects.all()
