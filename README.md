<h1 align="center">recently-updated</h1>

<p align="center">
  <a title='License' href="https://raw.githubusercontent.com/bmathews/recently-updated/master/LICENSE">
    <img src='https://img.shields.io/badge/license-MIT-blue.svg' />
  </a>
  <a href="https://badge.fury.io/js/recently-updated">
    <img src="https://badge.fury.io/js/recently-updated.svg" alt="npm version" height="18">
  </a>
</p>

<h4 align="center">
  See which packages you depend on were recently updated
</h4>

***

This cli tool shows you if packages you depend on had new versions published within the last 24 hours. If your CI builds start failing all of a sudden, or builds/tests are broken locally after a fresh npm install, seeing this list of packages and their latest publish times/versions might help you track the problem down quicker.

### Installation

With npm, do:
```
npm install -g recently-updated
```

### Usage
In a project directory with a `./node_modules`, do:
```
recently-updated
```

<div align="center">
<img src="https://cloud.githubusercontent.com/assets/848347/21056128/2593bee4-bde9-11e6-8e4a-db876575d8a0.png" />
</div>
