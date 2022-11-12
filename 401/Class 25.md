# Chakra UI

Chakra UI is a simple, modular and accessible component library that gives you the building blocks you need to build your React applications. [1](https://chakra-ui.com/)

It is based on styled systems (it has its own theme specification).


## Chakra UI vs Material UI

Chakra UI is more robust and it creates more flexible, composable, and scalable code. Chakra UI is also easier to modify.


## How to Use Chakra UI

### Installtion:

````
$ npm install --save @chakra-ui/react
````

### Setting up:

```
import { ThemeProvider, ColorModeProvider } from "@chakra-ui/react"

const App = ({ children }) => (
  <ThemeProvider>
    <ColorModeProvider>{children}</ColorModeProvider>
  </ThemeProvider>
)

```

### You Can Now Use It!

```
import { Button } from "@chakra-ui/react"

const App = () => <Button>Wow</Button>

```
