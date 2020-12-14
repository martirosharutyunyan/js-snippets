# js snippets

Javascript, SCSS, Reactjs, Typescript + Reactjs, Nodejs snippets 


## Usage

keywords



**Enjoy!**
Keywords for easy working

```

cl=>    console.log($0)

c=>    const $1 = $0;

car=>   const $1 = [$0];

cob=>   const $1 = {$0};

l=>    let $1 = $0;

lob=>   let $1 = {$0};

lar=>   let $1 = [$0];

if=>        if (){

            }

ife=>       if (){

            } else{

            }

ef=>        else if () {

            }

sw=>        switch ($1) {
                case $2:
                    $0
                    break;
                default:
                    console.log('error')
            }

cs=>        case :

            break;

for=>       for (let i = 0; i < $1; i++) {
                $0
            }

forin=>     for (let key in $1) {
              $0
            }

forof=>      for (let key of $1) {
              $0
            }

fn=>        function (){

            }

fne=>       function(e){

            }

cf=>        const  = () =>{

            }

cfe=>       const  = e =>{

            }

cfl=>       const  = () =>

cfle=>      const = e =>

lineCallback=> ()=> 

lineCallbackE=> e=>

callback=>  ()=>{

            }

callbackE=> e=>{
  
            }

tr=>        try{

            } catch(err){
                console.log(error)
            }

r=>         return

ter=>       ? :

sfcc=>      String.fromCharCode($1)

jsonstr=>   JSON.stringify($0null2)

jsonparse=> JSON.parse($1)

imr=>       import React from 'react';

im=>        import $1 from '$0';

imp=>       import { $1 } from '$0';

impa=>      import React { useState useEffect useMemo memo } from 'react';

imrout=>    import { Route Switch NavLink Link } from 'react-router-dom';

imredux=>   import { useSelector useDispatch } from 'react-redux';

imty=>      import PropTypes from 'prop-types';

ima=>       import axios from 'axios';

dispatch=>  const dispatch = useDispatch();

dis=>       dispatch($1)

useEffect=> useEffect(() => {
             $1
            } [$0])

useState=>  const [$1 set$1] = useState($0)

mo=>        memo();

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

rjsx=>      return (
                <div key={$1}>
                    $0  
                </div>
            )

mapPrint=>  map(elem=>{
                return (
                    <div key={$1}>
                        $0  
                    </div>
                )
            })


map=>       map(elem=>{
                  if (elem.id === $1 ){

                  } 
                  return elem   
            })

ex=>        export default

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

rfc=>       import React, { useState, useEffect, useMemo, memo } from 'react';

            function $1 ($2){

            return (
                <div>
                    $0
                </div>
            )

            export default $1 = memo($1);

//scss
i=>         @include ();  


//nodejs
req=>       const $0 = require('$0');

reqfs=>     const fs = require('fs');

reqpath=>   const path = require('path');

reqexpress=>    const express = require('express');

reqmorgan=> const morgan = require('morgan');

reqaxios=>  const axios = require('axios');

reqasync=>  const async = require('async');

reqrimraf=> const rimraf = require('rimraf');

reqremove=> const remove = require('remove');

reqmongoose=>   const mongoose = require('mongoose');

appexpress=>    const app = express();

dotenv=>    require('dotenv').config();

reqbcrypt=> const bcrypt = require('bcrypt');

reqjsonwebtoken=>   const jwt = require('jsonwebtoken');

appRouter=> const app = express.Router();

schemaMongoose=>    const mongoose = require('mongoose');
                    const Schema = mongoose.Schema;
        
        
                    const userSchema = new Schema({
                        name:String,
                        surname:String$0,
                    });

                    const User = mongoose.model('User', userSchema)

                    module.exports=User

appListen=>         app.listen(port,()=> console.log(`server running on ${port}`)

appPost=>           app.post('./',async (req, res)=>{
                        try{
                            $0
                        } catch(err){
                        console.log(err)
                        }
                    }

mex=>       module.exports = $0;

errorNode=> (err,data)=>{
                if(err) throw err
                $0
            }

appuse=>    app.use()

fsfunc=>    fs.$1(path.join(__dirname, './', '$0'))



//Typescript

imr=>       import React from 'react';

im=>        import $1 from '$0';

imp=>       import { $0 } from '$1';

impa=>      import React, { useState, useEffect, useMemo, useRef, memo, FC } from 'react';

imrout=>    import { Route, Switch, NavLink, Link } from 'react-router-dom';

imredux=>   import { useSelector, useDispatch } from 'react-redux';

imty=>      import PropTypes from 'prop-types';

ima=>       import axios from 'axios';

rfc=>       import React, { useState, useEffect, useMemo, useRef, memo, FC } from 'react';,
            
            let $1:FC = () => {
                return (
                    <div>
                    
                    </div>,
                )
            }
        
        
            export default $1;

react=>     import React, { useState, useEffect, useMemo, useRef, memo, FC, } from 'react';
            import { Route, Switch, NavLink, Link } from 'react-router-dom';
            import { animateScroll as scroll } from 'react-scroll';
            import { useSelector, useDispatch } from 'react-redux';
            import { action } from '../../redux/actions/action';
            // import Media from '../../media';
            import axios from 'axios';
            import 'react-scroll';
            //types
            import { Redux } from '../../types/types';
            
            let $1:FC = () => {
            
                const dispatch = useDispatch();
            
                useEffect(() => {
            
                }, []);
            
                const [state, setState] = useState('');
            
                const arr = useSelector((state:Redux) => state.Reducer.arr);
            
                return (
                    <>
                        <section className=''>
                            
                        </section>
                    </>
                )
            }
            
            export default $1 = memo($1);

rjsx=>  return (
                <div>
                    $0
                </div>
            )

useState=>  const [$1, set$1] = useState<$2>($0);

useEffect=> useEffect(():void => {
                $0
            }, [$1]);

memo=>      memo($0);

useSelector=>   const $1 = useSelector((state:$2) => state.Reducer.$0);

useMemo=>   const $2 = useMemo(() => {
                return ($3)$4=> {
                    $0
                }
            }, [$1]);

mapPrint=>  $1.map((elem:$2,i:number)=>:JSX.Element {
                return (
                    <div key={elem.id}>
                        $0
                    </div>
                )
            })

map=>       $1.map((elem:$2)=> {
                if (elem.id === $1){
                    $0
                }
                return elem
            })

epd=>       e.preventDefault();

onclick=>   e.preventDefault();

onchange=>  onChange={($1)=> $0}

dispatch=>  const dispatch = useDispatch();

dis=>       dispatch($0)

cln=>       className='$0'

tr=>        try {
               $0
            } catch(err) {
               console.log(err)
            }

r=>         return $0

ter=>       $1 ? $2: $0

sfcc=>      String.fromCharCode($0)

jsonstr=>   JSON.stringify($0,null,2)

jsonparse=> JSON.parse($0)

k=>         ...$0

cl=>        console.log($0)

if=>        if ($1) {
                $0
            }

ife=>       if ($1) {
                $2
            } else {
                $0
            }

ef=>        else if ($1) {
                $0
            }

sw=>        switch ($1) {
                case $2:
                    $0
                    break;
                default:
                    console.log('error')
            }

swredux=>   switch (action.type) {
                case $2:
                    $0
                default:
                    return state
            }

cs=>        case $1:
                $0
                break;

csredux=>   case $1:
                return {
                    ...state
                    $0
                }

for=>       for (let i:number = 0; i < $1; i++) {
                $0
            }

forin=>     for (let key in $1) {
              $0
            }

forof=>     for (let key of $1) {
                $0
            }

cnum=>      const $1: number = $0

cstr=>      const $1: string = '$0'

cbool=>     const $1: boolean = $0

carr=>      const $1: $2[] = $0

cob=>       const $1: $2 = {
                $0
            }

lnum=>      let $1: number = $0

lstr=>      let $1: string = '$0'

lbool=>     let $1 : boolean = $0

larr=>      let $1: $2[] = $0

lob=>       let $1: $2 = {
                $0
            }

int=>       interface $1{
                $0
            }

intexp=>    export interface $1{
                $0
            }

type=>      type $1 = $0

typeexp=>   export type $1 = $0

typeob=>    type $1 = {
                $0
            }

typeobexp=> export type $1 = {
                $0
            }

typearr=>   type $1 = $0[]

typearrexp=>    export type $1 = $0[]

fnnum=>     function $1($2):number {
                $0
                return 
            }

fnstr=>     function $1($2):string {
                $0
                return 
            }

fnbool=>    function $1($2):boolean {
                $0
                return 
            }

fnvoid=>    function $1($2):void {
                $0
            }

fnjsx=>     function $1($2):JSX.Element {
                return (
                    <>
                        $0
                    </>
                )
            }

fn=>        function $1($2):$3 {
                $0
            }

exp=>       export default $0;

n>          number

s=>         string

indextsx=>  import React from 'react';
            import ReactDOM from 'react-dom';
            import rootReducer from './components/redux/store/store';
            import { BrowserRouter as Router } from 'react-router-dom';
            import thunkMiddleware from 'redux-thunk';
            import { Provider } from 'react-redux';
            import { createStore, applyMiddleware, compose } from 'redux';
            import App from './App';
            
            //const store=createStore(rootReducer)
            declare global {
                interface Window {
                  __REDUX_DEVTOOLS_EXTENSION_COMPOSE__?: typeof compose;
                }
            }
            
            const composeEnhancers = window.__REDUX_DEVTOOLS_EXTENSION_COMPOSE__ || compose;
            const store = createStore(rootReducer,composeEnhancers(applyMiddleware(thunkMiddleware)));
            
            ReactDOM.render(
                <React.StrictMode>
                    <Provider store={store}>
                        <Router>
                            <App />
                        </Router>
                    </Provider>
                </React.StrictMode>,
                document.getElementById('root'),
            );


cf=>        const $1 = ($2:): => {
                $0
            }

cfa=>       const $1 =async ($2:):Promise<void> => {
                $0
            }        

cfl=>       const $1 = ($2:): => $0

cfla=>       const $1 =async ($2:):Promise<void> => $0

lineCallback=>  ($1:):=> $0

lineCallbacka=>  async($1:):Promise<void>=> $0

callback=>  ($1:):=> {
                $0 
            }

callbacka=> async($1:):=> {
                $0 
            }

node ts

rq=>    require('');

fsimport=>  import fs from 'fs';

pathimport=>    import path from 'path';

expressimport=> import express from 'express';

morganimport=>  import morgan from 'morgan';

rimrafimport=>  import rimraf from 'rimraf';

removeimport=>  import remove from 'remove';

mongooseimport=>    import mongoose from 'mongoose';

puppeteerimport=>   import puppeteer from 'puppeteer';

nodemailerimport=>  import nodemailer from 'nodemailer';

appexpress=>    const app = express();

dotenv=>    dotenv.config();

bcryptimport=>  import bcrypt from 'bcrypt');

jsonwebtokenimport=>    import jwt from 'jsonwebtoken');

axiosimport=>   import axios from 'axios');

asyncimport=>   import async from 'async');

appRouter=> const app = express.Router();

schemaMongoose=>    import mongoose from 'mongoose';
                    const Schema = mongoose.Schema;
                     
                     
                    const userSchema = new Schema({
                        name:String,
                        surname:String,$0
                    });
                     
                    export const User = mongoose.model('User',userSchema)
                
appListen=> app.listen(port,()=> console.log(`server running on port $0`))

appPost=>   app.post('/',async (req:any, res:any):Promise<void>=>{
                try{
                    $0
                } catch(err){
                    console.log(err)
                }
            })

mex=>   module.exports =  ;

err=>   (err,data):void=>{
            if(err) throw err", 
            $0
        }

use=>   app.use('/$1',require('$0')

fsfunc=>    fs.$1(path.join(__dirname, './', '$0'))

server=>    import express from 'express';
            const app = express();
            import dotenv from 'dotenv'
            dotenv.config();
            const port:string | number = process.env.port;
            import morgan from 'morgan';
            import mongoose from 'mongoose';
                   
                   
            const mongoURL:string = process.env.mongoURL
                   
                   
            const MongoDB = ():void => {
                mongoose.connect(mongoURL,{
                    useNewUrlParser: true,
                    useUnifiedTopology: true,
                    useCreateIndex:true,
                },():void=> console.log('mongoDB connected'))
            }
            MongoDB()
            
            
            
            app.use(morgan(`dev`));
            app.use(express.json())
            app.use(express.urlencoded({
             extended: false
            }))
            
            $0
            
            
            app.listen(port, () => console.log(`server is runnig on port $1`))

nodemailer=>    import nodemailer from 'nodemailer';
                
                const transporter = nodemailer.createTransport(
                    {
                        host: "smtp.mail.ru",
                        port: 465,
                        secure: true, // if 465 true else false
                        auth: {
                            user: "",
                            pass: "",
                        },
                    }
                    {
                        from: "",
                    },
                );
                
                export const mailer= (message:):void => {
                    transporter.sendMail(message,(err):void => {
                        if (err) console.log('email dont exist')
                    });
                };

router=>    import express from 'express';
            const app = express.Router();
                    
            app.post('/',async (req, res):Promise<void>=>{
                try{
                    $0
                } catch(err){
                    console.log(err)
                }
            })
            
            module.exports = app;

comparebcrypt=> bcrypt.compare($1,$2,(err:Error,data:boolean):void=>{
                    if(data){
                        $0  
                    }
                })

hashbcrypt=>    bcrypt.hash($1,10,(err:Error,data:string):void=>{
                    $0
                })

mysql=> import mysql from 'mysql';
        
        
        export const conn = mysql.createConnection({
            host:'localhost',
            user:process.env.mysqlUser,
            database:process.env.mysqlDB,
            password:process.env.mysqlPassword
        })

mysqlconn=> conn.connect((err:Error):void=>{
                if(err) throw err
                console.log('mysqlDB connected')
            })

mysqlquery=>  conn.query($1,(err:Error,data:$2):void=>{
                    if(err) throw err
                    $0
                })

postgres=>  import { Client } from 'pg';
            
            export const client = new Client({
                database:process.env.postgresDBname,
                password:process.env.postgresDBpassword,
                port:5432,
                host:'localhost',
                user:'postgres',
            })

postgresconnection=>    client.connect((err:Error):void=>{
                            if(err) throw err
                            console.log('postgresDB connected')
                        })

postgresquery=> client.query($1,(err:Error,data:$2):void=>{
                    if(err) throw err
                    $0
                })

```