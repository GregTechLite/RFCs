# Ice Cream Related Chain

- **Author(s)**: Catarrel
- **Created**: 2026-06-22

## Summary
- Add Ice cream chain and Ice-cream-related chains for edible purposes,
which includes **Milk Powder**, **Ice cream Emulsion (Main Body)**, **Cones**, and **Ice Creams**.
**Sodium carboxymethyl cellulose** is used in the chain of **Ice cream Emulsion**, which comes from the chains provided by **Leah_Torham**.

- 添加了冰淇淋产线与冰淇淋相关产线以做食用用途，
这包括**奶粉**，**冰淇淋乳液（主体）**，**蛋筒**与**冰淇淋**。
在**冰淇淋乳液**产线中使用的**羧甲基纤维素钠**来自于**莉娅的小助手**所提供的相关产线。

## Motivation
- To substitute the production process of a popular dessert into the game, which can not only set up a new branch aim for the gameplay, but also reuse, continue and expand the structure of the Nutrition Paste Chain; The Milk Powder Chain, related to the Ice Cream Chain, can also provide an usage expansion for milk in the game.

- 为了将一款大众喜爱的甜品的制作工艺流程代入游戏中，这不仅能为游戏体验设立一个新的支线目标，而且还能复用、延续、拓展现有的营养膏产线；与冰淇淋产线相关联的奶粉产线，也可为游戏中的牛奶提供一项使用拓展。

## Usage
- Ice creams can be used for edible purposes, and often provide additional potion effects (positive or negative) depending on the flavour and additive chemicals; Milk Powder can not only be engaged in Ice Cream Chain, but also can be directly prepared and drunk.
Prepared milk powder provides potion effect elimination when drunk, just as milk does.

- 冰淇淋不仅可以用作食用用途，还能获得一些额外的药水效果（正面或负面），取决于其口味与添加的化学成分；奶粉不仅可参与冰淇淋产线中，还可直接冲调并饮用。
冲调奶粉在饮用后可消除药水效果，就像牛奶一样。

### Processing
**Milk Powder:**
1. Milk UHT Sterilization
> 250mB **Milk** --[**Fluid Heater**, 480EU/t, 30t, Cleanroom]--> 250mB **Sterilized Milk**
2. Milk Dehydration
> 250mB **Sterilized Milk** --[**Chemical Dehydrator**, 64EU/t, 120t, Cleanroom]--> 1 **Milk Powder** + 250mB **Water**
3. Milk powder preparation
> - 1 **Milk Powder** + 1 **Water Bottle** --[**Shapeless Crafting**]--> 1 **Prepared Milk Powder**
> - 1 **Milk Powder** + 1 **Glass Bottle** + 250mB **Water** --[**Canning Machine**, 7EU/t, 10t]--> 1 **Prepared Milk Powder**

**Ice cream Emulsion (Main Body):**
0. Sodium carboxymethyl cellulose (provided by **Leah_Torham**, with EU/t and duration self-drafted)
> 21 **Cellulose Dust** + 6 **Sodium Hydroxide** + 16 **Chloroacetic Acid** + 4000mB **Ethyl Tert-Butyl Ether**(NC) --[**Chemical Reactor**, 1920EU/t, 240t]--> 49 **Sodium carboxymethyl cellulose** + 4 **Salt**
1. Aqueous phase
> 8 **Sugar** + 4 **Milk Powder** + 2 **Gelatin Dust** + 1 **Sodium carboxymethyl cellulose** + 1 **Programmed Circuit [5]**(NC) + 1B **Distilled Water** + 1B **Milk** --[**Mixer**, 480EU/t 96t, Cleanroom]--> 2B **Ice Cream Water Phase Mixture**
2. Crude emulsion
> 2B **Ice Cream Water Phase Mixture** + 1B **Food Oil Phase Mixture** --[**Mixer**, 1920EU/t, 160t]--> 3B **Ice Cream Crude Emulsion**
3. Ultrasonic Homogenization
> 3B **Ice Cream Crude Emulsion** + 1B **Distilled Water** --[**Sonication**, 1920EU/t, 600t]--> 4B **Ice Cream Emulsion**
4. Freezing and curing
> 4B **Ice Cream Emulsion** --[**Vacuum Freezer**, 480EU/t, 1200t]--> 4B **Cured Ice Cream Emulsion**

**Cones:**
1. Cone paste
> 4 **Flour** + 2 **Sugar** + 1 **Salt** + 1 **Programmed Circuit [5]**(NC) + 500mB **Egg Liquid** + 500mB [**Soybean Oil** / **Butter**] --[**Mixer**, 120EU/t, 48t]--> 1000mB **Cone Paste**
2. Cone
> 125mB **Cone Paste** + 1 **Mold (Cylinder)**(NC) --[**Fluid Solidifier**, 7EU/t, 15t]--> 1 **Ice Cream Cone**

