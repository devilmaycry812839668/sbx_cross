本程序是实数编码遗传算法的交叉操作中的SBX 模拟二进制交叉
"""
输入：
    population 种群矩阵
    alfa 交叉概率
    numRangeList 决策变量的上限(下限默认为0)
    mu    SBX方式的分布指数, 推荐为1
"""

本模块需要调用numpy库, 无返回值，直接对传入的种群变量进行修改

接口如下：
    alfa=0.9
    population=np.random.rand(xN*yN).reshape(xN, yN)*1.0

    #决策变量的下限默认均为0，上限可以自定义
    numRangeList=np.array([1]*3)

    cross(population, alfa, numRangeList)


