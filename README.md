
# mdbook_themes

This repository contains all common themes from the official mdbook developers along with some other hand crafted themes.

Another advantage of using this repository is that when some new themes are added/updated or some bugs/glitches in the theme is fixed. It can be easily tracked and updated.

## Available Themes

- Space
- Sustain
- Eco-Friend
- Game [in future ..]

## Usage

1. Make this repository as git submodule by using the following command.

    ```git submodule add https://github.com/hari-vickey/mdbook-themes.git```

2. Open `book.toml` and change the following `theme` value to the folder/sub-repository name. Change the `default-theme` to your favourite theme.

    ```
	[output.html]
	theme = "mdbook-themes"
	default-theme = "space"
    ```

3. Now, you are free to delete previous theme directory.

4. Build the mdbook using `mdbook build` and see the changes.

    > *__**Pro:**__ `mdbook serve --open` can be used to build and track changes automatically. Saves one commnad to type :P .*


mdBook.zip is attached to get the base files for building. Extract it to the root folder for building.

## Create/Modify Theme

- To change the header, modify the `header.hbs` file

- To change the styling, modify `variables.css` file

- To add functionalities, modify `book.js` (carefully)

**__Feel free to create/update themes and add a pull request.__**
