## Вариант задания 5

|Параметр | Значение по варианту
|------ | -----------
|Вид исключения | Instruction address misaligned
|Тест           | sa/rv32mi/illegal.S
|Reset Vector   | 0x2000
|Trap Vector    | 0х1880
|При обработке  | Вывод строки «illexc»


## Результаты работы

* ./results/test_results.txt - результат симуляции
* ./results/illegal.dump - дамп теста
* ./results/trace_mprf_diff_.log - трейслог MPRF
* ./results/trace_csr_.log - трейслог CSR
