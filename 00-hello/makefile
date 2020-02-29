hello: hello.c
	$(info Building $?)
	cc -o $@ $?

clean:
	$(warning Removing hello)
	rm hello

r2: hello
	$(info Opening $? in radare2)
	r2 $?

help:
	$(info The available targets are:)
	$(info build     - (default) compile hello.c)
	$(info r2        - open radare2 on compilation result)
	$(info clean     - remove all compilation results)

