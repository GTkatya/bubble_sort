# bubble_sort
Сортировка пузырьком
1. Функция bubbleSort принимает массив arr и его размер size.
2. Алгоритм пузырьковой сортировки состоит из двух вложенных циклов:
   - Внешний цикл for (i = 0; i < size - 1; i++) выполняется size - 1 раз (для сортировки всего массива).
   - Внутренний цикл for (j = 0; j < size - i - 1; j++) выполняется size - i - 1 раз (для прохода по оставшейся неотсортированной части массива).
3. Внутри внутреннего цикла производится сравнение соседних элементов arr[j] и arr[j + 1]. Если arr[j] больше arr[j + 1], то элементы меняются местами.
4. В функции main создается массив arr, его размер вычисляется, выводится исходный массив, вызывается функция bubbleSort для сортировки, и выводится отсортированный массив.
