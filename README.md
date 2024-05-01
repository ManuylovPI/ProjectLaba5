Project: ProjectLaba5

В данном проекте представлена модель трехзвенного манипулятора, движение каждого звена описывается с помощью модели привода.


В проекте есть следующие директории:
data:
 - ActuatorConstants: содержит параметры приводов для каждого звена
models:
 - FirstLink.slx - модель первого звена
 - SecondLink.slx - модель второго звена
 - ThirdLink.slx - модель третьего звена
 - Laba6 - главная модель/модель манипулятора
scripts:
 - Initialization:
    - LoadConstants.m - загружает все необходимые константы в Workspace проекта
 - Deinitialization:
    - ClearTrash.m - очищает ненужные временные файлы
    - UnloadProject.m - выгружает все константы из Workspace проекта
tests:
 - ProjectLaba5.mldatx - информация о данных для тестирования привода первого звена
 - Laba6_Harness4_HarnessInputs.mat - информация о входных значения тестов
 - Laba6_Harness4.slx - модель Harness для привода первого звена
Шорткаты:
 - Laba6 - запускает главную модель проекта
 - LoadConstants - загружает все необходимые константы в Workspace проекта
 - UnloadProject - выгружает все константы из Workspace проекта

git репозиторий https://github.com/ManuylovPI/ProjectLaba5
