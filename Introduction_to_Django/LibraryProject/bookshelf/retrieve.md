# Retrieve Example

To retrieve the book we created ("1984"):

```python
from bookshelf.models import Book

# Retrieve the book titled "1984"
book = Book.objects.get(title="1984")
print(book.title, book.author, book.publication_year)
# Output: 1984 George Orwell 1949
```
