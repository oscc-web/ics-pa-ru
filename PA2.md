
<!-- # PA2 - Simple and complex machines: von Neumann computer systems -->

# PA2 - Простые и сложные машины: компьютерные системы фон Неймана

<!-- > #### flag::The Story of the Birth of the World - Chapter 2
> Pioneers have created Turing machines But what can a simple machine built with just a few digital circuit modules do? The pioneer said that all infinite possibilities are contained within it. -->

> #### flag::История рождения мира — Глава вторая
> Первопроходец уже создал машину Тьюринга. Но что может сделать столь простая машина, собранная всего из нескольких модулей цифровых схем? Первопроходец сказал: все бесконечные возможности уже заключены в ней.

<!-- > #### danger::Code Management
> Before proceeding with this PA, please execute the following command in the engineering directory to branch and organize, otherwise it will affect your grades: -->

> #### danger::Управление кодом
> Перед началом этого PA выполните следующие команды в каталоге проекта, чтобы привести ветки в порядок. Если этого не сделать, это может повлиять на вашу оценку:
```
git commit --allow-empty -am "before starting pa2"
git checkout master
git merge pa1
git checkout -b pa2
```

<!-- > #### danger::Submission requirements (please carefully read the following content. If there is any violation, the consequences will be borne by oneself)
> **<u>Expected average time</u>**: 40 hours
>
> **<u>Periodic arrangements</u>**:
> * Task PA2.1: Implement more instructions to run most `cpu-tests` in NEMU
> * Task PA2.2: Implementing klib and infrastructure
> * Task PA2.3: Run FCEUX and submit a complete experimental report -->

> #### danger::Требования к сдаче (пожалуйста, внимательно прочитайте следующее. Любое нарушение — на вашей ответственности)
> **<u>Ожидаемое среднее требуемое время</u>**: 40 часов
>
> **<u>Поэтапный план</u>**:
> * Task PA2.1: Реализовать больше инструкций, в NEMU запустить большую часть `cpu-tests`
> * Task PA2.2: Реализовать klib и инфраструктуру
> * Task PA2.3: Запустить FCEUX, сдать полный лабораторный отчёт
