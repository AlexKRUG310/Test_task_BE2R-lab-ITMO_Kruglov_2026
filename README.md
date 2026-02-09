## Тематика задания: RL for locomotion incl. sim-to-real gap, energy-efficient locomotion, hierarchical systems, and physically-consistent pipelines  
Задача: подобрать наиболее релевантные статьи на выбранную тему. 
Найти и обосновать открытую проблему, заслуживающую внимания, и сформулировать гипотезу для преодоления этого барьера. 

Выполнил: Круглов А. С. 
  
### Рассматриваемые статьи:  
Рассмотренные в задании статьи находятся в папке Articles -> Used

1. Ashish Kumar, Zipeng Fu, Deepak Pathak, Jitendra Malik. RMA: Rapid motor adaptation for legged robots. Robotics: Science and Systems, 2021.
2. L. Smith, J. C. Kew, X. Bin Peng, S. Ha, J. Tan and S. Levine, "Legged Robots that Keep on Learning: Fine-Tuning Locomotion Policies in the Real World," 2022 International Conference on Robotics and Automation (ICRA)
3. A. Loquercio, A. Kumar and J. Malik, "Learning Visual Locomotion with Cross-Modal Supervision," 2023 IEEE International Conference on Robotics and Automation (ICRA)

### Связанные со статьями репозитории:
1. RMA - https://github.com/antonilo/rl_locomotion
2. FT - https://github.com/lauramsmith/fine-tuning-locomotion
3. CMS - https://github.com/antonilo/vision_locomotion

Подробный анализ данных статей c рассмотрением недостатков каждого решения и гипотизами для их преодоления содержится в файле Test_task_Kruglov_A.S.pdf

Статьи, глубокий анализ которых не проводился, но в которых также рассматривается указанная тематика находятся в папке Articles -> Unused  

## Реализация метода Fine-Tuning
Были проведены обучение и развертывание в симуляции модели робота Unitree A1 в соответствии с инструкциями, содержащимися в связанном со статьей репозитории. 

Общее время обучения: 5 ч. 32 мин.

Далее приведено разваитиие политики на разных итерациях обучения.

![Итерация 1](Demonstrations/Demo_1.gif)
![Итерация 260](Demonstrations/Demo_260.gif)
![Итерация 450](Demonstrations/Demo_450.gif)
![Итерация 900](Demonstrations/Demo_900.gif)