# Angular7firebase

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.2.

## Install firebase
`npm install -g firebase-tools` 

## Login to firebase account
`firebase login` 
 
 ## Install firebase into current project
`npm install firebase @angular/fire --save `

## Login to firebase, copy this code segment:
<img src="https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/deploy/Images/16.png">

## Paste the copied segment into environment.ts and environment.prod.ts: 
The segement should look like this:
<img src="https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/deploy/Images/3.png">

## Initialize firebase
`firebase init`
    
## Compile and minify code into a single package (./dist)
`ng build --prod`

## Deploy application
`firebase deploy`

## If any changes are made...
`firebase login; firebase init; ng build --prod; firebase deploy`
