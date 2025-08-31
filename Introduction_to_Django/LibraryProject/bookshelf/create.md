from bookshelf.models import Book
book = Book.objects.create(title="1984", author="George Orwell")
book.save()

# Output: <Book: 1984>
