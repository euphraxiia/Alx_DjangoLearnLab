# Delete

**Command**
```python
from bookshelf.models import Book
b = Book.objects.get(title="Nineteen Eighty-Four")
b.delete()
print(list(Book.objects.all()))
```

**Output**
```
[]
```

