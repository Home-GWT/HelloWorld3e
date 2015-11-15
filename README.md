(Eclipse 4.3 (Kepler)) https://developers.google.com/eclipse/docs/faq >> https://dl.google.com/eclipse/plugin/4.3
(appengine-java-sdk-1.9.9.zip) https://console.developers.google.com/storage/browser/appengine-sdks/deprecated/199/?_ga=1.15314486.1815503669.1445439969&pli=1
(Google Web Toolkit (GWT) 2.6.1) http://olex.openlogic.com/packages/gwt/2.6.1
(Eclipse Platform Project 4.3) http://olex.openlogic.com/packages/eclipse/4.3


(Deploy to GAE "Google App Engine")
---------------------------------
>> http://www.mkyong.com/google-app-engine/google-app-engine-hello-world-example-using-eclipse/
   http://www.ibm.com/developerworks/ru/library/j-gaej1/
>> https://appengine.google.com/ >> "HelloWorld" >> "hello-world-112923" >> ( https://console.developers.google.com/home/activity )
>> http://hello-world-112923.appspot.com/  ( http://1-dot-hello-world-112923.appspot.com/ )


Импорт GWT-проекта в Eclipse
----------------------------
0. Есть две рабочих папки: "EclipseGit" и "EclipseProjects"

1.  (Подготовка) Клонируем проект из репозитория в "EclipseGit"
2.  Создаем пустой GWT-проект с таким-же именем в Eclipse, в рабочей папке (воркспейсе) "EclipseProjects"
3.  Делаем импорт существующегося исходного кода проекта ("File Sysytem": из папки "EclipseGit" в папку "EclipseProjects") в созданый пустой GWT-проект С критерием перезаписи текущих ресурсов.
4.  После создания каждого проекта в Eclipse устанавливает для этого проекта версию-Java (чтобы избавиться от ошибок...)
5.1 Пропуем пересобрать этот проект (компилируем...)
5.2 Идем в "Run As" >> "Run Configuration", во вклвдке "Main" выбираем наш проект. Здесь-же заходим во кладку "Arguments" и проверяем "Program arguments"...

6. Переходим на перспективу "Git"
7. Выбираем "Create a new Git Repository and add it to this view" и выбираем наш проект (из рабочей папки "EclipseProjects")
8. Возвращаемся на перспективу "Java EE"
9. В выпадающем списке (на проекте) в пункте-меню "Team" - дальше можно продолжать работу с проектом уже через GIT-репозиторий...