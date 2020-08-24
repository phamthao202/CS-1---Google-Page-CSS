# CS-1---Google-Page-CSS
googlepageCSS
.nav-style{
    text-align: right;
}
.menu-style{
    text-decoration: none;
    margin: 10px;
    font-size: 13px;
    color: rgba(0,0,0,0.87);
}
.menu-style:hover{
    text-decoration: underline;
    color:grey;
}
.fa-bars{
    margin: 10px;
}
.fa-address-card{
    margin:10px;
}
.google-pic{
    text-align: center;
    padding-top: 150px;

}
.input-container{
    text-align: center;

}
input{
    width: 600px;
    height: 45px;
    font-size: 20px;
    box-shadow: none;
    padding-left: 60px;
    margin-bottom: 25px;
    border-radius: 25px;
    border: 1px solid rgb(223, 223, 223);
  }
input:focus{
    border: 1px solid white;
    outline: 0px solid white;
    box-shadow: 0px 1px 5px 1px rgb(223, 223, 223)
}
input:hover{
    border: 1px solid white;
    outline: 0px solid white;
    box-shadow: 0px 1px 5px 1px rgb(223, 223, 223);
}
.button-container{
    text-align:center;
}
button {
    margin: 5px;
    width: 200px;
    height: 40px;
    border: none;
    font-size: 14px;
    color: #5d5d5d;
    border-radius: 5px;
    background-color: #eeeeee;
  }
  button:hover {
    color: black;
    border: 0.5px solid #bfbfbf;
    box-shadow: 0px 0.5px 2px 1px rgb(223, 223, 223);
  }
.dong-chu{
    text-align: center;

}  
.language{
    text-decoration: none;
}
.language:hover{
    text-decoration: underline;
}
html,
body {
  margin: 0px;
  height: 100%;
  display: flex;
  font-size: 13px;
  flex-direction: column;
}
a {
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  
  .languages-header > a {
    margin-left: 5px;
    margin-right: 5px;
    display: inline-block;
  }
  
  footer {
    margin-top: auto;
  }
  
  footer > div {
    padding: 15px;
    background-color: #f2f2f2;
    border-top: 1px solid #e4e4e4;
  }
  
  footer * a {
    margin-left: 25px;
    color: rgba(0, 0, 0, 0.54);
  }
  
  .second {
    display: flex;
  }
  
  .left {
    flex: 1;
  }
  
  .right {
    flex: 1;
    display: flex;
    justify-content: flex-end;
  }
  .mic {
    top: 0px;
    width: 24px;
    left: -50px;
    height: 24px;
    position: relative;
  }
  
  .search {
    top: 0px;
    right: 650px;
    position: relative;
  }