**Ice Cream**
1. Ice Cream Ball
> 250mB **Cured Ice Cream Emulsion** + 1 **Mold (Ball)**(NC) --[**Fluid Solidifier**, 16EU/t, 100t]--> 1 **Ice Cream Ball**
2. Ice Cream Ball of different flavour
> 1 **Ice Cream Ball** + 100mB **Fruit Juice, Serum, etc** --[**Chemical Bath**, 30EU/t, 1t]--> 1**Ice Cream Ball (Flavour)**
3. Ice Cream
> 1 **Ice Cream Ball** + 1 **Ice Cream Cone** + 1 **Programmed Circuit [1]**(NC) --[**Food Processor**, 30EU/t, 40t]--> 1 **Ice Cream**
4. Ice Cream of different flavour and balls
> - Every 1 Ice Cream Ball, duration plus 40t.
> - Programmed Circuit [1]: single ball;
> - Programmed Circuit [2]: double ball, of same flavour;
> - Programmed Circuit [3]: double ball, of different flavour;
> - Awaiting for opinions on ice cream schemes--

------

**奶粉：**
1. 牛奶高温瞬时灭菌
> 250mB **牛奶** --[**流体加热器**, 480EU/t, 30t, Cleanroom]--> 250mB **灭菌牛奶**
2. 牛奶脱水
> 250mB **灭菌牛奶** --[**化学脱水机**, 64EU/t, 120t, Cleanroom]--> 1 **奶粉** + 250mB **水**
3. 奶粉冲调
> - 1 **奶粉** + 1 **水瓶** --[**无序合成**]--> 1 **冲调奶粉**
> - 1 **奶粉** + 1 **玻璃瓶** + 250mB **水** --[**装罐机**, 7EU/t, 10t]--> 1 **冲调奶粉**

**冰淇淋乳液（主体）：**
0. 羧甲基纤维素钠（由**莉娅的小助手**提供，EU/t与耗时自拟）
> 21 **纤维素粉** + 6 **氢氧化钠** + 16 **氯乙酸** + 4000mB **乙基叔丁基醚**(NC) --[**化学反应釜**, 1920EU/t, 240t]--> 49 **羧甲基纤维素钠** + 4 **盐**
1. 水相
> 8 **糖** + 4 **奶粉** + 2 **明胶** + 1 **羧甲基纤维素钠** + 1 **编程电路[5]**(NC) + 1B **蒸馏水** + 1B **牛奶** --[**搅拌机**, 480EU/t 96t, Cleanroom]--> 2B **冰淇淋水相混合物**
2. 粗乳液
> 2B **冰淇淋水相混合物** + 1B **食品用油相混合物** --[**搅拌机**, 1920EU/t, 160t]--> 3B **冰淇淋粗乳液**
3. 超声均质
> 3B **冰淇淋粗乳液** + 1B **蒸馏水** --[**超声震荡**, 1920EU/t, 600t]--> 4B **冰淇淋乳液**
4. 冷冻熟化
> 4B **冰淇淋乳液** --[**真空冷冻机**, 480EU/t, 1200t]--> 4B **熟化冰淇淋乳**

**蛋筒：**
1. 蛋筒面糊
> 4 **面粉** + 2 **糖** + 1 **盐** + 1 **编程电路[5]**(NC) + 500mB **蛋液** + 500mB [**大豆油** / **黄油**] --[**搅拌机**, 120EU/t, 48t]--> 1000mB **蛋筒面糊**
2. 蛋筒
> 125mB **蛋筒面糊** + 1 **模具（圆柱）**(NC) --[**流体固化器**, 7EU/t, 15t]--> 1 **冰淇淋蛋筒**

**冰淇淋**
1. 冰淇淋球
> 250mB **熟化冰淇淋乳** + 1 **模具（球）**(NC) --[**流体固化器**, 16EU/t, 100t]--> 1 **冰淇淋球**
2. 不同口味的冰淇淋球
> 1 **冰淇淋球** + 100mB **果汁，浆液，等等** --[**化学浸洗机**, 30EU/t, 1t]--> 1**冰淇淋球（口味）**
3. 冰淇淋
> 1 **冰淇淋球** + 1 **冰淇淋蛋筒** + 1 **编程电路[1]**(NC) --[**食品料理机**, 30EU/t, 40t]--> 1 **冰淇淋**
4. 不同口味与球数的冰淇淋
> - 每加1个冰淇淋球，耗时+40t
> - 编程电路[1]：单球；
> - 编程电路[2]：双球，相同口味；
> - 编程电路[3]：双球，不同口味；
> - 征集冰淇淋方案意见中——
