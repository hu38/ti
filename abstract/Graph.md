# Unweight Shortest Path
## 1 path   | one node  <-> one node
- int jumpGame(int[] nums) 
- int wordLadderLength(String beginWord, String endWord, List<String> wordList)
- List<String> removeInvalidParentheses(String s)
- int resolvePuzzleTwoByThree(int[][] board)
## 1 path   | one node  <-> any node
- int BFS(GraphNode start, List<GraphNode> goals)
## 1 path   | one node  <-> all nodes
- int BFS(GraphNode start, List<GraphNode> goals)
## 1 path   | any node  <-> one node
- int BFS(GraphNode start, List<GraphNode> goals)
## 1 path   | any node  <-> any node
- int[][] updateMatrix(int[][] matrix)
- int wordLadderLengthOptimized(String beginWord, String endWord, List<String> wordList)
## 1 path   | any node  <-> all nodes
- int KBFS(List<GraphNode> inits, Set<GraphNode> targets)
- int orangeRotting(int[][] grid) 
## 1 path   | all nodes <-> any node
- void wallsAndGates(int[][] rooms)
## 1 path   | all nodes <-> all nodes
- List<Integer> putChair(char[][] gym)
- int shortestDistanceFromAllBuildings(int[][] grid)
- int putChairSum(char[][] gym)
- int minTravelForAllFriends(int[][] grid)
## all path | one node  <-> one node
- List<List<String>> wordLadderAllPaths(String beginWord, String endWord, List<String> wordList)

# Weighted Shortest Path
## 1 path   | one node  <-> any/all node - best first search
- long shortestTimeToOffice(String startNode, String endNode, String[][] edgeList)
- int minEffortPath(int[][] matrix)
- int swimInRisingWater(int[][] grid)
- int kthSmallestInSortedMatrix(int[][] grid, int k)
- int maxTripCostKHighways(int n, int[][] highways, int k)
- int minCostOneValidPath(int[][] grid)
- boolean canReachCorner(int[][] grid, int limit)
- int minCostToReachCityWithDiscount(int n, int[][] highways, int discounts)
- int minCostToReachCityInTime(int maxTime, int[][] edges, int[] passingFees)

# Others
## Combinations
- int reachableNodesDivideGraphs(int[][] edges, int maxMoves, int n)
- long minSubgraphWeight(int n, int [][] edges, int src1, int src2, int dest)
- int raceCar(int target)
### Negative Weight - advanced algos 