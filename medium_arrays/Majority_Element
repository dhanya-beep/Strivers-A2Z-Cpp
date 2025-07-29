class Solution {
public:
    int majorityElement(vector<int>& nums) {
        int maxi = nums[0];
        int count = 1;

        for(int i = 1; i <nums.size(); i++){
            if(maxi == nums[i]){
                count++;
            }
            else{
                count--;
            }
            if(count == 0){
                maxi = nums[i];
                count++; 
            }   
        }

        return maxi;
        
    }

};
