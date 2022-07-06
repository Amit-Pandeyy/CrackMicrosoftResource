# Take the Crack Job @Microsoft Challenge Today!!

>  **Connect with a Community of over 40,000 Coders** 
[![GitHub KushalVijay](https://img.shields.io/github/followers/KushalVijay?label=follow&style=social)](https://github.com/KushalVijay) 
![](https://img.shields.io/youtube/channel/subscribers/UCOZMPD9TMk0C4yipWBaPZ7w?label=Subscribe%20to%20our%20Channel%20&style=social)
[![Linkedin: Kushal Vijay](https://img.shields.io/badge/-Kushal%20Vijay-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/kushalvijay/)](https://www.linkedin.com/in/kushalvijay/)
[![Twitter: Kushal Vijay](https://img.shields.io/twitter/follow/KushalVijay_?style=social)](https://twitter.com/KushalVijay_)

## Enter the Challenge
- Fork & Star this Github Repo 🌟
- Share your progress every week by adding new commit every week.
- Make sure to add Hashtags to your repo **#CrackWithKushalVijay  #SavageForce  #JobHuntWithKushalVijay**
- Add details about your progress in the below table.
- Join our Doubt Resolution & Discussion Group: [**Enter Now!!**](https://t.me/vijaykushal) 👀

<br />

> "First, solve the problem. Then, write the code.” – John Johnson

<br/>

## Learning Plan (70 Amazing Problems for Microsoft)

Your Status can be: **Done ✅ | In Progress🕓 | Skipped❌**
<br>
Difficulty Rating: **Easy | Easy-Medium | Medium | Medium-Hard | Hard**

> **Problems for Week 1**

| Problem Link | Status | Difficulty |
| ------ | ------ | ------ |
| [2 Sum](https://leetcode.com/problems/two-sum/)  |Hashmap  |  |
| [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) |flag and start from end  |  |
| [Add 2 Numbers](https://leetcode.com/problems/add-two-numbers/) |Reverse them , then add and then again reverse  |  |
| [Copy linked list with arbitrary pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)  | Use hashmap |  |
| [Level Order Tree Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)  | queue and then loop based on queue size |  |
| [Connect all Siblings](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)  |Without using queue using two pointers  |  |
| [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) |two method substr and reverse  |  |
| [Find all Palindrome Substrings](https://leetcode.com/problems/palindromic-substrings/)  |  |  |
| [Find maximum single sell profit](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)  |  |  |
| [Missing Number](https://leetcode.com/problems/missing-number/)  |xor method and sum method  |  |


---
<br>

> **Problems for Week 2**

| Problem Link | Status | Difficulty |
| ------ | ------ | ------ |
| [Find all sum combinations]( https://leetcode.com/problems/combination-sum/) |Recursion and Backtarcking take and not take concept as all distinct answers will be unique  |  |
| [Regular Expression Matching]( https://leetcode.com/problems/regular-expression-matching/)  | Watch striver video dp -34 |  |
| [Clone a directed graph](https://leetcode.com/problems/clone-graph/)  |Use dfs approach along with hashmap return node* from function call dfs for each keep adding return node as neighbour at last return new node  |  |
| [Closest Meeting Point]( https://www.educative.io/m/closest-meeting-point) |Centroid is the closest point in most cases to handle edge case also check 8 neighbours of centroid  check solution once |  |
| [Search 2D Matrix]( https://leetcode.com/problems/search-a-2d-matrix//) |apply binary search by considering whole matrix as single array convert your mid to coordinates in each iteration x=mid/n , y=mid%n  use while(l<=r) when l=mid+1 and r=mid-1 |  |
| [Is Binary Number Multiple of 3]( https://practice.geeksforgeeks.org/problems/is-binary-number-multiple-of-30654/1)  |Find delta which (no of odd set bits - no of even set bits) if delta div by 3 then return 1 else return 0  |  |
| [Kadane's Algorithm]( https://leetcode.com/problems/maximum-subarray/)  |One trick first initialise ans= num[0] then calucalte prefix sum if(sum>ans) update ans whenever at any poimt sum<0 Update sum =0  |  |
| [Majority Element]( https://leetcode.com/problems/majority-element/)  |Exploit the always exist thing to find use a count and num variable  if(count=0) num = cur_value  if(cur_value==num) count++  else count--;  at the end return num as answer  |  |
| [Search in a Rotated Array]( https://leetcode.com/problems/search-in-rotated-sorted-array/)  |Use binary search for every one of left or right side is sorted check if target lies in that sorted part or not accordingly change the value of l and r  |  |
| [Check for BST]( https://leetcode.com/problems/validate-binary-search-tree/) |Use keeping the previous value method . i.e use a reference variable prev initilised to lowest value and do simple inorder at each point if(root->val<=prev) return false else update prev = val check left and right  |  |

---
<br>

> **Problems for Week 3**

| Problem Link | Status | Difficulty |
| ------ | ------ | ------ |
| [Finding middle element in a linked list]( https://leetcode.com/problems/middle-of-the-linked-list/)  |Use 2 pointer approach fast and slow pointer both initialised by head node while(fast && fast->next) fast->next->next slow->next after loop return slow as middle node
| [Root to leaf path sum](https://leetcode.com/problems/path-sum/)  |do a preorder traversal at each before calling left or right reduce target-=root->val if(left||right) return true  at each node check if its leaf if(leaf) and target=root->val return true  if(null) return false;
| [Reverse a linked list]( https://leetcode.com/problems/reverse-linked-list/)  |Use 3 sliding pointers intialised as a=head->next ,b=head,c=NULL loop while(b!=NULL) b->next=c c=b b=a, if(a) a=a->next  after loop return c;
| [Remove every k’th node]( https://practice.geeksforgeeks.org/problems/remove-every-kth-node/1/)  |Use 2 pointers cur and prev and variable temp initialised as k if(temp==1) delete node using prev node i.e set prev->next = cur->next and again set temp=k  use dummy node to take care of head prev = dummy 
| [Merge 2 sorted linked list]( https://leetcode.com/problems/merge-two-sorted-lists/)  |Use 3 pointers (l1,l2,cur) l1(list1) ,l2(list2) ,cur(new merged list) initialise cur as dummy node  also take head variable to store head  use merging technique store each new node in cur->next move corresponding pointer  |  |
| [Longest Even Length Substring such that Sum of First and Second Half is same]( https://practice.geeksforgeeks.org/problems/e015cb4d3f354b035d9665e7c8a54a7aefb1901b/1/) |  |  |
| [k largest elements in an array]( https://leetcode.com/problems/kth-largest-element-in-an-array/) |Priority queue / min heap can be used just keep largest k elements in your in each iteration first push element to heap if size>k pop out element  |  |
| [Mirror Tree]( https://leetcode.com/problems/invert-binary-tree/)  |Return type Node* for solve function first store value returned from left in temp node then store value from right in left  and after right call store right = temp  at last just return the root   |  |
| [Median of Two Sorted Arrays]( https://leetcode.com/problems/median-of-two-sorted-arrays/)  |Binary search approach apply binary search on shorter array then based on that make count decision for other array find l1,l2,r1,r2 and make decision based on their values    |  |
| [Determine if Two Trees are Identical]( https://leetcode.com/problems/same-tree/) | base case (if(n1==NULL or n2==NULL) return n1==n2;)  if(val not equal) return false  if(left && right) return true  else return false;    |  |
| [Max Rectangle in Binary Matrix]( https://leetcode.com/problems/maximal-rectangle/) |  |  |
| [Maximum Product Subarray ]( https://leetcode.com/problems/maximum-product-subarray/) |First divide all array to subparts not containig zero then call solve function for that subarray before this thing inittially run a for loop to check if zero exists if yes mark ans=0 else ans=INT_min  in solve function first find product of whole array if(+ve or size =1) return product directly else check left and right part product till first -ve from left or right return max(product/left,product/right)  |  |
| [Edit Distance](https://practice.geeksforgeeks.org/problems/edit-distance3702/1/) |DP Question 3 types of choices if character no equal insert(i,J+1) , delete(i+1,j) , replace(i+1,J+1)  base cases two i>=l1 return l2-j  or j>=l2 return l1-i  |  |
| [Longest Arithmetic Subsequence]( https://leetcode.com/problems/longest-arithmetic-subsequence/) |  |  |
| [Coin Change]( https://leetcode.com/problems/coin-change-2/)  |DP questions  take  and not take choices  return sum(of answers from both choices )  base cases  if(amount==0) return 1    if(amount<0 or index>=n) return 0   use DP Unbounded 0/1 knapsack  |  |

---
<br>

> **Problems for Week 4**

| Problem Link | Status | Difficulty |
| ------ | ------ | ------ |
| [Spiral Matrix II]( https://leetcode.com/problems/spiral-matrix-ii/) |Concept is similiar to printing a matrix in spiral form just maintain counter variable and keep incrementing at each step rest all those things are same   |  |
| [Largest Number ]( https://leetcode.com/problems/largest-number/) |Good question  Normal sort will not work here as we only want to compare the most significant digit of all the numbers so use the custom comparator before that firstly convert all the nums to string format and then in comparator t1 = a+b , t2=b+a  return t1>t2 as we want to sort them in descending order of most significant digit after this just traverse new sorted vector keep adding elements to ans string  |  |
| [Maximum Distance](https://leetcode.com/problems/maximum-distance-between-a-pair-of-values/) |2 approches 1st two pointer approach just be careful in checking bounds for this approach inner loop while(p1<n1 && p1<p2 && nums[p1] > nums2[p2]) p1++   while changing max ans also introduce one if condition to check for validity  2nd approach nlogn lower_bound binary search reverse the second array than for each element of first find lower_bound in reverse array this will be farthest element in original array satisfying our conditions     |  |
| [Next Permutation]( https://leetcode.com/problems/next-permutation/) |Striver SDE sheet questions 4 steps approach first start from back i=n-2 while(arr[i]>=arr[i+1]) i--  then find the element starting from back which is just greater than arr[i] let it be temp   swap(temp,arr[i])  atlast reverse from i+1 to arr.end()  before doing 2 and 3 step just have chcek if(i>=0) to save from whole descending array   |  |
| [Anti Diagonals]( https://leetcode.com/problems/diagonal-traverse/)  |Two approaches one using space where perform tarversal for each diagonal  and second approach is simulation that concept of direction based movement take dir variable dir=0 up move and dir=1 down move  also based on movement design a while loop also keep for some edge cases and if checks for assigning head to new movement for all that watch my leetcode solution  |  |
| [Hotel Bookings Possible]( https://www.interviewbit.com/problems/hotel-bookings-possible/) |Greedy based solution firstly sort both arrays start and depart and then whenever start[i] < depart[j] K--  else  while(dpart[j]<start[i]) J++ and K++  if at any point k<0 return false  after whole loop return true  |  |
| [Flip]( https://www.interviewbit.com/problems/flip/)  |Good question uses kadanes algorithm watch the solution . if(0) count++  if(1) count--  if(count>max) max= count , l=ltemp , r=i   if(count<0) ltemp = i+1 count=0;  after looping over the array  check if(l==-1) return {}  else return {l+1,r+1}  |  |
| [Rotting Oranges]( https://leetcode.com/problems/rotting-oranges/) |Famous question very well explained by striver Multisource BFS approach using queue Just use for loop on size method and keep a bool flag to check if you are infecting atleast one orange at a stage if(flag) count++   after size wala for loop  for multisource first loop through matrix and add (x,y) to queue if (2)   after completing the whole bfs make check if there any cell with 1 value left if yes then return -1 else return count    |  |
| [Shortest Unsorted Continuous Subarray ]( https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) |5 approaches to solve the question See the leetcode official solution Can also use monotonic stack solution very helpful Most optimal one is 1) traverse from begining and find break point i.e where nums[i]> num[i+1]  find min from this point to end  2) traverse from back find break point then find max from start to this point 3). find correct positions for these min and max element array between these positions , including them is our answer  |  |
| [Unique Paths]( https://leetcode.com/problems/unique-paths/) |3 approaches recursive solution first then dynamic programming using memoization 3rd and most optimal approach using combinatrics ans = (m+n-2)C(m-1)  or (m+n-2)C(n-1)  |  |
| [Maximum Depth of Binary Tree]( https://leetcode.com/problems/maximum-depth-of-binary-tree/) |Simple recursive solution use postorder tarversal get left height, right height  whichever is maximum add 1 to it then return it  base case if(root==null) return 0;  |  |
| [Vertical Order Traversal of a Binary Tree ]( https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/)  |Column and rows method do a preorder traversal and store values use unordered_map<int,unordered_map<int,multiset<int>>> mp  multiset is used because elements which lie on same column and same row they should be stored in sorted order after traversal again extract those values from map and store them in ans vector then return it as in map elements will be stored in ascending order of columns  |  |
| [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) |Similar to level order tarversal 1st approach could be like maintain a flag and then when flag =true  reverse the vector before pushing it into the ans vector change flag  and keep on doing this way level tarversal  2nd approach could be the striver one where you are pushing elemnts from back in temp array case1 and in case2 putting elements from front use ternary operator to find the index |  |
| [Populating Next Right Pointers in Each Node]( https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) |Good question 2 approaches for this 1st brute could be to use level order traversal then assigning the next pointers  2nd approach smart recursive solution in that going only leftmost element and than populating next pointers of nodes below this level  while(node->left)  for full aproach watch code  trick to use two pointers one cur and one prev  |  |
| [Longest Increasing Subsequence]( https://leetcode.com/problems/longest-increasing-subsequence/) |Watch striver video for LIS  |  |

---
<br>

> **Problems for Week 5**

| Problem Link | Status | Difficulty |
| ------ | ------ | ------ |
| [Partition List](https://leetcode.com/problems/partition-list/) |Two pointer solution by using two dummy and creating two lists from same node by using thosetwo pointers after looping over the list just those two list using t1 and dummy d2  one thing you should ensure that after loop is over assign t2->next =NULL as new list it should be null Yaha me fasa bhi tha question me  |  |
| [Reverse Nodes in k-Group]( https://leetcode.com/problems/reverse-nodes-in-k-group/) |Watch striver video for iterative solution using prev ,cur,nex and count variable 4 steps process  cur->next = nex->next , nex->next = prev->next , prev->next = nex , nex = cur->next   |  |
| [Tapping Rain Water]( https://leetcode.com/problems/trapping-rain-water/) |  |  |
| [Simplify Path](https://leetcode.com/problems/simplify-path/) |  |  |
| [Min Stack](https://leetcode.com/problems/min-stack/) |  |  |
| [All Unique Permutations ](https://leetcode.com/problems/permutations-ii/) |  |  |
| [Generate all Parentheses](https://leetcode.com/problems/generate-parentheses/)  |  |  |
| [Largest Continuous Sequence Zero Sum](https://www.interviewbit.com/problems/largest-continuous-sequence-zero-sum/)  |  |  |
| [Group Anagrams](https://leetcode.com/problems/group-anagrams/) |  |  |
| [LRU Cache](https://leetcode.com/problems/lru-cache/) |  |  |
| [Construct Binary Tree From Inorder And Preorder]( https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) |  |  |
| [Number of Provinces ]( https://leetcode.com/problems/number-of-provinces/) |  |  |
| [Subsets](https://leetcode.com/problems/subsets-ii/) |  |  |
| [Valid Sudoku]( https://leetcode.com/problems/valid-sudoku/) |  |  |
| [Flatten Binary Tree to Linked List]( https://leetcode.com/problems/flatten-binary-tree-to-linked-list/ )  |  |  |
| [Gas Station]( https://leetcode.com/problems/gas-station/) |  |  |
| [Maximum Area of a Piece of Cake After Horizontal and Vertical Cuts ]( https://leetcode.com/problems/maximum-area-of-a-piece-of-cake-after-horizontal-and-vertical-cuts/)  |  |  |
| [Word ladder]( https://leetcode.com/problems/word-ladder-ii/) |  |  |
| [Meeting Rooms]( https://www.interviewbit.com/problems/meeting-rooms/) |  |  |
| [Distribute Candies]( https://leetcode.com/problems/distribute-candies/) |  |  |

---
## Contribute

Want to contribute? Great!
Make a change in your file and raise a PR.

## License

MIT

**Free Software, Hell Yeah!**

Disclaimer: Data collected from Internet and intended for educational purposes.

