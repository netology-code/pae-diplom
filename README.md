# Дипломный проект профессии «Инженер по автоматизации»

## Автоматизированная система управления

### Цель проекта

Цель дипломного проекта - разработка АСУ ТП для учебного объекта.

Вам предстоит:

- собрать контроллеры и сервера
- спроектировать и настроить промышленную сеть
- разработать приложения для SCADA и PLC
- оформить документацию.

------

### Чеклист готовности к работе над проектом

1. Установите пакет TIA Portal

<details>
  <summary> Подсказка по установке TIA Portal V13 с официального ресурса Siemens (доступна по клику)</summary>

1. Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему. Процесс регистрации описан в [соответствующей инструкции](https://docs.google.com/presentation/d/1RPHvCE2OxBbHRMWSAV2E-HxscZvR2nRIZVHCy8hvjJE/edit?usp=sharing).
2. Загрузите и установите программное обеспечение для создания проекта PLC Siemens, входящее в состав пакета TIA Portal с [официального ресурса Siemens](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE). 
3. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109745155/simatic-step-7-including-plcsim-v13-sp2-trial-download?dti=0&lc=en-DE) в две отдельные папки:
  - STEP 7 Professional V13 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_1.png)
  - SIMATIC STEP 7 PLCSIM V13 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_2.png)
4. Запустите установочный файл SIMATIC_STEP_7_Professional_V13_SP2_Upd4.exe, пройдите стандартную процедуру установки.
5. Запустите установочный файл SIMATIC_S7_PLCSIM_V13_SP2.exe, пройдите стандартную процедуру установки.  
  
*ОБРАТИТЕ ВНИМАНИЕ! Устанавливается демо-версия программы. Функционал будет ограничен спустя 21 день после установки. Рекомендуется установка софта на виртуальной машине. Как это сделать, описано в [инструкции](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing).*

</details>

2. Скачайте [MasterSCADA 4D](https://masterscada.ru/download4) согласно [инструкции](https://docs.google.com/document/d/13jDH8mqTwOePICQuc0o2sfBaAQhGyeZ0rGnzL_DHZ8o/edit?usp=sharing), проведите установку ПО.
*Примечание: использование MasterSCADA 4D является рекомендованным, блок работы с проектом в SCADA можно выполнить в любом ПО SCADA (укажите в шаблоне название и версию ПО, приложите соответствующие файлы и скрины проекта)*
3. Установите платформу nanoCAD, зарегистрируйте её, используя [инструкцию](https://docs.google.com/presentation/d/1E5cgmdySQHRs7mX5v0GNZqZWmRzVVc3osXE2-queDwk/edit?usp=sharing)

Если все этапы чеклиста пройдены, то можете стартовать работу над проектом. Успехов в работе!

------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [TIA Portal v13](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE)
2. [Инструкция по созданию виртуальной машины](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing)
3. [ГОСТ 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85)
4. [MasterSCADA 4D](https://masterscada.ru/download4).
4. [Инструкция по загрузке ПО MastersSCADA 4D](https://docs.google.com/document/d/13jDH8mqTwOePICQuc0o2sfBaAQhGyeZ0rGnzL_DHZ8o/edit?usp=sharing).
5. [Инструкция к установке платформы nanoCAD](https://docs.google.com/presentation/d/1E5cgmdySQHRs7mX5v0GNZqZWmRzVVc3osXE2-queDwk/edit?usp=sharing)
6. [Техническое задание](https://docs.google.com/document/d/1TBjyVoP65fEyx6a2ZjyQarB16WyLETFiQP5SEh9pq4U/edit?usp=sharing)
7. [Шаблон спецификации](https://docs.google.com/spreadsheets/d/1BdMG-EkZNaT82Bf-Lh1p2s9I25VJAvjZV7f9jB9GtuQ/edit?usp=sharing)
8. [Шаблон для дипломного проекта](https://docs.google.com/document/d/1syuRp_KMY9Vj1X58U7BP1Kn0W9HTMInL4Ahvn2P5W7Q/edit?usp=sharing)

------

### Инструкция к работе над проектом

1. Выполните установку необходимых программных инструментов из **Чеклиста готовности к курсовой работе**.
2. Сделайте копию [Шаблона для дипломного проекта](https://docs.google.com/document/d/1syuRp_KMY9Vj1X58U7BP1Kn0W9HTMInL4Ahvn2P5W7Q/edit?usp=sharing) себе на Google Диск.
3. Зайдите в «Настройки доступа» скопированного вами шаблона и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. В названии файла введите вашу фамилию и имя.
5. В соответствии с [техническим заданием](https://docs.google.com/document/d/1TBjyVoP65fEyx6a2ZjyQarB16WyLETFiQP5SEh9pq4U/edit?usp=sharing) спроектируйте учебный проект АСУ ТП.
6. Сохраните файлы проекта и документацию на своём Google диске.
7. Вставьте в соответствующие абзацы вашего «Шаблона для дипломного проекта» ссылки на файлы и необходимые скрины выполненного задания.
8. Для проверки дипломного проекта преподавателем отправьте ссылку на ваш документ в личном кабинете.
9. Любые вопросы по решению заданий задавайте в чате учебной группы.

#### **Дополнительное задание к проекту (необязательное)** *

ПО  объектового контроллера, основными задачами которого являются (если исполнитель готов участвовать в дополнительном тендере):
- реализация алгоритмов ТП
- сбор и обработка показаний датчиков
- передача всех типов информации в SCADA.

*Примечание: рекомендуем на этапе проектирования схемы проекта направить его на проверку дипломному руководителю отдельно; и только после изучения руководителем приступить к следующим этапам проектирования*

------

### Роадмап

- 1 неделя
- 2 неделя
- 3 неделя
- 4 неделя

------

### Правила сдачи работы

1. Отправлена ссылка на документ (Google Doc) с выполненным заданием в личном кабинете.
2. Документ размещён на личном Google Диске.
3. К документу настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка».

------

### Критерии оценки



