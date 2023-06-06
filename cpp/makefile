RUN = 
IN = < in.txt
OUT = > out.txt
COMPAILE = -std=gnu++17 -Wall -Wextra -O2 -o main.exe 

run: main.exe
	./main.exe $(RUN)

in : main.exe
	./main.exe $(IN) $(RUN)

out : main.exe
	./main.exe $(OUT) $(RUN)

in-out : main.exe
	./main.exe $(IN) $(OUT) $(RUN)

main.exe: main.cpp
	g++  main.cpp $(COMPAILE)

delete:
	rm main.exe
