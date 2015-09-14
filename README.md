# challenge-form

Test out your functions by inputting it inside the textarea. Make sure it is wrapped in a gen function that returns your strategy. For example:

```    
function gen() {
      return function strategy(userPlayedArray,compPlayedArray) {
        var compArray = [1,2,3,4,5,6,7,8,9,10]
        compPlayedArray.forEach(function (e) {
          compArray.splice(compArray.indexOf(e), 1)
        })
        var random = Math.floor(Math.random()*compArray.length)
        return compArray[random]
      }
    }
```
