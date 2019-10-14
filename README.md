<h1 align="center"><a href="https://github.com/mrdoob/three.js">JavaScript 3D library</a> for <a href="https://github.com/theme-next">NexT</a></h1>

<h1 align="center">Installation</h1>

<h2>If you want to use the CDN instead of clone this repo, please jump to the Step 3.</h2>

<h2 align="center">Step 1 &rarr; Go to NexT dir</h2>

Change dir to **NexT** directory. There must be `layout`, `source`, `languages` and other directories:

```sh
$ cd themes/next
$ ls
_config.yml  crowdin.yml  docs  gulpfile.js  languages  layout  LICENSE.md  package.json  README.md  scripts  source
```

<h2 align="center">Step 2 &rarr; Get module</h2>

Install module to `source/lib` directory:

```sh
$ git clone https://github.com/theme-next/theme-next-three source/lib/three
```

<h2 align="center">Step 3 &rarr; Set it up</h2>

Enable module in **NexT** `_config.yml` file:

```yml
three_waves: true
OR
canvas_lines: true
OR
canvas_sphere: true
```

**And, if you wants to use the CDN, then need to set:**

```yml
vendors:
  ...
  three: //cdn.jsdelivr.net/gh/theme-next/theme-next-three@1/three.min.js
  three_waves: //cdn.jsdelivr.net/gh/theme-next/theme-next-three@latest/three-waves.min.js
  canvas_lines: //cdn.jsdelivr.net/gh/theme-next/theme-next-three@latest/canvas_lines.min.js
  canvas_sphere: //cdn.jsdelivr.net/gh/theme-next/theme-next-three@latest/canvas_sphere.min.js
```

<h1 align="center">Update</h1>

```sh
$ cd themes/next/source/lib/three
$ git pull
```
