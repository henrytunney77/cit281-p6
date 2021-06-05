# cit281-p6

class shape{
    constructor(sides={}){this.sides=sides;
    }

    perimeter(){
return (this.sides.length)?this.sides.reduce((a,b) => a+b):0;

    }
}



class Rectangle extends Shape{
constructor(length=0,width=0){
    super([length, width,length,width]);

this.length=length;
this.width=width;
}

area(){
return this.length*this.width;
}}



class Triangle extends Shape{
constructor(lineA=0,lineB=0,lineC=0){
super (lineA,lineB,lineC)
this.lineA=lineA
this.lineB=lineB
this.lineC=lineC
}



area(){
    function sum (this.line, this.lineB, this.lineC);
return Math.sqrt(sum*(sum-this.lineA,sum-this.lineB, sum-this.lineC))
  }}
    


const data = [ [3, 4], [5, 5], [3, 4, 5], [10], [] ];

for(const element of data){
    console.log
}


//console.log(new Rectangle(4, 4).perimeter());  // 16
//console.log(new Rectangle(4, 4).area());  // 16
//console.log(new Rectangle(5, 5).perimeter()); // 20
//console.log(new Rectangle(5, 5).area()); // 25
//console.log(new Rectangle().perimeter()); // 0
//console.log(new Rectangle().area()); // 0

//console.log(new Triangle(3, 4, 5).perimeter());  // 12
//console.log(new Triangle(3, 4, 5).area());  // 6
//console.log(new Triangle().perimeter()); // 0
console.log(new Triangle().area()); // 0
