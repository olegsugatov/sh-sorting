# sh-sorting
ls > output - перенаправление потока в файл
cat unsorted
sort < unsorted  - сортировка из файла
sort < unsorted > sorted - перезапись отсортированных значений
cat unsorted | sort | uniq - вывод cat перенапрвить в команду sort
ls | grep test
ls | wc - показывает количество слов, строк и букв

# sh-sorting
solution.sh
cat source | grep American | sort | uniq | wc -l