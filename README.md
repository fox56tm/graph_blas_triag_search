# GraphBLAS Triangle Counting

Реализация трех алгоритмов подсчета треугольников в неориентированных графах с использованием библиотеки `python-graphblas`. 

В файле `src/algorithms.py` реализованы следующие методы:

1.  **Naive Algorithm**
2.  **Burkhard Algorithm**
3.  **Sandia Algorithm**

# Установка

**Clone:**
   ```bash
   git clone [https://github.com/fox56tm/graph_blas_triag_counting.git]
   
# Настройка

   cd graph_blas_triag_counting
   uv sync
   uv run main.py
   
# Тесты

1. Пустой граф
2. Граф без треугольников
3. Граф К3

    ```bash
    uv run pytest
    

   
