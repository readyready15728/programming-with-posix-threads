all: mutex_static mutex_dynamic alarm_mutex trylock backoff

mutex_static:
	gcc -Wall -I../common -pthread -o mutex_static mutex_static.c

mutex_dynamic:
	gcc -Wall -I../common -pthread -o mutex_dynamic mutex_dynamic.c

alarm_mutex:
	gcc -Wall -I../common -DDEBUG -pthread -o alarm_mutex alarm_mutex.c

trylock:
	gcc -Wall -I../common -pthread -o trylock trylock.c

backoff:
	gcc -Wall -I../common -DDEBUG -pthread -o backoff backoff.c

clean:
	rm -f mutex_static mutex_dynamic alarm_mutex trylock backoff
