# triangulo-equilatero

//por David Feliciano


//tamaño del espacio de trabajo 
size(500,500);


//guias para ubicar las aristas por coordenadas 

ellipse(100,300,200,200);
ellipse(300,300,200,200);
ellipse(200,126,200,200);

//lineas guia de comprobacion 
line(100,300,300,300);
line(300,300,200,126);
line(200,126,100,300);

//triangulo equilatero 

fill(100);
triangle(100,300,300,300,200,126);

//comprobacion por medio de un circulo 
noFill();
ellipse(100,300,400,400);
