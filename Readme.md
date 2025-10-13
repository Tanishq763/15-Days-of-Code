# 👋 Welcome to Vision CSE  

## Day - 1 

1.Leetcode POTD [link](https://leetcode.com/problems/find-resultant-array-after-removing-anagrams/submissions/1800321550)</br>
2.CF Q-> [link](https://codeforces.com/contest/2160/problem/C) Code-> [link](https://codeforces.com/contest/2160/submission/343544320)</br>
3.Leetcode [link](https://leetcode.com/problems/design-exam-scores-tracker/submissions/1800455078)</br>

## Day - 2

1.Leetcode [link](https://leetcode.com/problems/count-primes/submissions/1800688127)</br>
2.Striver A to Z Q.[link](https://www.geeksforgeeks.org/problems/count-subarray-with-given-xor/1) </br>
class Solution {</br>
  public:</br>
    long subarrayXor(vector<int> &nums, int k) {</br>
    long i,n = nums.size(),x = 0,ans = 0;</br>
    map<long,long>mp;</br>
    mp[0]++;</br>
    for(i = 0;i<n;i++){</br>
    x = x^nums[i];</br>
    ans = ans + mp[k^x];</br>
    mp[x]++;</br>
   } </br>
</br>
return ans;</br>
        </br>
  }</br>
};</br>





