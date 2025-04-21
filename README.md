# FOPS-32
## Shcherbatykh A.E. 8-03-HW
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
Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_7_8.jpg)
Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
Ещё раз выполните команды git diff и git diff --staged.
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_9_10_11.jpg)
Теперь можно сделать коммит git commit -m 'First commit'.
Сделайте git push origin master
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32/blob/main/images/%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_12_13.jpg)
