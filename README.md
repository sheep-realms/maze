# Ancient Cube

<div style="text-align: center;">

![Title](res/img/title/title_748px.png)

</div>

这一个实验性的扫雷游戏。

## 游戏规则
1. 手持探索工具点击未探索方块进行探索，手持武器点击未探索方块进行攻击。
2. 探索遇到宝箱则获得奖励，遇到怪物则发生战斗，否则显示附近8个方块不同类型的计数。
3. 发生战斗时：
    - 如未手持武器，则判定被攻击；
    - 如手持武器，则尝试攻击怪物：
      - 如成功击杀怪物，则获得战利品；
      - 如未成功击杀怪物，则进入防御阶段；
      - 如未成功防御怪物的所有攻击，则判定被攻击。
4. 遇到宝箱时：
    - 如未手持武器，则获得战利品；
    - 如手持武器，则破坏宝箱。
5. 武器进行攻击、防御时会损耗耐久。
6. 受到等同于当前 HP 且大于 1 的攻击时，削减 1 点所受攻击。
7. 可通过梯子等通道前往下一层。
8. HP 归零时，游戏结束。