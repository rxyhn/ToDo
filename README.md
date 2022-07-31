<div align="justify">

<p align="center">
    <b>
        <p align="center">A simple command-line ToDo app written in Go.</p>
        <hr>
    </b>
</p>

## Installation

- Building From Source:

    Clone the repository:

    ```sh
    git clone https://github.com/rxyhn/ToDo.git
    ```

    Run the following commands:

    ```sh
    cd ToDo
    go build ./cmd/todo
    ./todo # This will be built inside the ToDo/ directory
    ```

## Usage

```sh
Usage of ./todo:
  -add
        add a new todo
  -complete int
        mark a todo as completed
  -del int
        delete a todo
  -list
        list all todos
```

</div>
