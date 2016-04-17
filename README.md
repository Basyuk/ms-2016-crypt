# ms-2016-crypt
Расшифровка текста

### Задание

Разработать программу, выполняющую расшифровку текста по заданному фрагменту и длине ключа.

### Требования

* Программа принимает на вход:
	- файл с зашифрованным текстом
	- файл с расшифрованным фрагментом
	- длину ключа
* Используемый алгоритм шифрования - шифр Виженера
* Желательно, чтобы программа выводила поргресс поиска ключа
* У программы должен быть параметр для вывода времени выполнения

### Пример использования

```
user@localhost:~$ decryptcuda
Usage: decryptcuda [-t] [-k] ENCRYPTED_FILE DECRYPTED_FRAGMENT_FILE KEY_LENGTH

Options:
  -t    print timings

Examples:
  decryptcuda text.txt frag.txt 8
    Bruteforce with 8-byte keys on "text.txt"
    87% done
    KEY: 0He4$k07
    decrypted text is written to "text_decrypted.txt"
```
