# VCG FE

VCG 前端工作流插件。

## React Keys

|             Prefix | Method                                             |
| -----------------: | -------------------------------------------------- |
|   `rus | useState` | `const [state, setState] = useState(initialState)` |
| `ruc | useContext` | `const context = useContext(initialContext)`       |
|     `rur | useRef` | `const refContainer = useRef(initialRef)`          |

### `rue | useEffect`

```javascript
useEffect(() => {
  componentDidMount || componentDidUpdate;

  return () => {
    componentWillUnmount;
  };
}, [input]);
```

### `ifc | internalFunctionComponent`

```javascript
const  = ({
  className = '',
  // props,
}) => {
  // TODO

  return // TODO
}
```

### `fc | functionComponent`

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

### `cc | classComponent`

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

### `ccsd | defaultProps`

```javascript
static defaultProps = {
  : PropTypes.string,
}


```

### `cchf | classHandleFunction`

```javascript
handle = ({}) => {};
```

### `fchf | functionHandleFunction`

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

### `ir | imp | import`

```javascript
import React from "react";
```

### `ed | exp | export`

```javascript
export default ;
```
