# Retrieve Example

from bookshelf.models import Book

# Retrieve one book by ID

book = Book.objects.get(id=1)
print(book.title, book.author, book.publication_year)
