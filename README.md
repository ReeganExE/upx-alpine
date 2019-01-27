# Smallest UPX Docker Image
Just Alpine + UPX (Ultimate Packer for Executables).

This Docker image will help you compress Linux & Windows executables from any platform where Docker can run. Useful for compressing [Go build](https://golang.org/pkg/go/build/) output.
# Usage
```sh
docker run --rm -v $PWD:/working reeganexe/upx /working/big-binary
```

UPX will replace the original file.

![image](https://user-images.githubusercontent.com/7277418/51802845-78d69d80-2280-11e9-9599-4439cc6e9166.png)

# LICENSE

MIT @ Ninh Pham