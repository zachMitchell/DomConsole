# About DOM Console

*DOM Console* aims to be an extremely light-weight playground for legacy web-browsers, or browsers that don't have a built-in JavaScript console. You can type in commands as you normally would, and **console output gets directly printed to the page.**

Legacy Web browsers (Such as the Nintendo 3DS browser, based off of webkit) are not supported these days with new & shiny things. I wanted to see things the browser could do, but didn't have an appropriate outlet for that. W3 Schools has a "try it" editor, but does not properly work on the 3DS...

As of right now, I don't intend to re-create *all* console functions. Rather, functions that are used frequently will be re-programmed to work with DOM Console.

## USAGE
*To access this page without downloading it, visit (https://zachmitchell.github.io/DomConsole)*
* The text field on the bottom is your command line! Type in whatever, and returned elements enter the pseudo console above
* That dashed square on top is `#sandbox`. You can place your html elements up there.

## TODO List
### Completed
1. `console.log`
1. `console.warn`
1. `console.error`
1. `console.clear`
1. Similar input methods to a developer console (F12 on Chrome)
1. Variable initiation
1. Popular Javascript plugin injection
1. Hot-swapping between a real console and DOM Console
1. A text-field for executing longer code.
1. Temporary script Storage (**Note:** *Based on tests, Nintendo 3DS doesn't support client-side cookies for some reason... Therefore, storing ANYTHING in general on 3DS will not work atm*)

### In the works
1. `console.table`
1. `console.group`

### Dream features
**These are features I can't implement at this time, due to various reasons (e.g backend required, lack of legacy browser support)**
1. Cloud storage (Preferrably [solid pod](https://inrupt.com/solid))

## Issues
Not all errors will appear in DOM Console. This is because `console.error` is not used when running a traceback on web browsers. I could be wrong on this, but until then, error messages only run if manually created by the developer (`console.error()`);

## Contributing
This project is open to external contributions. It is a spare-time project, so I'm happy with anyone dabbling with it.

When comitting, make your own personal branch. If/when we merge, start afresh with a new branch.
