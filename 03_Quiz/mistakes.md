# Quiz Mistakes & Learning Gaps

只记录回答错误、不完整、理由错误或暴露重要概念漏洞的题目。完整 Quiz 保留在对应 Day Note。

## 2026-08-27 / Profit Growth vs Revenue Growth

### Question

看到：

```text
收入 +30%
净利润 +50%
```

作为公司分析者，下一步应该调查什么？

### My Answer

> 利润增长率大于收入增长率，需要看看公司那些地方把收入的增长抵消了。
> 可能是应收账款？购买存货？投资建设？

### Correct Understanding

观察到“利润增速与收入增速不同”并继续调查，这个方向是正确的。

但净利润增长快于收入通常意味着**利润率可能提高**，而不是收入增长被抵消。

第一步更适合调查：

- 毛利率是否提高
- 成本是否下降
- 费用率是否下降
- 产品结构是否变化
- 是否有一次性收益

应收账款、存货等项目更适合用于分析“利润与经营现金流为什么不匹配”。

### Why I Got It Wrong

主要认知问题是：

1. 对“收入 → 成本/费用 → 利润”的利润表逻辑还不熟悉。
2. 将利润表问题和现金流/资产负债表项目混在一起。
3. 已经知道要调查异常，但还没有形成“不同异常应该先查哪张表”的路径。

### Rule / Signal to Remember

> **利润异常 → 先查收入、成本、费用、利润率和一次性项目。**

> **利润与经营现金流不匹配 → 再重点查应收账款、存货等营运资金项目。**

### Related Concepts

- [Income Statement](../02_Concepts/income-statement.md)
- [Cash Flow Statement](../02_Concepts/cash-flow-statement.md)
- [Balance Sheet](../02_Concepts/balance-sheet.md)

---

## 2026-08-27 / Accounting Equation & Equity

### Question

公司有：

```text
现金        30 万
存货        20 万
设备        50 万
银行贷款    40 万
```

所有者权益是多少？

### My Answer

> 30 万。

### Correct Understanding

先汇总所有资产：

```text
总资产 = 30 + 20 + 50 = 100 万
```

再使用会计恒等式：

```text
所有者权益 = 资产 - 负债
           = 100 - 40
           = 60 万
```

正确答案是 **60 万**。

### Why I Got It Wrong

核心问题不是计算能力，而是**没有形成资产负债表计算的固定操作顺序**：

1. 先识别哪些项目属于资产。
2. 汇总总资产。
3. 识别负债。
4. 使用 `Equity = Assets - Liabilities` 求所有者权益。

这说明“资产 = 负债 + 所有者权益”的概念已经接触，但还没有稳定地用于实际报表项目。

### Rule / Signal to Remember

> **求所有者权益时，不要盯某一个资产项目。先算总资产，再减总负债。**

```text
Assets = Liabilities + Equity
Equity = Assets - Liabilities
```

### Related Concepts

- [Accounting Equation](../02_Concepts/accounting-equation.md)
- [Balance Sheet](../02_Concepts/balance-sheet.md)
