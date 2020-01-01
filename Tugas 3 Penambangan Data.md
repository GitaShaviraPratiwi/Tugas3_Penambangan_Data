# Regresi Linear

#### Pengertian Regresi Linear[¶](https://mdandikuswanto.github.io/penambangan/license/#pengertian-regresi-linear)

Regresi linear merupakan sebuah pendekatan untuk memodelkan hubungan antara variable terikat Y dan satu atau lebih variable bebas yang disebut X. Salah satu kegunaan dari regresi linear adalah untuk melakukan prediksi berdasarkan data-data yang telah dimiliki sebelumnya. Hubungan di antara variable-variabel tersebut disebut sebagai model regresi linear. Regresi linear hanya dapat digunakan pada skala interval dan rasio. Berdasarkan penggunaan variable bebas, maka regresi linear dapat dibagi menjadi dua, yaitu regresi linear sederhana dan regresi linear berganda.

#### Macam-Macam Regresi Linear Berdasarkan Penggunaan Variabel[¶](https://mdandikuswanto.github.io/penambangan/license/#macam-macam-regresi-linear-berdasarkan-penggunaan-variabel)

Regresi linear dapat dibedakan menjadi 2 macam berdasarkan penggunaan variable bebasnya, berikut penjelasan dari kedua macam regresi linear tersebut.

###### A. Regresi Linear Sederhana

Analisis regresi linier sederhana adalah hubungan secara linear antara satu variabel independen (X) dengan variabel dependen (Y). Analisis ini untuk mengetahui arah hubungan antara variabel independen dengan variabel dependen apakah positif atau negatif dan untuk memprediksi nilai dari variabel dependen apabila nilai variabel independen mengalami kenaikan atau penurunan.. Data yang digunakan biasanya berskala interval atau rasio. Berikut adalaha persamaan umum regresi linear sederhana:


$$
Y'= a +bx
$$


Untuk mencari nilai a dan b dapat menggunakan formula seperti dibawah ini:


$$
a = \frac{\sum y(\sum x^{2})-\sum x\sum y}{n\sum x^{2}-(\sum x)^{2}}
$$

$$
b= \frac{n\sum xy - \sum x \sum xy}{n\sum x^{2} - (\sum x)^{2}}
$$



Keterangan:

- Y' = Variabel dependen (nilai yang diprediksikan)
- X = Variabel independen (variable bebas)
- a = Konstanta (nilai Y’ apabila X = 0)
- b = Koefisien regresi (nilai peningkatan ataupun penurunan)

B. Regresi Linear Sederhana

###### Analisis regresi linear berganda sebenarnya sama dengan analisis regresi linear sederhana, hanya variabel bebasnya lebih dari satu buah. Persamaan umumnya adalah:


$$
Y = a+b_{1}x_{1}+b_{2}x_{2}+b_{3}x_{3}.....+b_{n}x_{n}
$$



Untuk mencari nilai a dan b dapat menggunakan formula seperti dibawah ini:


$$
a= \frac {\sum y}{n}-b_{1}(\frac {\sum x_{1}}{n})-b_{2}(\frac {\sum x_{2}}{n})
$$

$$
b1 = \frac{(\sum x_{2}^{2})(\sum x_{1}y)-(\sum x_{1}x_{2})(\sum x_{2}y)}{(\sum x_{1}^{2})(\sum x_{2}^{2})-(\sum x_{1}x_{2})^{2}}
$$

$$
b2 = \frac{(\sum x_{1}^{2})(\sum x_{1}y)-(\sum x_{1}x_{2})(\sum x_{1}y)}{(\sum x_{1}^{2})(\sum x_{2}^{2})-(\sum x_{1}x_{2})^{2}}
$$

Keterangan :

- Y' = Variabel dependen (nilai yang diprediksikan)
- X(1,2,3,...) = Variabel independen (variable bebas)
- a = Konstanta (nilai Y’ apabila X = 0)
- b(1,2,3,...) = Koefisien regresi (nilai peningkatan ataupun penurunan)

Berikut contoh kasus penyelesaian regresi linear berganda :

| x1        | x2                               | y      | x1^2   | x2^2   | x1.x2     | x1.y   | x2.y   |
| :-------- | :------------------------------- | :----- | :----- | :----- | :-------- | :----- | :----- |
| 3         | 4                                | 4      | 9      | 16     | 12        | 12     | 16     |
| 2         | 1                                | 5      | 4      | 1      | 2         | 10     | 5      |
| 3         | 3                                | 9      | 9      | 9      | 9         | 27     | 27     |
| 4         | 2                                | 11     | 16     | 4      | 8         | 44     | 22     |
| **12**    | **8**                            | **29** | **38** | **30** | **31**    | **93** | **70** |
|           |                                  |        |        |        | **23025** |        |        |
|           |                                  |        |        |        |           |        |        |
| 6         | 4                                | y ?    |        |        |           |        |        |
|           |                                  |        |        |        |           |        |        |
| b1        | -0,88235                         |        |        |        |           |        |        |
| b2        | -89,4118                         |        |        |        |           |        |        |
| a         | 367,3235                         |        |        |        |           |        |        |
|           |                                  |        |        |        |           |        |        |
| Persamaan | y=a+b1x1+b2x2                    |        |        |        |           |        |        |
|           | y=367,3235+(-5,29412)+(-357,647) |        |        |        |           |        |        |
| y         | 4,382353                         |        |        |        |           |        |        |