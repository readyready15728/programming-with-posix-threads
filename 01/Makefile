all: alarm alarm_fork alarm_thread

alarm:
	gcc -Wall -I../common -o alarm alarm.c

alarm_fork:
	gcc -Wall -I../common -o alarm_fork alarm_fork.c

alarm_thread:
	gcc -Wall -I../common -pthread -o alarm_thread alarm_thread.c

clean:
	rm alarm alarm_fork alarm_thread
