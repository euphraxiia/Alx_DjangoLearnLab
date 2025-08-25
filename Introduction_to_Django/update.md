# Update

**Command**
```python
from bookshelf.models import Book
b = Book.objects.get(title="1984")
b.title = "Nineteen Eighty-Four"
b.save()
print(b.id, b.title, b.author, b.publication_year)
```

**Output**
```
2 Nineteen Eighty-Four George Orwell 1949
```

