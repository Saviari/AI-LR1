# AI-LR1
Однослойная нейронная сеть для распознавания цифр

Для решения задачи классификации поступающих на вход цифр применяется обучение с учителем при помощи заранее составленного датасета. Датасет состоит из чёрно-белых bmp-изображений цифр размером 28х28 пикселей. Данные изображения переводятся в матрицу, состоящую из 0 и 1, где 0 - белый пиксель, а 1 - чёрный. Для обучения используется матрица весов, где значения изменяются по правилу Хебба. При достижении определённого лимита, который устанавливается в данном случае опытным путём, цифра распознаётся верно. 
![1](https://user-images.githubusercontent.com/51208839/198050837-3913a7f9-53be-4638-882f-f1130ce76afd.png)
![2](https://user-images.githubusercontent.com/51208839/198051049-65f0d0a7-7811-4b5b-826d-4af7d5c9bd40.png)
![3](https://user-images.githubusercontent.com/51208839/198051657-198e8dc7-303a-403b-ad80-b5384a7e416c.png)
