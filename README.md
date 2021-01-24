# leetcode

  [3,5,2,1]  //5 + 2 = 7

   function twoSum(array, target) {
    //nested loop 
        //add two nums and compare to target
            //return nums if sum is target
    for (let i = 0; i < array.length; i++) {
        for (let j = i + 1; j < array.length; j++) {
            if (num[i] + num[j] == target) {
                return [num[i], num[j]]
            }
        }
    }
    return []
   }
   //O(n^2)


   //eve, treert

   function isPalindrome(word) {
    //while right index is bigger than left index
        //check if left letter !== right letter
            //return false
        //++/-- pointers
    //return true
    leftPointer = 0
    rightPointer = word.length - 1
    while (leftPointer < rightPointer) {
     if (word[leftPointer] !== word[rightPointer]) {
        return false
     }
     leftPointer++
     rightPointer--
    }
    return true
   }
