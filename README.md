# Pyomo-Worker-usecase

Modeling and optimization of a weekly workforce with Python and Pyomo

Problem description

A new food store has been opened at the University Campus which will be open 24 hours a day, 7 days a week. Each day, there are three eight-hour shifts. Morning shift is from 6:00 to 14:00, evening shift is from 14:00 to 22:00 and night shift is from 22:00 to 6:00 of the next day.

During the night there is only one worker while during the day there are two, except on Sunday that there is only one for each shift. Each worker will not exceed a maximum of 40 hours per week and have to rest for 12 hours between two shifts.

As for the weekly rest days, an employee who rests one Sunday will also prefer to do the same that Saturday.

In principle, there are available ten employees, which is clearly over-sized. The less the workers are needed, the more the resources for other stores.
