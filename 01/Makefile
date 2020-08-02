all: alarm alarm_fork alarm_thread thread_error

alarm:
	gcc -Wall -I../common -o alarm alarm.c

alarm_fork:
	gcc -Wall -I../common -o alarm_fork alarm_fork.c

alarm_thread:
	gcc -Wall -I../common -pthread -o alarm_thread alarm_thread.c

thread_error:
	gcc -Wall -I../common -pthread -o thread_error thread_error.c

clean:
	rm -f alarm alarm_fork alarm_thread thread_error
