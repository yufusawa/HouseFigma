html {
  font-family: "Raleway", sans-serif;
  font-weight: 500;

}
body {
  margin: 0;
  padding: 0;
  
}
button {
  border-color: #598D66;
  border-radius: 0%;
  padding: 20px 60px;
  background-color: rgba(255, 255, 255, 0);
  color: #598D66;
  font-weight: 500;
  font-size: 20px;
  transition: 0.3s;
  
}
button:hover{
  background-color: #598D66;
  color: #F4F6F5;
}
.container{
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 100px;

}
.header {
 display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    background-color: #E1EDE6;
    height: 100px;
    

}

.header-left {

}
.header-right {
   /*
  display: flex;
  justify-content: space-between;
  align-items: center;
  
  gap: 60px;
  /*
  padding-left: 803px;
  padding-right: 165px;
  */
}
.header-right a {
  text-decoration: none;
  color: #2C2D35;
  size: 20px;
  transition: 0.3s;
  
}
.header-right:hover a {
  text-decoration: none;
  color: #598D66;
  size: 20px;
  
}
.logo-container {
  display: flex;
  
  align-items: center;
  gap: 8px;
  /*
  padding-left: 165px;*/
}
.logo-text {
  color: #598D66;
  font-weight: 700;
  size: 20px;

}

.hero {
  display: flex;
  flex-direction: column;
  position: relative; /*чтобы можно было выставить картинку к вверху отдельно от текста*/
  padding: 0 165px;
  min-height: 621px;
}
.hero-text {
  padding-top: 145px;
  padding-left: 735px;
  width: 540px; height: 132px;
}
.hero-text button{
  
  margin-top: 60px;
}
.hero img {
  position: absolute;
  top: 0;
}
.hero h1 {
  font-weight: 500px;
  font-size: 60px;
}
.hero-text p {
  color: #86928B;

}
.catalog {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 165px;
}
.catalog h2 {
  font-size: 40px;
  width: 255px;
  height: 44px;
}
.catalog-top {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}
.catalog-nav {
  width: 433px;
  height: 43px;
  display: flex;
  justify-content: space-between;
  gap: 32px;
}
.catalog-nav button {
  
  width: 126px;
  height: 43px;
  padding: 0 0;
  background-color: #D4E8D9;
  color: #2C2D35;
  border-radius: 20px;
  border: none;
  font-size: 20px;
  
}
.catalog-nav button:hover {
  background-color: #376B44;
  color: white;
}
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 350px;
  height: 730px;
  padding: 20px 0;
  background-color: #E1EDE6;
}
.card-author {
  color: green;
}
.card h3 {
  margin-right: 50%;
}
.card img {
  width: 310px;
  height: 422px;
}
.footer {
  background-color: #E1EDE6;
  height: 168px;
}
.card-container-main {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  
}
.card-container {
display: flex;
justify-content: space-around;
/*justify-content: center;
gap: 30px;*/
}