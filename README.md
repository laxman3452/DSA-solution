# DSA-solution

# 1) Sum of All elements in a two dimensional array.

## Code

Inline `code`

Indented code

    // code
    let sum = 0;
    let twoD = [[1,2,3],[4,5],[1,2,4,5]];
    for(let i=0;i<twoD.length;i++){
      for(let j=0;j<twoD[i].length;j++){
          sum += twoD[i][j];
      
      }
    }
    console.log(sum);

# 1) Sum of lower traingle in a matrix.

## Code

Inline `code`

Indented code

    // code
    let lowerSum = 0;
    let twoD = [[1,2,3],[4,5,6],[1,2,4,]];
    for(let i=0;i<twoD.length;i++){
      for(let j=0;j<=i;j++){
          uppeSum += twoD[i][j];
      
      }
    }
    console.log(upperSum);

# 1) Sum of upper traingle in a matrix.

## Code

Inline `code`

Indented code

    // code
    let upperSum = 0;
    let twoD = [[1,2,3],[4,5,6],[1,2,4]];
    for(let i=0;i<twoD.length;i++){
      for(let j=twoD[i].length-1;j>=i;j--){
          upperSum += twoD[i][j];
      
      }
    }
    console.log(upperSum);




