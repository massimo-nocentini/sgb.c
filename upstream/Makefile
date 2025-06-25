
fetch:
	wget https://cs.stanford.edu/pub/sgb/sgb.tar.gz
	mkdir -p ../src
	cp sgb.tar.gz ../src/
	cd ../src && tar xf sgb.tar.gz && rm sgb.tar.gz

build:
	cd ../src/ && make clean && make tests && sudo make install