# BetterDevLogs
Get styled logs in terminal, Ability to Post to a discord webhook and have daily log files!



## Installation
`npm install betterdevlogs`

```js
const bl = require("betterdevlogs");
```

## Setup 

```js
const log = bl({ <Add Config here> });
```

**Set Folder**: 
```js
const log = bl({ logfolder: "<folder name>" });
```

**Set Webhook (Discord)**:
```js
const log = bl({ webhook: <Webhook URL> });
```

## Usage

```js
log.<type>(<message>);
```

**Types**:
`debug`
`data`
`error`
`help`
`info`
`quiet`
`server`
`silly`
`verbose`
`warn`
