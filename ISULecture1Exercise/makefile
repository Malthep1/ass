exename = helloworld
depencendies = main.o
all: $(depencendies)
	$(CXX) $< -o $(exename)

.PHONY: clean help
clean:
	rm *.o $(exename)	

help:
	echo $(depencendies)