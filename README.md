# paper
一些参考文献信息
## ASE
### 2025
#### RSfuzz   集群模糊测试，行为约束 鲁棒性
多机器人集群在战场侦察、农业害虫监测以及灾害搜救等复杂任务中发挥着关键作用。然而由于群体算法的复杂性，逻辑漏洞不可避免且往往会导致严重的安全后果。尽管已有多种通过软件测试检测逻辑漏洞的方法，但这些技术在群体环境中面临重大挑战：1）由于集群庞大的可组合参数空间，生成能触发故障的场景极为困难，而这对于有效暴露逻辑漏洞至关重要；2）由于集群高度灵活和动态的特性，建模和评估全局群体状态（尤其是协作行为方面）具有挑战性，这使得逻辑漏洞难以被检测。
本研究提出RSFuzz，一个用于检测多机器人系统逻辑漏洞的鲁棒性导向群体模糊测试框架。该框架利用行为约束的鲁棒性来量化评估群体状态，并指导生成故障触发场景。此外，RSFuzz能识别并针对关键集群节点实施扰动，有效缩减输入空间。基于该框架，我们构建了单攻击者模糊测试（SA-Fuzzing）和多攻击者模糊测试（MA-Fuzzing）两种方案，分别在测试过程中采用单个和多个攻击者干扰集群任务执行。我们在模拟环境中使用三种主流群体算法评估了RSFuzz的性能，结果表明其效果平均提升17.75%，效率提高38.4%，优于现有最优技术。部分检测到的漏洞已在真实环境中得到验证。相关代码和数据已开源。
关键词—模糊测试，行为约束，群体，逻辑漏洞，鲁棒性

### 2024
#### *Towards Understanding the Effectiveness of Large Language Models on Directed Test Input Generation  华科

#### *SlicePromptTest4J: High-coverage Test Generation using LLM via Method Slicing  北大

#### Effective Vulnerable Function Identification based on CVE Description Empowered by Large Language Models 华科  脆弱函数识别?

#### DroneWiS: Automated Simulation Testing of small Unmanned Aerial System in Realistic Windy Conditions   Saint Louis University, Missouri 无人机测试
