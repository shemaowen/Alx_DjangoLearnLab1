# Delete Operation

## Python Command:
# Delete the retrieved book
book.delete()

# Confirm the deletion by checking the count of books in the database
all_books = Book.objects.all()
print(all_books)