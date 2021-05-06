# Modyfikacje obrazu w oparciu o filtry wyostrzające i statyczne

## Na początku wczytuję klasę grayscale1, która będzie modyfikowała obraz w oparciu o filtry wyostrzające i statyczne. Klasa ta pobiera zdjęcie (nazwa: widok.jpg).

* zdjęcie przed modyfikacjami:

![widok](https://user-images.githubusercontent.com/80594097/117310520-a3622880-ae83-11eb-92db-368f3daf5c9c.jpg)


## Na początku na zdjęciu modyfikowany jest filtr wyostrzający w oparciu o:

* operator Robertsa (dla gradientu pionowego i poziomego):

![Roberts](https://user-images.githubusercontent.com/80594097/117310463-96ddd000-ae83-11eb-95a5-43e9e27678d5.jpg)


* operator Prewitta (dla gradientu pionowego):

![Prewitt(pion)](https://user-images.githubusercontent.com/80594097/117310886-ffc54800-ae83-11eb-8d9c-874849f6ff48.jpg)


* operator Prewitta (dla gradientu poziomego):

![Prewitt(poziom)](https://user-images.githubusercontent.com/80594097/117310890-005dde80-ae84-11eb-8b7b-4bc16b98275f.jpg)


* operator Sobela (dla gradientu pionowego):

![Sobel(pion)](https://user-images.githubusercontent.com/80594097/117311136-38652180-ae84-11eb-87e9-586c52f2908d.jpg)


* operator Sobela (dla gradientu poziomego): 

![Sobel(poziom)](https://user-images.githubusercontent.com/80594097/117311141-38fdb800-ae84-11eb-9834-5d728d92ddc0.jpg)


* operator Laplace'a:

![Laplace'a](https://user-images.githubusercontent.com/80594097/117311298-5df22b00-ae84-11eb-8dc3-ba43cbb4d19b.jpg)



Następnie na zdjęciu modyfikowane są filtry statystyczne w oparciu o:

* filtr minimum:

* filtr maksimum:

* filtr medianowy:
