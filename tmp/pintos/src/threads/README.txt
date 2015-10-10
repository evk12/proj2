Ethan Koch
8/28/15

CIS 520 9:30-10:20
Project 0

Files Added:
cis520/pintos/src/tests/threads/alarm-mega.ck

Files Changed:
cis520/pintos/src/tests/threads/alarm-wait.c

	void
	test_alarm_mega (void)
	{
	  test_sleep (5, 70);
	}

cis520/pintos/src/tests/threads/Make.tests

	added "alarm-mega" to following line:
	alarm-many alarm-mega alarm-multiple alarm-simultaneous alarm-priority alarm-zero	\

cis520/pintos/src/tests/threads/tests.c

	added following line:
	{"alarm-mega", test_alarm_mega},

cis520/pintos/src/tests/threads/tests.h

	added following line:
	extern test_func test_alarm_mega;

cis520/pintos/src/tests/threads/Rubric.alarm

	added following line:
	4	alarm-mega
