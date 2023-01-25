# Решение задачи по анализу статистики отдела продаж
## Создание класса SalesManager.java
1. **Создадим метод public SalesManager**
```
 public SalesManager(int[] sales) {
        this.sales = sales;
    }
```
2. **Cоздадим метод max**

   ```
   public int max() {
    int max = -1;
        for (int sale : sales) {
            if (sale > max) {
                max = sale;
            }
        }
        return max;
    } 
    ```
## Добавление класса Main
1. **Создаем переменную и передаем в нее массив**
   SalesManager Manager1 = new SalesManager(new int [] {});

1. **Заполняем массив показаниями продаж каждого менеджера**
   {150, 200, 30,50,450}

1. **Затем выводим на экран наибольшее значение по каждому менеджеру**

   System.out.println ("Менеджер 1 : " + Manager1.max());

### [Ссылка проекта по адресу](https://github.com/RibTani1984/project.git) 