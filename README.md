## JakVM

This is a project written in [Jakt](https://github.com/serenityOS/jakt) which intends to be able to parse, and (hopefully) execute Java class files.

This is in its very early stages, and I'm honestly not sure how far it'll go.

### Running

1. Ensure that you have `jakt` installed correctly.
2. Compile the program
    ```console
    $ jakt ./src/main.jakt
    ```
3. Run the program, with a class file as the first argument, one is already included for you.
    ```console
    $ ./build/main example/Main.class
    ```
