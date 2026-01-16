# How to setup Tailwind CSS

Step 1 :
Write this command in Command Prompt.

```
npm init -y
```

Step 2 :
To Install Tailwind CSS,
Install tailwindcss and @tailwindcss/cli via npm,
Write this command in Terminal.

```
npm install tailwindcss @tailwindcss/cli
```

Step 3 :
Crete The New CSS File to include this,
Add the @import "tailwindcss"; to the input.css file.

```
@import "tailwindcss";
```

Step 4 :
Run The Following Command,
Run the CLI tool to scan your source files for classes and build your CSS.

```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```