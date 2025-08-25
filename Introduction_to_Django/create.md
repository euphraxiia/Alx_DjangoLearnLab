# Create

**Command**
```python
from bookshelf.models import Book
b = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
print(b.id, b.title, b.author, b.publication_year)
```

**Output**
```
2 1984 George Orwell 1949
```

