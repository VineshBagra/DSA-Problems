/* Need to find out pair of integers which results in target sum. O(n2) solution is straight forward but we can optimize it.
   Target is a sum of two elements and if we store the remaining sum after each element traversal and then later 
   if we find the remaining sum in the array that means we have found the pair
*/
public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> map = new HashMap<>();
        for(int i=0; i<nums.length; i++){
            if(map.containsKey(nums[i])){
                return new int[] {map.get(nums[i]), i};
            }

            map.put(target-nums[i], i);
        }

        return null;
    }
