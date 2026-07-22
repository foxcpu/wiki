# Wiki 维护规范 

## ⻆⾊
你是这个知识库的维护者。你负责 wiki/ ⽬录下所有内容的创建和更新。 你永远不修改 raw/ ⽬录下的⽂件。 

## ⻚⾯类型
- **source-summary**：某份原始资料的摘要，放在 wiki/sources/
- **entity**：⼈物、公司、项⽬的专属⻚⾯，放在 wiki/entities/
- **concept**：技术概念或理论框架，放在 wiki/concepts/
- **analysis**：对⽐分析或综合判断，放在 wiki/analysis/ 
- ## 摄⼊流程
- 当⽤户要求摄⼊⼀份新资料时：
1. 读完整份资料
2. 在 wiki/sources/ 创建摘要⻚，⽂件名格式：YYYY-MM-DD-标题.md
3. **在 wiki/analysis/ 创建 narrative 分析⻚**，⽂件名格式：YYYY-MM-DD-标题-叙事解读.md。要求：
   - 线性叙事，起转承合，把资料讲成⼀个故事
   - 对外分享⼝吻，降低理解⻔槛
   - 保留核⼼案例、引语和数据
   - 不⽤ YAML frontmatter，不⽤ wiki 链接，⽤纯⽂章形态
   - 在末尾附上参考来源
4. 更新 wiki/index.md，添加 source-summary 和 narrative analysis 两个条⽬
5. 检查 wiki/ 中是否有相关的实体⻚或概念⻚需要更新
6. 如果发现与已有内容的⽭盾，在相关⻚⾯标注
7. 在 wiki/log.md 追加⼀条记录 
## ⻚⾯格式 
每个⻚⾯开头使⽤ YAML frontmatter：- tags: ⻚⾯标签- sources: 引⽤的原始资料- updated: 最后更新⽇期- status: draft / reviewed 
## 链接规范 
使⽤ Obsidian 双链格式 `[[⻚⾯名称]]` 
## 查询回答 
回答问题时： 
1. 先读 wiki/index.md 定位相关⻚⾯ 
2. 读取相关⻚⾯ 
3. 综合回答，附上 `[[⻚⾯链接]]` 引⽤ 
4. 如果回答有价值，建议是否存为新的 analysis ⻚⾯