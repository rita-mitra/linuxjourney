# find

## Lesson Content

Со всеми теми файлами, которые есть у вас в системе, вам нужно подсуетиться, чтобы найти какой-то один. Для этого мы можем использовать команду find (найти)!

<pre>$ find /home -name puppies.jpg</pre>

Для find вам нужно задать директорию, в которой вы будете искать, и что вы хотите найти, в этом случае мы пытались найти файл по имени puppies.jpg.

Вы можете указать тип файла, который вы пытетесь найти.

<pre>$ find /home -type d -name MyFolder</pre>

Как видите, я указал тип файла, который я ищу как директорию (d) и имя MyFolder.

Есть одна крутая вещь, find не останавливается на поиске только внутри данной директории, а продолжает искать то, что вы ищете внутри подкаталогов, которые могут быть в директории.

## Exercise

<ol>
<li>Найдите файл из корневой директории, у которого в названии есть слово net.</li>
</ol>

## Quiz Question

Какую опцию нужно указать, если я хочу искать по имени?

## Quiz Answer

-name