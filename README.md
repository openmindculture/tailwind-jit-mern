tailwind-jit-starter

this is a dev stack for using tailwindcss 2.1 with JIT compilation
in a MERN stack with (p)react, node and a no-sql database
to be deployed on the cloud.

## why not XYZ

Originally intended to use tailwind with create-react-app,
after trying to solve conflicts and incompatibilities,
I rebased the starter on [retinafunk's tailwind-jit-starter](https://github.com/retinafunk/tailwind-jit) and decided to drop old technology like webpack in favour of smaller, more elegant solutions, which in consequence lead to the decision to drop React in favour of preact, making our starter a MEPPN stack.

## tailwind

read more here : https://blog.tailwindcss.com/tailwindcss-2-1
and

I added configs bor tailwindcss , via postcss and a live reload dev server
just

All is configured for you you ready to go in 2 minutes.

Start with cloning the repository and in Terminal :

> yarn or >npm install

then :

A script to compile twailwindcss with postcss

> yarn dev

and to have a live reload local dev server for better and faster deb experience

> yarn serve

Change the Taiwind css classes in /build/index.html to see in action

Visit http://localhost:8081/ in your Browser

HAVE FUN!
