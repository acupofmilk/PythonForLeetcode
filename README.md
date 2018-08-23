class Solution:
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        bequeath = {}  #遗留下来的元素
        for i, num in enumerate(nums): #enumerate:创建一个(sequence,element)，可用于遍历的数据对象；
            if target - num in d: 
                return [bequeath[target - num], i]
            bequeath[num] = i


the second:
        for now in nums:
            for next in range(nums.index(now)+1,len(nums)):
                if now+nums[next]==target:
                    return (nums.index(now),next)
            
        
