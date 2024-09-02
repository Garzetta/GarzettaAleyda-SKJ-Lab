# For add_numbers
all: add_numbers

add_numbers: add_numbers.cpp
	g++ -o add_numbers add_numbers.cpp

dump: add_numbers
	objdump -d add_numbers > add_numbers.asm

clean:
	rm -f add_numbers add_numbers.asm

run: add_numbers
	./add_numbers

# For multiply_numbers
multiply: multiply_numbers

multiply_numbers: multiply_numbers.cpp
	g++ -o multiply_numbers multiply_numbers.cpp

dump_multiply: multiply_numbers
	objdump -d multiply_numbers > multiply_numbers.asm

clean_multiply:
	rm -f multiply_numbers multiply_numbers.asm

run_multiply: multiply_numbers
	./multiply_numbers

