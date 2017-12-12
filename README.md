# Построение ирисов Фишера, точки на R.

## Код:
>colors <- c("setosa" = "red", "versicolor" = "green3", "virginica" = "blue") <br/>
>plot(iris[, 3:4], pch = 21, bg = colors[iris$Species], col = colors[iris$Species]) <br/> 
>points(4,1/2,pch=22,bg="black",col="black")

## Описание:<br/> 
  Функция plot строит графическое представление ирисов.
points задает точку с координатами 4 и 0.5, выделяя черным цветом, нанесем ее в форме квадрата 
на график.

## Результат вывода:

![alt text](https://github.com/dmitrail/IRISI-BUILDING/blob/master/IRISI.png)
