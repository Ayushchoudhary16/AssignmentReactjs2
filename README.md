# AssignmentReactjs2

//App.js

import ProductInfo from "./assignment/Question1";
import WetherMessage from "./assignment/Question2";
import Employe from "./assignment/Question3";
import ProductList from "./assignment/Question4";

function App(){
    const productList = [
      {
        Name:"Pizza",
        price:"350",
        id :10,
      },
      {
        Name:"Pasta",
        price:"500",
        id :20,
      },
      {
        Name:"Burgger",
        price:"280", 
        id :30,
      },
      {
        Name:"Colddrink",
        price:"320", 
        id :40,
      },
    ];

return(
   <div className="App">
      <ProductInfo productName="Pasta" price="500"/>
      <WetherMessage isSunny={true}/>
      <ProductList products = {productList} />
      <Employe name="Ayush" position="Manager" salary="100000"/>  
  <div/>
)    
