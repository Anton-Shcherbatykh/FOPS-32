# FOPS-32
## Shcherbatykh A.E. 8-01-HW
### Задание 1
1. Зарегистрируйте аккаунт на GitHub.
2. Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_1_2.jpg)
3. Склонируйте репозиторий, используя https протокол git clone ....
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_3.jpg)
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
6. Выполните команду git status и запомните результат.
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_4_5_6.jpg)
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
8. Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_7_8.jpg)
9. Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
11. Ещё раз выполните команды git diff и git diff --staged.
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_9_10_11.jpg)
12. Теперь можно сделать коммит git commit -m 'First commit'.
13. Сделайте git push origin master
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_12_13.jpg)


### Задание 2
1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_1.jpg)
2. Добавьте файл .gitignore в следующий коммит git add...
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_2.jpg)
3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_3.jpg)
4. Сделайте коммит и пуш
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_4.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_4_1.jpg)


### Задание 3

1. Создайте новую ветку dev и переключитесь на неё.
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_1.jpg)
2. Создайте в ветке dev файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_2_%26_3.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_3_1.jpg)
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_3_2.jpg)
4. Переключитесь на основную ветку.
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_5.jpg)
   
6. Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
   
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_8_1.jpg)
   
7. Сделайте пуш в основной ветке.
8. Не удаляйте ветку dev.
   
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_7.jpg)
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_8.jpg)
   
