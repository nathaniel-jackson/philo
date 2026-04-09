# Philosophers

42 Project

Philosophers is a multi threading practice project.
The requirements are as follows:
- There are a number a philosophers around a table, each represented by a thread.
- There is an equal number of forks represented by a value with a corresponding mutex, with each philosopher able to see one to the right, and one to the left.
- Each philosopher needs to eat, otherwise they die after some amount of time.
- The philosophers take some amount of time to eat.
- After eating, they will sleep for a different amount of time.
- Upon waking up, they will begin thinking.
- If any philosopher dies, the program terminates.
- Optionally, after each philosopher has eaten a certain amount of meals, the program terminates.

You must keep the philosophers alive as long as possible, or until they've all eaten their required meals.

The program is run as follows:

`./philo \{num_philo} \{time_to_die} \{time_to_eat} \{time_to_sleep} \[num_meals]`

All the times are in milliseconds.
