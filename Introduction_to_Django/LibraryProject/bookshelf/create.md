# Create Book Record

```python
from bookshelf.models import Book

book = Book.objects.create(
    title="Things fall apart",
    author="Chinua Achebe",
    publication_year=1989
)
