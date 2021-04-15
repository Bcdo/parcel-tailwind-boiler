## Tailwind-boiler

This is a boiler project with [Tailwind](https://tailwindcss.com/) for styling, and [Parcel](https://parceljs.org/) for building. This boiler is for smaller projects, but I will work on implementing [CraftCMS](https://craftcms.com/) and [Vue](https://vuejs.org/) as a fork to this git in the future.

## Technology

- Parcel
- Tailwind JIT
- PostCSS 8

## Installation

Clone the git and use the package manager [npm](https://www.npmjs.com/get-npm) to install the packages.

```bash
npm install
```

## Usage

To run the dev server and serve it on localhost:1234

```bash
npm run start
```

To build for production

```bash
npm run build
```

To do a clean

```bash
npm run clean
```

The clean script will run with both running the dev server as well as building. Never manually run any other of the scripts, they are controlled with [npm-run-all plugin](https://www.npmjs.com/package/npm-run-all), and are used during the three commands above.

The files build and ready for production is in the dist folder. Make sure that the index.css file is empty when running the build, as the pcss will produce the content of the css file.

## Roadmap

- [x] Implement best practices from [html5boilerplate](https://html5boilerplate.com/)
- [ ] Automate index.css handling

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
