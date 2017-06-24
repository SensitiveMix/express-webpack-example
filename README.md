```bash

                                                          __                     __  
  ___  _  ______  ________  __________     _      _____  / /_  ____  ____ ______/ /__
 / _ \| |/_/ __ \/ ___/ _ \/ ___/ ________| | /| / / _ \/ __ \/ __ \/ __ `/ ___/ //_/
/  ___>  </ /_/ / /  /  __(__  (__  /_____| |/ |/ /  __/ /_/ / /_/ / /_/ / /__/ ,<   
\___/_/|_/ .___/_/   \___/____/____/      |__/|__/\___/_.___/ .___/\__,_/\___/_/|_|  
        /_/                                                /_/                       


```
A workflow with full live reload for webpack&express application.

## Start

[![Greenkeeper badge](https://badges.greenkeeper.io/SensitiveMix/express-webpack-example.svg)](https://greenkeeper.io/)

```bash
git clone git@github.com:SensitiveMix/express-webpack-example.git
 ```

## Install dependencies.

```bash
npm install
```

```bash
npm install supervisor -g
```

## Usage
* `npm start` to develop with full live reload.
* `npm run browsersync` is a alternative for development. It may be faster when modifying the express views
(templates) only.
* `npm run production` to emit outputs and run the express for production.
* `npm run build` if you care about what is hold in memory for development...


## LISENCE
MIT License

Copyright (c) 2016 Jack Sun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

