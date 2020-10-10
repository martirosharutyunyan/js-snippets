# js-snippets README

This is the README for your extension "js-snippets". After writing up a brief description, we recommend including the following sections.

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
Keywords for easy working

cl=>    console.log($0)
c=>    const $1 = $0;
car=>   const $1 = [$0];
cob=>   const $1 = {$0};
l=>    let $1 = $0;
lob=>   let $1 = {$0};
lar=>   let $1 = [$0];

if=>    if (){

}

ife=>   if (){

} else{

}

ef=> else if () {

}

sw=>  switch ($1) {
              case $2:
                $0
                break;
              default:
                console.log('error')
            }

cs=>    case :
          
  break;

for=>   for (let i = 0; i < $1; i++) {
              $0
            }

forin=>     for (let key in $1) {
              $0
            }

forof=>      for (let key of $1) {
              $0
            }

fn=>    function (){

}

fne=> function(e){

}

cf=> const  = () =>{

}

cfe=> const  = e =>{

}

cfl=>   const  = () =>

cfle=>  const = e =>

lineCallback=> ()=> 

lineCallbackE=> e=>

callback=>  ()=>{

}

callbackE=> e=>{
  
}

tr=>    try{

} catch(err){
    console.log(error)
}

r=> return

ter=> ? :

sfcc=>  String.fromCharCode($1)

jsonstr=> JSON.stringify($0null2)

jsonparse=> JSON.parse($1)

imr=>   import React from 'react';

im=>    import $1 from '$0';

imp=>   import { $1 } from '$0';

impa=>  import React { useState useEffect useMemo memo } from 'react';

imrout=>    import { Route Switch NavLink Link } from 'react-router-dom';

imredux=>   import { useSelector useDispatch } from 'react-redux';

imty=>  import PropTypes from 'prop-types';

ima=>   import axios from 'axios';

dispatch=>  const dispatch = useDispatch();

dis=>   dispatch($1)

useEffect=> useEffect(() => {
             $1
            } [$0])

useState=>  const [$1 set$1] = useState($0)

mo=> memo();

useSelector=>   const $1 = useSelector(state => state.Reducer$0)

useMemo=>   useMemo(() => {
              return ($1)=>{
                $2
              }
            } [$0])

cfuseMemo=> const  = useMemo(() => {
      return ()=>{
        
      }
  }, [])

rjsx=>   return (
             <div key={$1}>
               $0  
             </div>
           )

mapPrint=>    map(elem=>{
             return (
               <div key={$1}>
                 $0  
               </div>
             )
           })


mapPrint=>    map(elem=>{
                  if (elem.id === action.payload.id ){

                  } 
                  return elem   
              })

ex=> export default

react=>     import React, { useState, useEffect, useMemo, memo} from 'react';
            import { Route, Switch, NavLink, Link } from 'react-router-dom';
            import { animateScroll as scroll } from 'react-scroll';
            import { useSelector, useDispatch } from 'react-redux';
            import { action } from '../../redux/actions/action';
            import PropTypes from 'prop-types';
            // import Media from '../../media'; 
            import './container1.scss';
            import axios from 'axios';
            import 'react-scroll';
            
            
            function $1($2) {
            
                const dispatch = useDispatch();
                
                useEffect(() => {
                        
                }, []);
              
                const [state, setState] = useState('');
            
                const redux = useSelector(state => state.Reducer);
                
                return (
                    <>
                        <section className=''>
                            $0
                        </section>
                    </>
                )
            }
            
            $1.propTypes ={
                //state: PropTypes.array,
              
            }
            
            export default $1 = memo($1);

rfc=>  import React, { useState, useEffect, useMemo, memo } from 'react';
  function $1 ($2){

    return (
        <div>
            $0
        </div>
    )

  export default $1 = memo($1);

//scss
i=>   @include ();  


//nodejs
req=> const $0 = require('$0');

reqfs=> const fs = require('fs');

reqpath=> const path = require('path');

reqexpress=>  const express = require('express');

reqmorgan=> const morgan = require('morgan');

reqaxios=> const axios = require('axios');

reqasync=> const async = require('async');

reqrimraf=> const rimraf = require('rimraf');

reqremove=> const remove = require('remove');

reqmongoose=> const mongoose = require('mongoose');

appexpress=>  const app = express();

dotenv=>   require('dotenv').config();

reqbcrypt=> const bcrypt = require('bcrypt');

reqjsonwebtoken=> const jwt = require('jsonwebtoken');

appRouter=> const app = express.Router();

schemaMongoose=> const mongoose = require('mongoose');
        const Schema = mongoose.Schema;
        
        
        const userSchema = new Schema({
            name:String,
            surname:String$0,
        });
        
        const User = mongoose.model('User', userSchema)
        
        module.exports=User

appListen=> app.listen(port,()=> console.log(`server running on ${port}`)

appPost=>   app.post('./',async (req, res)=>{
            try{
              $0
            } catch(err){
              console.log(err)
            }
            }

mex=> module.exports = $0;

errorNode=>  (err,data)=>{
           if(err) throw err
           $0
         }

appuse=>  app.use()

fsfunc=>  fs.$1(path.join(__dirname, './', '$0'))
