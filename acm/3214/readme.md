Description

有N 个军训新学员开始了他们的军训生活，第一天教官教他们站队，根据他们的身高，站成“凸”字形或者“凹”字形，也就是从左到右身高依次递增再递减或者依次递减再递增，如果是“凸”字形队列，身高最高的人可以有一个或者多个，其他人必须严格递增或或者递减，同样地，如果是“凹”字形队列，身高最矮的人可以有一个或者多个，其他人必须严格递增或者递减，现在这N 个同学已经站好了队，请你来判断一下现在这个队形是否是“凸”的或者“凹”的，如果是即输出YES，否则输出NO。
Input

一个整数T(T<=50)表示数据组数，接下来每组数据包含两部分，首先是一个整数N(N<=100000)，表示人数，然后下一行N 个整数，表示每个人的身高h(h<=100000)。
Output

对于每组数据，如果队列是“凸”的或者“凹”的，则输出YES，否则输出NO。
Sample Input

5

5

1 2 3 2 1

5

3 2 1 2 3

5

1 1 2 1 1

5

1 2 3 4 5

5

5 4 3 2 1

Sample Output

YES

YES

NO

NO

NO
