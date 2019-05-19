## Sublime Text 3 React snipptes with hooks

Sublime Text 3 React snipptes including fuctional component, hooks and prop types


### Installing

Navigate to your Sublime Text 3 user packages directory and git clone this repository


### Snippets

#### Functional component

**rfc →**

```javascript
import React from 'react';

const propTypes = {
  ${1:}: string${2:.isReqired},
};

const defaultProps = {
  ${3:}: ${4:null},
}

function ${TM_FILENAME/(\w+)\.js/\1/g}(${5:\{ ${6:} \}}) {
  return <>{${6:}}</>;
};

${TM_FILENAME/(\w+)\.js/\1/g}.propTypes = propTypes;
${TM_FILENAME/(\w+)\.js/\1/g}.defaultProps = defaultProps;

export default ${TM_FILENAME/(\w+)\.js/\1/g};
```
