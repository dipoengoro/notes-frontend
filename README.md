# Notes

<p>
<img src='https://img.shields.io/badge/node%20%20-v%5E12.18.0-brightgreen' alt='react-version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=%2361DBFB&label=react%20%20&prefix=v&query=dependencies.react&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-frontend%2Fmaster%2Fpackage.json' alt='react-version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=green&label=npm%20%20&prefix=v&query=dependencies.npm&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-frontend%2Fmaster%2Fpackage.json' alt='npm version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=%23A9A9A9&label=express%20%20&prefix=v&query=dependencies.express&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-backend%2Fmaster%2Fpackage.json' alt='express version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=%23841F27&label=mongoose%20%20&prefix=v&query=dependencies.mongoose&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-backend%2Fmaster%2Fpackage.json' alt='mongoose version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=%2332CD32&label=passport%20%20&prefix=v&query=dependencies.passport&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-backend%2Fmaster%2Fpackage.json' alt='passport version'/>
<img src='https://img.shields.io/badge/dynamic/json?color=%23805A46&label=chai-http&prefix=v&query=dependencies%5B%27chai-http%27%5D&suffix=%20%20&url=https%3A%2F%2Fraw.githubusercontent.com%2Fsiddheshkothadi%2Fnotes-backend%2Fmaster%2Fpackage.json' alt='chai-http version'/>

<a href='https://github.com/siddheshkothadi/'><img src='https://img.shields.io/github/followers/siddheshkothadi?label=Follow&style=social' alt='follow'/></a>
<a href='https://twitter.com/siddhesh_kt'><img src='https://img.shields.io/twitter/follow/siddhesh_kt?label=Follow%20siddhesh_kt&style=social' alt='follow'/></a>
</p>

### The simplest way to keep notes!

<p>Manage your notes. Add, view, edit or delete them easily.</p>
<p>This repository contains the code for the front end of <b>Notes</b>. Refer the <a href='https://github.com/siddheshkothadi/notes-backend'>express app</a> for back end side (RESTful API using Express and Node).</p>

<p align='center'>
  <img src='https://github.com/siddheshkothadi/notes-frontend/blob/preview/preview/Notes-Intro.gif' alt=':(' />
</p>

## Getting started

<p>These instructions will get you a copy of the project up and running on your local machine for development.</p>

### Prerequisites
<ol>
  <li><a href='https://nodejs.org/en/'>Node.js</a> - a JavaScript runtime</li>
  <li><a href='https://git-scm.com/downloads'>Git</a> - for cloning and version control</li>
</ol>

### Installing

<ul>
  <li><p>Clone the repository</p>
    
   ```
   git clone https://github.com/siddheshkothadi/notes-frontend
   ```
   ```
   cd notes-frontend
   ```

  </li> 
  <li><p>Install the dependencies</p>
    
   ```
   npm install
   ```

  </li>
  <li><p>After all the dependencies are installed, start the website on localhost:3000</p>
    
   ```
   npm start
   ```

  <p><b>NOTE:</b> Make sure you are running the <a href='https://github.com/siddheshkothadi/notes-backend'>back end server</a> on localhost:5000 !</p>
  </li>
</ul>

### Component tree

```
          App
          / \
         /   \
    Header   Dashboard
                /\
               /  \
         Textbox   Notes
         (To Add   (Contains 
          a Note)      Notes)
```
