# FE Toolkit

[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/zhanghe.vcgfetoolkit.svg)](https://marketplace.visualstudio.com/items?itemName=zhanghe.vcgfetoolkit) [![Installs](https://vsmarketplacebadge.apphb.com/installs/zhanghe.vcgfetoolkit.svg)](https://marketplace.visualstudio.com/items?itemName=zhanghe.vcgfetoolkit) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

Front-end development toolkit.
<div align="center"><a href="https://zhanghe.cool" alt="Big lvan"><img src="https://cdn.jsdelivr.net/gh/zhanghecool/assets/images/gif/zhanghecool.gif" width="auto" /></a></div>

## My other user code snippet plugin: [Big Lvan](https://marketplace.visualstudio.com/items?itemName=zhanghe.biglvan)

<div align="center"><a href="https://marketplace.visualstudio.com/items?itemName=zhanghe.biglvan" alt="Big lvan"><img src="https://cdn.jsdelivr.net/gh/zhanghecool/biglvan/assets/icons/logo.png" width="100" /><p>Big lvan</p></a></div>

# React Keys

|             Prefix | Method                                             |
| -----------------: | -------------------------------------------------- |
|   `hus , useState` | `const [state, setState] = useState(initialState)` |
| `huc , useContext` | `const context = useContext(initialContext)`       |
|     `hur , useRef` | `const refContainer = useRef(initialRef)`          |

### `hue , useEffect`

```javascript
useEffect(() => {
  componentDidMount || componentDidUpdate;

  return () => {
    componentWillUnmount;
  };
}, [input]);
```

### `hucb , useCallback`

```javascript
const memoizedCallback = useCallback(() => {
  // doSomething(a, b);
}, [a, b]);
```

### `hum , useMemo`

```javascript
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

### `hurd , useReducer`

```javascript
const [state, dispatch] = useReducer(reducer, initialArg, init);
```

### `huih , useImperativeHandle`

```javascript
useImperativeHandle(ref, createHandle, [deps]);
```

### `ifc , internalFunctionComponent`

```javascript
const  = ({
  className = '',
  // props,
}) => {
  // TODO

  return // TODO
}
```

### `fc , functionComponent`

```javascript
import React from 'react';
import withStyles from 'isomorphic-style-loader/lib/withStyles';
import cs from 'classnames';
import styles from './.scss';

const  = ({
  className = '',
  // props,
}) => {
  // TODO

  return // TODO
}

export default withStyles(styles)();
```

### `cc , classComponent`

```javascript
import React, { Component } from 'react';
import PropTypes from 'prop-types';
import withStyles from 'isomorphic-style-loader/lib/withStyles';
import cs from 'classnames';
import styles from './.scss';

class  extends Component {
  static propTypes = {
    // propName: PropTypes.string,
  }

  static defaultProps = {
    // propName: "",
  }

  state = {
    // stateName: "",
  }

  render() {
    const { propName } = this.props;
    const { stateName } = this.state;

    return (
      // TODO
    )
  }
}

export default withStyles(styles)();
```

### `ccsp`

```javascript
static propTypes = {
  : PropTypes.string,
}


```

### `ccsd , defaultProps`

```javascript
static defaultProps = {
  : PropTypes.string,
}


```

### `state`

```javascript
state = {};
```

### `cchf , classHandleFunction`

```javascript
handle = ({}) => {};
```

### `fchf , functionHandleFunction`

```javascript
const handle = () => {};
```

### `tp`

```javascript
const {} = this.props;
```

### `ts`

```javascript
const {} = this.state;
```

### `ir , imp , import`

```javascript
import React from "react";
```

### `imws , importwithStyles`

```javascript
import withStyles from "isomorphic-style-loader/lib/withStyles";
```

### `imcn , importclassnames`

```javascript
import cs from "classnames";
```

### `ed , exp , export`

```javascript
export default ;
```

### `ec , expc , exportc`

```javascript
export const  = () => ;
```

### `cin , consoleinfo`

```javascript
console.info("msg: ", subst);
```

### `clo , consolelog`

```javascript
console.log("msg: ", subst);
```

### `cer , consoleerror`

```javascript
console.error("msg: ", subst);
```

### `cdi , consoledir`

```javascript
console.dir(obj);
```

### `cta , consoletable`

```javascript
console.table(data, columns);
```

### `cti , consoletime`

```javascript
console.time(label);
```

### `cte , consoletimeend`

```javascript
console.timeEnd(label);
```

### `ctl , consoletimeLog`

```javascript
console.timeLog(label);
```

### `cwa , consolewarn`

```javascript
console.warn("msg: ", subst);
```

### `ccl , consoleclear`

```javascript
console.clear();
```

### `cco , consolecount`

```javascript
console.count(label);
```

### `cmmf , commentsfunctions`

```javascript
/**
 * 用一句话介绍此函数是干嘛用的。
 *
 * @param {string} employee - 参数的介绍文字
 * @return {string} 函数返回的数据
 *
 * @example
 *
 *     const xx = foo('hello')
 */
```

# Style keys

### `fl`

```css
font-size: 16px;
line-height: 24px;
```

### `wh`

```css
width: 1280px;
height: 344px;
```

### `te`

```css
overflow: hidden;
white-space: nowrap;
text-overflow: ellipsis;
width: 100%;
```

### `tem`

```css
position: relative;
line-height: 24px;
height: 48px;
font-size: 16px;
overflow: hidden;
display: block;
width: 100%;

&:after {
  content: "";
  position: absolute;
  bottom: 0;
  right: 0;
  width: 150px;
  height: 24px;
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #ffffff 50%);
}
```

### `temw`

```css
overflow: hidden;
display: -webkit-box;
text-overflow: ellipsis;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

### `hvc`

```css
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
```
