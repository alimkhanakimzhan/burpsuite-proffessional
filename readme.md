#Burp Suite Professional instr. alimkhan

Download a RAR archive

1) Разархивировать tar
2) Переместим наши два .jar файла в папку "jre1.8.0_291/bin"
3) Откроем эту папку через терминал и пропишем "java -jar BurpLoaderKeygen.jar"
4) Откроем новое окно терминала и пропишем "java -javaagent:BurpLoaderKeygen.jar -noverify -jar burpsuite_pro_v2020.11.3.jar"
5) Вставляем наш license key, в BurpSuite, получаем Activation Request key
6) Вставляем этот ключ в BurpLoader, получаем наш Activation Response Key, который вставляем в BurpSuite.
7) Готово! Мы активировали лицензию.

Примечание:
Чтобы запустить BurpSuite Pro., нужно прописывать каждый раз  "java -javaagent:BurpLoaderKeygen.jar -noverify -jar burpsuite_pro_v2020.11.3.jar" 

Commands list (ASC):
1) tar zxvf jre-8u291-linux-x64.tar.gz   
2) java -jar BurpLoaderKeygen.jar
3) java -javaagent:BurpLoaderKeygen.jar -noverify -jar burpsuite_pro_v2020.11.3.jar
