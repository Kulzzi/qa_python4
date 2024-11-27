# qa_python_4: юнит-тестирование

Приложение **BooksCollector** позволяет установить жанр книг и добавить их в избранное.
Данное приложение покрыто 15 юнит-тестами (с параметризацией), написанными на языке **Python**.
Покрытие тестами на уровне методов составляет 100%, на уровне класса - 29%.

**Список юнит-тестов**:
+ test_add_new_book_add_two_books
+ test_add_new_book_add_two_same_books_add_only_one
+ test_add_new_book_incorrect_name_error
+ test_set_book_genre_choose_genre_from_list
+ test_set_book_genre_choose_genre_not_from_list_error
+ test_get_book_genre_book_with_genre_get_genre
+ test_get_book_genre_book_with_no_genre_get_empty_string
+ test_get_books_with_specific_genre_get_list_with_genre_filter
+ test_get_books_for_children_not_from_age_rating_get_list
+ test_get_books_for_children_from_age_rating_get_empty_list
+ test_add_book_in_favorites_add_same_two_books_add_only_one
+ test_delete_book_from_favorites_delete_book_get_empty_list

Для запуска тестов выполните команду:\
*pytest -v tests.py*

