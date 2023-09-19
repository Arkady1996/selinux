# SELINUX
___
<b>Цель задания</b>
<p>Диагностировать проблемы и модифицировать политики SELinux для корректной работы приложений, если это требуется</p>

___

<b>Описание задания</b>
1. Запустить nginx на нестандартном порту 3-мя разными способами:
    * переключатели setsebool;
    * добавление нестандартного порта в имеющийся тип;
    * формирование и установка модуля SELinux.
2. Обеспечить работоспособность приложения при включенном selinux.
    * развернуть приложенный стенд https://github.com/mbfx/otus-linux-adm/tree/master/selinux_dns_problems;
    * выяснить причину неработоспособности механизма обновления зоны (см. README);
    * предложить решение (или решения) для данной проблемы;
    * выбрать одно из решений для реализации, предварительно обосновав выбор;
    * реализовать выбранное решение и продемонстрировать его работоспособность
