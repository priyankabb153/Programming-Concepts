# comments

#Target : dependency
#<TAB>Command

PROJECT_NAME = all.exe
SRC = test.c\
src\sum.c\
src\square.c

INC = inc

$(PROJECT_NAME):$(SRC)
	gcc -I $(INC) $(SRC)  -o all.exe 
	
	
run : $(PROJECT_NAME)
	$(PROJECT_NAME)


#to delete all the exe files	
clean :
	rm -rf *exe
#del /q .exe didnt work