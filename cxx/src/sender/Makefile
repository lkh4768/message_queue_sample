CC = g++
CFLAGS = -Wall -c -g
LFLAGS = -Wall -g
SRCS = ../Message.cxx ../PriorityMsgQueue.cxx sender.cxx
OBJS = $(SRCS:.cpp=.o) 
EXEC = sender 

$(EXEC) : $(OBJS)
	$(CC) $(LFLAGS) $(OBJS) -o $@

.cxx.o:
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm *.o $(EXEC)
