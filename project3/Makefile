all:
	gcc -g -o sim *.c
clean:
	rm -f sim && rm -f result.txt && rm -f output_memory_map.txt
run:
	rm -f ../logs/test.txt && rm -f sim && gcc -g -o sim *.c && clear && ./sim ../programs/program1.txt pipeline > result.txt
run2:
	rm -f ../logs/test.txt && rm -f sim && gcc -g -o sim *.c && clear && ./sim ../programs/p2_program4.txt pipeline > result.txt
compare:
	diff -iw ../cao2/program1_result.txt ../logs/test.txt
