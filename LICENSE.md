##def find_sum_of_elements(arr, k, l):
##    if k < 1 or l > len(arr) or k > l:
##        return "Некорректные значения K и L"
##    
##    sum_of_elements = 0
##    for i in range(k-1, l):
##        sum_of_elements += arr[i]
##    
##    return sum_of_elements
##
##arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
##k = 3
##l = 7
##result = find_sum_of_elements(arr, k, l)
##print("Сумма элементов массива с номерами от", k, "до", l, "включительно:", result)

##Array21. Дан массив размера N и целые числа K и L (1 ≤ K ≤ L ≤ N). Найти среднее арифметическое элементов массива с номерами от K до L h

##def find_average_of_elements(arr, k, l):
##    if k < 1 or l > len(arr) or k > l:
##        return "Некорректные значения K и L"
##    
##    sum_of_elements = 0
##    num_of_elements = l - k + 1
##    for i in range(k-1, l):
##        sum_of_elements += arr[i]
##    
##    average = sum_of_elements / num_of_elements
##    return average
##
##arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
##k = 3
##l = 7
##result = find_average_of_elements(arr, k, l)
##print(k, "до", l, "включительно:", result)

##Array22. Дан массив размера N и целые числа K и L (1 < K ≤ L ≤ N). Найти сумму всех элементов массива, кроме элементов с номерами от K до L включительно.
##
##def find_sum_except_range(arr, k, l):
##    if k < 1 or l > len(arr) or k > l:
##        return "Некорректные значения K и L"
##    
##    sum_except_range = 0
##    for i in range(len(arr)):
##        if i < k-1 or i > l-1:
##            sum_except_range += arr[i]
##    
##    return sum_except_range
##
##arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
##k = 3
##l = 7
##result = find_sum_except_range(arr, k, l)
##print("от", k, "до", l, "включительно:", result)
