# ideomatTIMP

  скачали библиотеку boost с помощью утилиты wget
![image](https://user-images.githubusercontent.com/90716549/156234690-6750c422-298a-44e3-bc63-e1c38781d88a.png)

  разархивировали скаченный файл в директорию ~/boost_1_69_0 с помощью команды tar -xf boost_1_69_0_tar
![image](https://user-images.githubusercontent.com/90716549/156236227-aecbca22-32e0-4c72-b3b3-2d2e561eb881.png)
 
 Подсчитаем количество файлов в директории ~/boost_1_69_0 не включая вложенные директории с помо
 щью команды tree boost_1_69_0 -L 1
![image](https://user-images.githubusercontent.com/90716549/156236782-2bc8152a-423c-4540-a244-acf9f29c9001.png)

Подсчитаваем количество файлов в директории ~/boost_1_69_0 включая вложенные директории с помощью команды tree boost_1_69_0 
![image](https://user-images.githubusercontent.com/90716549/156315114-fe5dcf2a-2745-4e83-af21-27044cab2768.png)

Подсчитаем количество заголовочных файлов, файлов с расширением .cpp,  с момощю команды -P "*.cpp"
![image](https://user-images.githubusercontent.com/90716549/156318296-8f3d043e-c6b7-4975-8a12-c01f7ea8e02a.png)


сколько остальных файлов (не заголовочных и не .cpp). с помощью команды -I ".cpp|.hpp"
![image](https://user-images.githubusercontent.com/90716549/156318006-bc21f937-cabd-4896-b19c-50625af315dc.png)

найдем полный пусть до файла any.hpp внутри библиотеки boost с помощью команды find ./boost_1_69_0 -name "any.hpp"
![image](https://user-images.githubusercontent.com/90716549/156318866-3eeed329-f29d-4aa3-8af9-a9fa525b32a1.png)

Выведем в консоль все файлы, где упоминается последовательность boost::asio с помощью команды  grep -rL "boost::asio"
![image](https://user-images.githubusercontent.com/90716549/156319633-67d63208-53a7-466c-80a6-c0bc2d155005.png)




