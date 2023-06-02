# LazyDev: Automated Coding Project Generator

LazyDev is a Python module that utilizes GPT models to create entire coding projects for you. With just a few simple commands, LazyDev can generate a project file tree, write the necessary code, and even test the project for you. Say goodbye to the hassle of setting up projects from scratch and let LazyDev do the heavy lifting for you.

## Features

- **Effortless project initialization**: Simply use the `python -m lazydev.develop -r <what you want to do>` command to kickstart the project generation process.
- **Interactive question-based approach**: LazyDev asks relevant questions to gather essential information before starting the coding process, ensuring that the generated project meets your specific requirements.
- **Complete project planning**: LazyDev plans the entire project structure based on the gathered information, setting up the necessary directories and files for you.
- **Automated code generation**: The module automatically generates the code based on the project plan, saving you time and effort.
- **Built-in testing functionality**: LazyDev even includes an automated testing phase to ensure that the generated code performs as expected.

## Installation

```
git clone https://github.com/thecodacus/lazy-dev.git
cd lazy-dev
pip install -r requirements.txt
```

LazyDev requires Python 3.6 or above.

## Usage

Using LazyDev is as simple as running a single command. Once installed, you can initiate the project generation process by executing the following command:

```
python -m lazydev.develop -r <what you want to do>
```

Replace `<what you want to do>` with a brief description of your project's purpose or objective. LazyDev will then prompt you with a series of questions to gather the necessary information for project generation.

After answering the questions, LazyDev will proceed to plan the project structure, create the appropriate file tree, generate the required code files, and even run tests to verify the functionality.

## Example

Let's say you want to create a Python web application for managing a book library. You can use LazyDev to automate the project setup. Here's an example command:

```
python -m lazydev.develop -r "Book Library Web App"
```

LazyDev will ask you questions like:

- What database system would you like to use?
- What features would you like to include in your web app?
- Are there any specific libraries or frameworks you want to use?

Based on your responses, LazyDev will generate the project structure, code templates, and even a basic test suite for your book library web app.

## Contributing

Contributions are welcome! If you encounter any issues, have ideas for new features, or want to improve the existing ones, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com//thecodacus/lazy-dev).

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](https://github.com/thecodacus/lazy-dev/blob/master/LICENSE) file for more details.

## Acknowledgements

LazyDev was inspired by the desire to automate the initial setup and coding process for various projects. The underlying GPT models used in this module were developed by OpenAI.

It is inspired by the project [smol-ai/developer](https://github.com/smol-ai/developer), and the principle `Build the thing that builds all the things.`

## Contact

If you have any questions or suggestions, feel free to reach out to us at thecodacus@gmail.com.

Happy coding with LazyDev!