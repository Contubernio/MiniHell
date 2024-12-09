
# Minishell

A 42 project focused on building a simple, functional shell inspired by bash. Minishell is capable of executing basic commands, handling signals, and supporting features like redirections and pipes, emulating some of the behavior of a Unix shell.

## Features

- Execute basic shell commands
- Handle redirections (`>`, `<`, `>>`)
- Support pipes (`|`)
- Manage environment variables
- Basic signal handling (`Ctrl+C`, `Ctrl+D`, `Ctrl+Z`)
- Built-in commands: `cd`, `echo`, `env`, `setenv`, `unsetenv`, `exit`

## Getting Started

### Prerequisites

- GCC or any compliant C compiler
- Make

### Installation

1. Clone the repository:
    ```bash
    git clone 
    cd minishell
    ```

2. Build the project:
    ```bash
    make
    ```

### Usage

Run the shell executable:
```bash
./minishell
```

## Examples

```bash
minishell$ echo "Hello, World!"
Hello, World!
minishell$ ls -l | grep minishell
-rwxr-xr-x  1 user  group  12345 date time minishell
minishell$ cat < file.txt | grep "search term" > output.txt
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The 42 Network for the project inspiration
- [GNU Bash](https://www.gnu.org/software/bash/) for being a reference implementation
- Various online resources and communities
