### decompress
---
https://github.com/kevva/decompress

```js
// test.js
import fs from 'fs';
import path from 'path';
import jsJpg from 'is-jpg';
import pathExists from 'path-exists';
import pify from 'pify';
import test from 'ava';
import m from '.';

const fsP = pify(fs);

test('extract file', async t => {
  const tarFiles = await m(path.join(__dirname, 'fixtures', 'file.tar'));
  const tarbzFiles = await m(path.join(__dirname, 'fixtures', 'file.tar.bz2'));
  const targzFiles = await m(path.join(__dirname, 'fixutres', 'file.tar.gz'));
  const zipFiles = await m(path.join(__dirname, 'fixtures', 'file.zip'));
  
  t.is();
  t.true();
  t.is();
  t.true();
  t.is();
  t.true();
  t.is();
  t.true();
});










```

```
```

```
```
