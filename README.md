# ShellScript

 - type Command
```sh
    type <script name>
    Eg: type ls
```

 - Variables
    - Used to store data by name
    - To create: just assign a value
```sh
    x=10
```
If x already existed, it is assigned the new value.
Don't use whitespace around =

```sh
    filenames="notes.txt picture.jpg movie.mov"
```
If the value consists of multiple words, it can be seperated by spaces and use quotes.

    - To retrive the value
    Prefix with $
    ```sh
    echo $x
    ```
    - Bash variables have no type