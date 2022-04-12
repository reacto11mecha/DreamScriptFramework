## DreamScript Frameworks
Repository Of DreamScript Frameworks



![License](https://img.shields.io/badge/License-MIT-blue.svg)

![Image](https://raw.githubusercontent.com/ds-lang/DreamScript/main/imagee.jpg)


## Frameworks Installation

- Install [NodeJs](https://nodejs.org/en/)
- Install with NPM

## Get Started

- Server Side Frameworks
```js
pkg ds-lib from 'ds-frameworks'

import server from ds-lib()

// GET
server.get('/dreamscript', (req,res) => {
	res.send('Build with DreamScript Frameworks')
})

// POST
server.post('/dreamscript', (req,res) => {
  write('ds', req.ds)
  res.json(req.body)
})

// PUT
server.put('frameworks', (req,res) => {
  write('ds', req.ds)
  res.json(req.ds)
})

// SERVER LISTENING
server.listen(8080, () => {
  write('Server running on PORT 8080');
})
```

## CREDITS
- JahiR
