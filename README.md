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
