这是一个包含了27个算法类别的数据集
算法类别包括labels= ["Uncategorized", "动态规划", "图论算法", "图的遍历", "最短路径算法", "拓扑排序和关键路径", "并查集", "最小生成树", "数据结构", "树与二叉树", "堆和栈", "队列", "算法", "背包问题", "广度优先搜索", "深度优先搜索", "分治", "贪心", "递归", "递推", "排序", "高精度计算", "基础程序设计", "字符串", "二维数组", "一维数组", "for循环", "while与do-while语句", "循环嵌套", "switch语句", "if语句", "基础编程", "图的连通性", "函数", "链表", "顺序表", "哈希表", "面向对象"]

example
代码：

import java.util.Scanner;
public class FluDeathRate {
    public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    int confirmed = scanner.nextInt();
    int deaths = scanner.nextInt();
    double deathRate = (deaths / (double) confirmed) * 100;
    System.out.printf(\"%.3f%n\", deathRate);
    scanner.close();\n    }\n
    }

"label": "[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0]  #基础编程
其中label中为1代表该代码算法类型，对应了labels数组中的位置
