# Electron Create React

A boilerplate with zero dependencies other than React. Easy to use with single command run and packaging scrips

## Usage

- Clone this repository
- cd into the directory and run `npm install`
- Delete git files `rm -rf .git`

## Development

- Run `npm start` to start electron and react concurrently

## Build and package

- Run `npm run package` to compile react, copy files and then package your app
- A new `dist` folder will be created in the root of your project containing the executable files
- NOTE: add `--mac` to the `postpackage` script besides `--win` if you are on a mac computer

## Project structure

- `electron/`: Code for the main Electron process
- `src/react/`: Code for the React renderer process
- `src/shared/`: Code shared between React and Electron
- `package.json`: Contains scripts for running the app in development, building it, and packaging it for production using electron-builder

## Contributing

Open a new PR to contribute

## Credits

Original idea by [johndyer24](https://github.com/johndyer24)

## License

MIT
