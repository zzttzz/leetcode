笔记
====
## top-100-liked-questions

### Two Sum
创建一个空字典，然后依次把target-nums[x]的值存入字典，存入一个就跟nums[x+1]去比较， 字典中的key为target-nums[x],value为x，也就是nums[x]在nums列表中的索引位置。当字典d中有nums[x+1]时，也就是target - nums[y] = nums[x+1] , y肯定是小于x+1的(因为y是x+1之前循环过的数字)<br>
stl vector 用下标索引赋值不会改变.size()的值，也就是说其不会识别改变，应用.put_back()<br>
map.insert(std::pair<T1,T2>(a1,a2))

