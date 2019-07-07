# Electron Create React Example

This is an example electron/create-react-app application, and serves as an example of how to structure your project if you want to share pieces of your codebase between electron and react.

## Usage

- Clone this repository
- cd into the directory and run `npm install`
- Delete git files `rm -rf .git`

## Development

- Run `npm start` to start the react development server
- After that, run `npm run start-electron` in a different terminal to start the electron app

## Build and package

- Run `npm run package` to compile react, copy files and then package your app
- A new `dist` folder will be created in the root of your project containing the executable files
NOTE: add `--mac` to the `postpackage` script besides `--win` if you are on a mac computer

## Project structure

- `electron/`: Code for the main Electron process
- `src/react/`: Code for the React renderer process
- `src/shared/`: Code shared between React and Electron
- `package.json`: Contains scripts for running the app in development, building it, and packaging it for production using electron-builder

## Contributing

Open a new PR to contribute

## License

MIT