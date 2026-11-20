diary = []
while True:
    def show_menu():
        print("Привет! я Читательский Дневник")
        print("1 - Добавить книгу")
        print("2 - Показать все книги")
        print("3 - Показать последние 5 прочитанных книг")
        print("4 - Заменить название по номеру")
        print("5 - поиск по названию")
        print("6 - Статистика")
        print("0 - Выход")
    def add():
        name_book = input("Введите название книги: ")
        diary.append(name_book)
    def show():
        print(diary)
    def last_five():
        print(diary[-5:])
    def replace():
        change1 = input("Введите книгу на замену: ")
        change2 = input("Введите книгу для замены: ")
        diary[diary.index(change1)] = change2
    def search():
        find_book = int(input("Введите цифру по которой хотите найти книгу: "))
        print(diary[find_book - 1])
    def states():
        print("Статистика: ")
        print("Это все книги которые были добавлены самые последние: ")
        print(diary[-2:])
    print("Меню(10), Выход(0)")
    operation = int(input("Выберете операцию: "))
    if operation == 0:
        print('оК')
        break
    elif operation == 1:
        add()
    elif operation == 2:
        show()
    elif operation == 3:
        last_five()
    elif operation == 4:
        replace()
    elif operation == 5:
        search()
    elif operation == 6:
        states()

    elif operation == 10:
        show_menu()
    else:
        print("Операция не найдена!")
