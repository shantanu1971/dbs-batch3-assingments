# dbs-batch3-assingments

export const courses:Course[]=[
{"courseId":10,"courseName":"Computer Science","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Computer Sciences are taught"}
{"courseId":11,"courseName":"Accounting","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Accounting taught"}
{"courseId":12,"courseName":"Genetics","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Animal Genetics taught"}
{"courseId":13,"courseName":"English","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"English Language is taught"}
{"courseId":14,"courseName":"History","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"World Histry is taught"}
{"courseId":15,"courseName":"Physics","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Pysics is coverd in details"}
{"courseId":16,"courseName":"Chemistry","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Chemical Sciences are taught"}
{"courseId":17,"courseName":"Electronics","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Electronics are taught"}
{"courseId":18,"courseName":"Commerce","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Commerce and accounting taught"}
{"courseId":19,"courseName":"Home Science","slots":3,"duration":"4 years","contact":"Department of Computer Science","Overview":"Home Management and Cooking taught"}

]

CSS:


h1 {
    color: #369;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 250%;
  }
  h2, h3 {
    color: #444;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: lighter;
  }
  body {
    margin: 2em;
  }
  body, input[type="text"], button {
    color: #333;
    font-family: Cambria, Georgia;
  }
  /* everywhere else */
  * {
    font-family: Arial, Helvetica, sans-serif;
  }
  
  /* HeroesComponent's private CSS styles */
.heroes {
    margin: 0 0 2em 0;
    list-style-type: none;
    padding: 0;
    width: 15em;
  }
  .heroes li {
    cursor: pointer;
    position: relative;
    left: 0;
    background-color: #EEE;
    margin: .5em;
    padding: .3em 0;
    height: 1.6em;
    border-radius: 4px;
  }
  .heroes li:hover {
    color: #607D8B;
    background-color: #DDD;
    left: .1em;
  }
  .heroes li.selected {
    background-color: #CFD8DC;
    color: white;
  }
  .heroes li.selected:hover {
    background-color: #BBD8DC;
    color: white;
  }
  .heroes .badge {
    display: inline-block;
    font-size: small;
    color: white;
    padding: 0.8em 0.7em 0 0.7em;
    background-color:#405061;
    line-height: 1em;
    position: relative;
    left: -1px;
    top: -4px;
    height: 1.8em;
    margin-right: .8em;
    border-radius: 4px 0 0 4px;
  }
