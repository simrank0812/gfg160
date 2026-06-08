# gfg160
DAY-1 [1/6/26]
SECOND LARGEST
class Solution {
    public int getSecondLargest(int[] arr) {
        int largest = -1 , second = -1;
        for(int num : arr){
            if (num > largest){
                second = largest;
                largest = num;
            }
            else if(num > second && num !=largest){
                second = num;
            }
        }
        return second;
    }
}

[3/6/26]

Today I solved reverse array problem.

[4/6/26]


Today I solved next permutation problem.


[5/6/26]


Today I solved find majority problem.



[6/6/26]


Today I solved stock buy and sell multiple transaction problem.



[7/6/26]


Today I solved stock buy and sell one transaction allowed problem.





[8/6/26]


Today I solved minimize the height problem.




