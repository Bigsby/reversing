foring: foring.c
	$(info Building $?)
	cc -o $@ $?

debug: foring.c
	$(infor Building $? for debug)
	cc -g -o $@ $?

clean:
	$(warning Removing foring)
	rm foring

r2: foring
	$(info Opening $? in radare2)
	r2 $?

help:
	$(info The available targets are:)
	$(info build     - (default) compile foring.c)
	$(info debug     - compile foring.c with debug symbols)
	$(info r2        - open radare2 on compilation result)
	$(info clean     - remove all compilation results)

