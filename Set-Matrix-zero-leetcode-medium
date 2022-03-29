//using hash map 

var setZeroes = function(matrix) {
    let m = matrix.length
    let n = matrix[0].length
    let hs = new Map
    let count = 0
    for(let i = 0 ; i < m ; i++){
        for(let j = 0 ; j < n ; j++){
            if(matrix[i][j] === 0){
                hs.set(count,[i,j])
                    count++ 
            }
        }
        
    }
    for(let i = 0 ; i < hs.size ; i++){
        for(let j = 0 ; j < n ; j++){
           let l = hs.get(i)[0];
           matrix[l][j] = 0
        }
        for(let k = 0 ; k < m ; k++){
             let l = hs.get(i)[1]
             matrix[k][l] = 0
        }
    }
};
