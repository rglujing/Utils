
all:bin testOSPlatform
bin:
	mkdir -p bin
testOSPlatform:testOSPlatform.cpp
	g++ -o $@ $<
	mv $@ bin/

clean:
	rm -rf ./bin
