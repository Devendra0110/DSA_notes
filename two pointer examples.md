### Two pointer examples
1.   ```
      function reverseArray(nums){
          for(let r=nums.length-1,l=0;r>l;r--,l++){
             [nums[r], nums[l]] = [nums[l], nums[r]]
          }
          return nums
      }   
      ```
