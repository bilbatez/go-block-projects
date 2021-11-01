FILENAME = lissajous

.SILENT: create clean

clean:
	if [ -d ./out ]; then rm -rf ./out; fi
	echo "clean 'out' directory"

create: main.go
	mkdir -p out
	go run . > ./out/$(FILENAME).gif
	echo "created" $(FILENAME).gif!