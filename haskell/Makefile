clean:
	rm -f src/out/*.o src/*.hi src/out/main

build: src/main.hs
	ghc -o src/out/main src/main.hs

run: build
	./src/out/main