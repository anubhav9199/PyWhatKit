# Contribution Guidelines

Thank you so much for your interest in contributing!. All types of contributions are valuable. 📝

Please make sure to read the documentation before making your contribution! It will make it a lot easier for us maintainers to make the most of it and smooth out the experience for all involved. 💚

### If you have a question about this project, how to use it, or just need clarification about something

* Open an Issue [here](https://github.com/Ankit404butfound/PyWhatKit/issues)
* Provide as much context as you can about what you're running into.
* Provide project and platform versions (python, pip etc), depending on what seems relevant. If not, please be ready to provide that information if maintainers ask for it.

### Request a Feature

If the project doesn't do something you need or want it to do:

* Head over to [this page](https://pywhatkit.herokuapp.com/request-feature)
* Provide as much context as you can about what you're looking for.
* If you want to contribute that feature yourself, please open a new draft PR [here](https://github.com/Ankit404butfound/PyWhatKit/pulls).

### Code Formatting

Please make sure that your code follows the PEP8 standards and that you provide proper type hinting for the functions and parameters with proper spacing.
For PyCharm users, you can use the shortcut `Ctrl + Alt + L` to reformat your code.
For VSCode users, create a `.vscode` folder in the project directory and a `settings.json` file inside it.
Inside the file add the following lines:

```json
{
    "python.formatting.provider": "autopep8",
    "editor.formatOnSave": true
}
```

For others, you can directly use `autopep8 -i filename` in the terminal to format your code.
Before committing your changes run `pre-commit run --all-files` in your terminal, this would fix most of the common errors.

### Contributing Code

Code contributions of just about any size are acceptable!

Setting up a development environment:

1. Fork the repository and then clone it to your local computer.
2. OPTIONAL BUT RECOMMENDED: Create a new virtual environment with `virtualenv` using `python3 -m venv venv`.
3. Activate the virtual environment and install the project dependencies using `pip3 install -r requirements.txt`.
4. Congrats 🎉, you are now ready to contribute.

To contribute the code:

1. Set up the development environment.
2. Make any necessary changes to the source code.
3. If possible, make sure to include comments describing what your code does.
4. Write clear, concise commit message(s).
5. Push changes to your forked repository and when you are ready to get your changes reviewed, create a new PR from your forked repository.
6. If your PR fixes an open issue, add a line in your PR's description that says `Fixes: #123`, where `#123` is the number of the issue you're fixing.
7. Someone from the maintainers will review your PR and will take the further steps.

NOTE: To contribute to the Documentation, follow the same steps as above.

### Adding New Features

If you want to add new features to the library, please open an issue first to discuss it. Thanks

### Provide Support on Issues

Helping out other users with their questions is a really awesome way of contributing to any community. If you can help out someone please go ahead for it. 🙂
