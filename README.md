<div align="center">
    <h4>
       Simple pattern to develop and compile C projects, created by <a href="https://github.com/denieu">Daniel Wojcickoski</a>.
    </h4>
</div>

## Folder Structure
* **/bin**       - Directory of binary files<br>
* **/includes**  - Directory of .h files<br>
* **/libs**      - Directory of lib files<br>
* **/obj**       - Directory of object files<br>
* **/resources** - Directory of .rc files<br>
* **/src**       - Directory of .c files<br>

## Use of pattern
<p>1° - Clone repo</p>

```bash
    git clone https://github.com/danielwojcickoski/project-pattern.c.git
    cd ./project-pattern.c
```

<p>2° - Adjust FILENAME in Makefile, this is the name of the binary generated after the make</p>
<p>3° - Adjust LIB_FLAGS in Makefile, these are the libs that should be used when compiling your project</p>

## Compiling
Make sure you already have build essentials installed.
```bash
    make
```

## Cleaning Object Files
Make sure you already have build essentials installed.
```bash
    make clean
```

## Running Application
Make sure you already have build essentials installed.
```bash
    make run
```
