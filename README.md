# Leetcode-2769.-Find-the-Maximum-Achievable-Number

# Solution
You're given:
1. An integer num
2. An integer t (maximum number of operations)

Each operation:
You can either:
1. Increase or decrease x by 1
2. And at the same time, increase or decrease num by 1

After at most t operations, find the maximum value that x can become so that x == num after those operations.

# Code
C++
class Solution {
public:
    int theMaximumAchievableX(int num, int t) {
        return num+(2*t);
        
}
};
