#Ejemplo Grid Areas  \
 
`.app-layout{
    
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows:100vh;
    grid-template-areas: "search tweets replies messages";
} `  \

`.tweets   { background-color: #A2DED0; grid-area: tweets;}
  .replies  { background-color: #F4D03F; grid-area: replies;}
  .search   { background-color: #6C7A89; grid-area: search;}
  .messages { background-color: #59ABE3; grid-area: messages;}`  \