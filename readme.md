# process-list-title
>Process title list in windows

### Install
```
npm i process-list-title
```

This module required `powershell@3` or above.

### API

#### `.takeTitle([fields])`
Return array with info of each runned process.


##### example
```js
const processList = require('process-list-title');

processList.takeTitle().then((list) => {/* ... */})
```

### Supports
nodejs  **>=4**

### License
MIT, 2022 (c) Okay Şahin
