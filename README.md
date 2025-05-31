# SA-MP Injector 🚀

![SA-MP Injector](https://img.shields.io/badge/SA--MP%20Injector-v1.0-blue.svg)

Welcome to the **SA-MP Injector** repository! This project provides a versatile executable and library for SA-MP (San Andreas Multiplayer) and OMP (Open Multiplayer). With this tool, you can inject `samp.dll` for SA-MP or both `samp.dll` and `omp-client.dll` for OMP. It allows you to launch the game via command line with customized parameters to connect to a server.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Command Line Options](#command-line-options)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features 🌟

- **Versatile Injection**: Supports both SA-MP and OMP by injecting the necessary DLLs.
- **Command Line Launch**: Start the game with specific parameters for seamless connection to servers.
- **Lightweight**: Designed to be efficient and easy to use without unnecessary bloat.
- **Open Source**: Contributions are welcome to improve functionality and performance.

## Installation ⚙️

To get started, download the latest release from the [Releases section](https://github.com/dat212222/samp-injector/releases). Look for the executable file, download it, and execute it on your Windows machine.

### Requirements

- Windows operating system
- SA-MP or OMP installed
- Basic knowledge of command line usage

## Usage 🎮

After installation, you can use the SA-MP Injector to launch your game. The injector will handle the injection of the required DLLs. 

### Steps to Use

1. Open your command line interface (CMD).
2. Navigate to the directory where you downloaded the SA-MP Injector.
3. Use the following command to launch the injector:

   ```
   samp-injector.exe [options]
   ```

For detailed options, refer to the [Command Line Options](#command-line-options) section.

## Command Line Options 🛠️

The SA-MP Injector supports various command line options to customize your game launch. Here are some of the options available:

- `-s <server_address>`: Specify the server address to connect.
- `-p <port>`: Set the port number for the connection.
- `-n <nickname>`: Choose your in-game nickname.
- `-l`: Launch the game in windowed mode.
- `-f`: Force the injector to use specific DLLs.

### Example Command

To connect to a server with the address `127.0.0.1` on port `7777` with the nickname `Player1`, use:

```
samp-injector.exe -s 127.0.0.1 -p 7777 -n Player1
```

## Contributing 🤝

We welcome contributions to enhance the SA-MP Injector. If you have ideas, improvements, or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

### Guidelines

- Ensure your code follows the existing style.
- Write clear commit messages.
- Test your changes before submitting.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact 📧

For questions or suggestions, feel free to reach out:

- **GitHub**: [dat212222](https://github.com/dat212222)
- **Email**: [your-email@example.com](mailto:your-email@example.com)

For the latest updates, check the [Releases section](https://github.com/dat212222/samp-injector/releases) regularly.

---

Thank you for your interest in the SA-MP Injector! We hope you find it useful for your gaming experience. Enjoy connecting to your favorite servers with ease!