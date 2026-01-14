# CRUD Operations Using Django ORM

This document demonstrates Create, Retrieve, Update, and Delete (CRUD) operations performed on the Book model using the Django shell.

## Create

```python
from bookshelf.models import Book

book = Book.objects.create(
    title="Things fall apart",
    author="Chinua Achebe",
    publication_year=1989
)

book = Book.objects.get(title="Things fall apart")
book.tittle, book.author, book.publication_year

book - Book.pbjects.get(title="Things fall apart")
book.tittle = "Rich dad poor dad"
book.save()

book = Book.objects.get(title="Rich dad poor dad")
book.delete()
Book.objects.all()
