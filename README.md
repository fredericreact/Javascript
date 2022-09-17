# Function

> Avant : 

    const Hello = function(param){
    
    };
<br>

> ES6 : 

    const Hello = (param) => {
    
    };
<br>

> Si j'ai un seul param : 

    const Hello = param => {
    
    };
    
> Si ca return que une valeur, alors on peut virer les {} : 

    const Hello = (param1,param2) => param1+param2;
    
> Return1 : 

    const Hello = (param) => (
    
    );   
<br>

> Return2 : 

    const Hello = (param) => {
    
    return(
    
    )
    
    };   
<br>

>Callback 

    boxes.forEach((divBox, index) => {

    });
    
>Traditional Anonymous Function
 
    (function (a) {
      return a + 100;
    });

    (a) => {
      return a + 100;
    };

>Regular function

    function France() {
      console.log("France");
    }
    France();

    const Germany = () => {
      console.log("Ger");
    };
    Germany();

    const Poland = () => console.log("Pol");
    Poland();

>Return function

    function UK() {
      return "UK";
    }
    console.log(UK());

    const Russia = () => "Russia";
    console.log(Russia());
