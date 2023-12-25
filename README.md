import React from 'react'
const user=[
  {
  name:"Dinesh",
  email:"dineshmcm07@gmail.com"
 },
 {
  name:"Mahendiran",
  email:"mahendiran28@gmail.com"
 },
 {
  name:"Amudha",
  email:"amudhamcm28@gmail.com"
 },
 {
  name:"Kavitha",
  email:"kavithamcm28@gmail.com"
 },
]


function App() 
{ 
  user.map((e,i)=>{
    return <>
    <h1>Welcome to React Day2 {e.name} and login mail is{e.email}</h1>
    </>
    })
  
}

export default App