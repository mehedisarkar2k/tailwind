# for first time

> > npx tailwindcss-cli build css/tailwind.css -o build/style.css

connect css from build file

## after doing following bellow no need to build folder

> > npm init -y

> > npm install -D tailwindcss@latest postcss@latest autoprefixer@latest vite

#### now delete build folder and connect css from tailwind css where we import tailwindcss files

# But for vite, must need tailwind config file with post config file

#### for getting this run following command

> > > npx tailwind init -p

##### it will run dev from the script

> > npm run dev

> > > "scripts": {
> > >
> > > "dev": "vite"
> > >
> > > },

> > npm run build

it will run build form the script

> > > "scripts": {
> > >
> > > "dev": "vite",
> > > "build": "vite build"
> > >
> > > }

tailwind.config.js
purge:[from which file should purge . "file path"]
