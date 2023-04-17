<h1 align="center">
  Greppiina
 </h1>
  
<p>
  Greppiina is a mini version of Grep which is a program that selects lines
  in a file which match a given pattern.
  
  <br/>
  
  This was an exercise done by following the guide provided by the Rust book to recap the major concepets that I have
  learned so far.
  
  Following the policy:
  **This project is not reviewed or supported by the Rust Foundation.**
</p>

<h2>
  Example
</h2>

<h3> Get started: </h3>
  
  `git clone https://github.com/ElmeriVincent/greppiina.git`
  
  `cd greppiina`
  
   Make sure you have rust and cargo installed: 
   https://doc.rust-lang.org/cargo/getting-started/installation.html
  
<h3> Running it: </h3>

`cargo run -- to poem.txt `

in the previous command we have 2 arguments `to` which is the word we want to search for and `poem.txt`
which is the file we want to search from. The poem.txt is provided by default for testing purposes.

*Expected output 1:*

![Example1](https://user-images.githubusercontent.com/77973084/232539391-14275272-0e07-4afc-a9a7-868c15cf31d6.png)

You can also use enviroment variable `IGNORE_CASE=1` to see everything that includes the word `to`

`IGNORE_CASE=1 cargo run -- to poem.txt`
 
 if you are using Powershell, use: 
 `$Env:IGNORE_CASE=1; cargo run -- to poem.txt`

*Expected output 2:*

![Example2](https://user-images.githubusercontent.com/77973084/232539480-ae48e965-60bf-449d-84c5-4d6d2c9b52b2.png)
