# Airbnb react snippets (Prettier)

ES6 [Reactjs][react] code snippets for VS Code compliant with [Airbnb style guide](https://github.com/airbnb/javascript/tree/master/react)

Fork of [cobeia/airbnb-react-snippets](https://github.com/cobeia/airbnb-react-snippets) which replaces string single quotes with double quotes, for prettier users

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Class Components

|   Trigger | Content                                           |
| --------: | ------------------------------------------------- |
|     `rc→` | class component skeleton                          |
|    `rcc→` | class component skeleton with constructor         |
| `rconst→` | class default constructor                         |
|    `rpt→` | empty propTypes declaration                       |
|    `rdp→` | empty defaultProps declaration                    |
|    `rbm→` | `binds the this of method inside the constructor` |
|   `rcwm→` | `componentWillMount method`                       |
|   `rcdm→` | `componentDidMount method`                        |
|   `rcwr→` | `componentWillReceiveProps method`                |
|   `rscu→` | `shouldComponentUpdate method`                    |
|  `rcwup→` | `componentWillUpdate method`                      |
|  `rcdup→` | `componentDidUpdate method`                       |
|  `rcwun→` | `componentWillUnmount method`                     |
|   `rren→` | `render method`                                   |
|   `rsst→` | `this.setState with object as parameter`          |
|   `rssf→` | `this.setState with function as parameter`        |
| `rprops→` | `this.props`                                      |
| `rstate→` | `this.state`                                      |

### Function Components

|  Trigger | Content                     |
| -------: | --------------------------- |
| `rfunc→` | function component skeleton |

### Hooks

|  Trigger | Content                   |
| -------: | ------------------------- |
|  `uste→` | UseState Hook             |
|  `uctx→` | UseContext Hook           |
|   `ufx→` | UseEffect Hook            |
|  `urdc→` | UseReducer Hook           |
| `ucbck→` | UseCallback Hook          |
|  `umem→` | UseMemo Hook              |
|  `uref→` | UseRef Hook               |
|   `uih→` | UseImperativeHandler Hook |
|   `ule→` | UseLayoutEffect Hook      |
|   `udv→` | UseDebugValue Hook        |

The following table lists all the snippets that can be used for prop types.
Every snippet regarding prop types begins with `pt` so it's easy to group it all together and explore all the available options.
On top of that each prop type snippets has one equivalent when we need to declare that this property is also required.
For example `pta` creates the `PropTypes.array` and `ptar` creates the `PropTypes.array.isRequired`

|  Trigger | Content                                                                              |
| -------: | ------------------------------------------------------------------------------------ |
|   `pta→` | `PropTypes.array,`                                                                   |
|  `ptar→` | `PropTypes.array.isRequired,`                                                        |
|   `ptb→` | `PropTypes.bool,`                                                                    |
|  `ptbr→` | `PropTypes.bool.isRequired,`                                                         |
|   `ptf→` | `PropTypes.func,`                                                                    |
|  `ptfr→` | `PropTypes.func.isRequired,`                                                         |
|   `ptn→` | `PropTypes.number,`                                                                  |
|  `ptnr→` | `PropTypes.number.isRequired,`                                                       |
|   `pto→` | `PropTypes.object.,`                                                                 |
|  `ptor→` | `PropTypes.object.isRequired,`                                                       |
|   `pts→` | `PropTypes.string,`                                                                  |
|  `ptsr→` | `PropTypes.string.isRequired,`                                                       |
|  `ptnd→` | `PropTypes.node,`                                                                    |
| `ptndr→` | `PropTypes.node.isRequired,`                                                         |
|  `ptel→` | `PropTypes.element,`                                                                 |
| `ptelr→` | `PropTypes.element.isRequired,`                                                      |
|   `pti→` | `PropTypes.instanceOf(ClassName),`                                                   |
|  `ptir→` | `PropTypes.instanceOf(ClassName).isRequired,`                                        |
|   `pte→` | `PropTypes.oneOf(['News', 'Photos']),`                                               |
|  `pter→` | `PropTypes.oneOf(['News', 'Photos']).isRequired,`                                    |
|  `ptet→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),`                         |
| `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,`              |
|  `ptao→` | `PropTypes.arrayOf(PropTypes.number),`                                               |
| `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,`                                    |
|  `ptoo→` | `PropTypes.objectOf(PropTypes.number),`                                              |
| `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,`                                   |
|  `ptsh→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),`            |
| `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |

[react]: https://facebook.github.io/react/
[badass-react-snippets]: https://github.com/tylerbuchea/badass-react-snippets
[vscode-react]: https://github.com/xabikos/vscode-react
