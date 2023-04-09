# Левостороннее красно-черное дерево + метод добавления новых элементов с балансировкой.

## Красно-черное дерево имеет следующие критерии:
- Каждая нода имеет цвет (красный или черный)

- Корень дерева всегда черный

- Новая нода всегда красная

- Красные ноды могут быть только левым ребенком

- У красной ноды все дети черного цвета


> Чтобы данные условия выполнялись, после добавления элемента в дерево происходит балансировка, благодаря которой все критерии выше станут валидными. Для балансировки существует 3 операции – левый малый поворот, правый малый поворот и смена цвета.