# 第1章 算法在计算中的作用

## 1、算法

         ****非形式地说，算法（algorithm）就是任何良定义的计算过程，该过程取某个值或值的集合作为输入并产生某个值或值的集合作为输出。就是把输入转换成输出的计算步骤的一个序列。

## 2、难题

        ****NP完全问题（NON-DETERMINISTIC PPLYNOMIAL）

        **NP完全问题\(NP-C问题\)**，是**世界七大数学难题**之一。 NP的英文全称是Non-deterministic Polynomial的问题，即多项式复杂程度的非确定性问题。简单的写法是 NP=P？，问题就在这个问号上，到底是NP等于P，还是NP不等于P。

        ****这七个“世界难题”是：NP完全问题、 [霍奇猜想](https://baike.baidu.com/item/%E9%9C%8D%E5%A5%87%E7%8C%9C%E6%83%B3/4679720)、[庞加莱猜想](https://baike.baidu.com/item/%E5%BA%9E%E5%8A%A0%E8%8E%B1%E7%8C%9C%E6%83%B3/4530364)、[黎曼假设](https://baike.baidu.com/item/%E9%BB%8E%E6%9B%BC%E5%81%87%E8%AE%BE/6891118)、[杨-米尔斯存在性和质量缺口](https://baike.baidu.com/item/%E6%9D%A8-%E7%B1%B3%E5%B0%94%E6%96%AF%E5%AD%98%E5%9C%A8%E6%80%A7%E5%92%8C%E8%B4%A8%E9%87%8F%E7%BC%BA%E5%8F%A3)、[纳卫尔-斯托可方程](https://baike.baidu.com/item/%E7%BA%B3%E5%8D%AB%E5%B0%94-%E6%96%AF%E6%89%98%E5%8F%AF%E6%96%B9%E7%A8%8B)、[BSD猜想](https://baike.baidu.com/item/BSD%E7%8C%9C%E6%83%B3)。这七个问题都被悬赏一百万美元。

        **P类问题**：所有可以在多项式时间内求解的判定问题构成P类问题。

         **判定问题**：判断是否有一种能够解决某一类问题的能行算法的研究课题。

         **NP类问题**：所有的非确定性多项式时间可解的判定问题构成NP类问题。

        **非确定性算法**：非确定性算法将问题分解成猜测和验证两个阶段。算法的猜测阶段是非确定性的，算法的验证阶段是确定性的，它验证猜测阶段给出解的正确性。设算法A是解一个判定问题Q的非确定性算法，如果A的验证阶段能在多项式时间内完成，则称A是一个多项式时间非确定性算法。有些计算问题是确定性的，例如加减乘除，只要按照公式推导，按部就班一步步来，就可以得到结果。但是，有些问题是无法按部就班直接地计算出来。比如，找大质数的问题。有没有一个公式能推出下一个质数是多少呢？这种问题的答案，是无法直接计算得到的，只能通过间接的“猜算”来得到结果。这也就是非确定性问题。而这些问题的通常有个算法，它不能直接告诉你答案是什么，但可以告诉你，某个可能的结果是正确的答案还是错误的。这个可以告诉你“猜算”的答案正确与否的算法，假如可以在多项式（polynomial）时间内算出来，就叫做多项式非确定性问题。

        **NPC问题：**NP中的某些问题的复杂性与整个类的复杂性相关联.这些问题中任何一个如果存在多项式时间的算法,那么所有NP问题都是多项式时间可解的.这些问题被称为NP-完全问题\(NPC问题\)。

        ****第一，虽然迄今为止不增找到对一个NP完全问题的有效算法，但是也没有人能证明NP完全问题确实不存在有效算法。对于所有NP完全问题，是否存在有效算法是未知的。

        ****第二，NP完全问题集具有一个非凡的性质：如果任何一个NP完全问题存在有效算法，那么所有NP完全问题都存在有效算法。

        ****第三，有几个NP完全问题类似于一些有着一直有效算法的问题。

## 3、效率

       ****为求解相同问题而设计的不同算法在效率方面常常具有显著的差别。这些差别可能比由于硬件和软件造成的差别要重要得多。


