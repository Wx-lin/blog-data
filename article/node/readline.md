```js
const readline = require('readline')
```

- readline.Interface

  - rl.on('close', ())
  - rl.on('line', (input))
  - rl.on('line', (input))
  - rl.on('pause', ())
  - rl.on('resume', ())
  - rl.on('SIGCONT', ())
  - rl.on('SIGTSTP', ())
  - rl.close()
  - rl.pause()
  - rl.prompt([preserveCursor])
  - rl.question(query, callback)
  - rl.write(data[, key])

- readline.clearLine(stream, dir)
- readline.clearScreenDown(stream)
- readline.createInterface(options)
- readline.cursorTo(stream, x, y)
- readline.moveCursor(stream, dx, dy)
- readline.emitKeypressEvents(stream[, interface])