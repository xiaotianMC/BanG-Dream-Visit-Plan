# Plan MiriaGo Route Skill

## 中文版
本文用于指导 AI 更准确地为用户规划 MiriaGo 巡礼路线。
---
# 1. 作品与片区信息确认（重要）
## 必须读取 README 中的片区信息表
在规划任何巡礼路线前：
- 必须仔细读取 README 中的「片区信息表」。
- 确认每个片区实际收录的作品范围。
- 不得仅根据片区名称、地名或单个点位名称判断作品归属。
- 避免因名称相似、地点关联或地理位置接近导致作品归属误判。
---
# 2. 入境机场确认
在开始规划巡礼行程前：
- 必须主动询问用户乘坐赴日航班的抵达机场。
## 羽田机场（Haneda Airport）
如果用户抵达机场为羽田机场：
- 必须提示用户：
  - 羽田机场内包含部分巡礼点位。
- 主动询问用户：
  - 是否希望在抵达当天顺路安排羽田机场巡礼。
如果用户选择安排羽田机场巡礼：
需要综合判断是否适合作为当天行程，包括：
- 航班预计抵达时间
- 入境手续耗时
- 行李领取时间
- 前往住宿地点的交通路线
- 当天剩余可用时间
不得强行安排影响整体行程合理性的羽田巡礼。
## 其他机场
如果用户抵达机场不是羽田机场：
- 不主动推荐羽田机场相关点位。
- 除非用户主动提出相关需求。
---
# 3. 点位精简规则
当用户提出以下需求时：
- 减少巡礼点位
- 压缩巡礼时间
- 缩短整体行程
- 降低每日巡礼强度
应遵循以下优先级：
## 删除顺序
1. 优先移除 .sjhplan 中明确标记为「可选」的点位。
2. 再考虑：
   - 路线绕行严重的点位
   - 交通成本较高的点位
   - 与其他点位重复度较高的点位
## 保留原则
应尽量保留：
- 作品关联度高的核心点位
- 剧情关键地点
- 代表性场景
- 交通顺路的必巡点位
不得优先删除：
- 未标记为「可选」的重要点位
- 作品核心场景
---
# 4. 最终输出要求
生成最终 MiriaGo 巡礼计划时：
必须提醒用户阅读 GUIDE 中以下章节：
- 「信息时效性声明」
- 「文明巡礼&安全巡礼」
提醒内容必须包含：
- 巡礼资料可能随时间变化，存在过期风险。
- 出发前应再次确认最新信息。
- 遵守当地法律法规及场所规定。
- 尊重居民、工作人员以及当地环境。
- 注意个人安全，合理安排路线与时间。
---

# English Version
This document provides instructions for AI to better plan MiriaGo pilgrimage routes.
---
# 1. Work and Area Information Verification (Important)
## Always read the area information table in README
Before planning any pilgrimage route:
- Carefully read the "Area Information Table" in README.
- Verify which works are included in each area.
- Do not determine work ownership only from area names, location names, or individual spot names.
- Avoid incorrect classification caused by similar names, geographical proximity, or misleading location information.
---
# 2. Arrival Airport Confirmation
Before creating an itinerary:
- Always ask the user which airport their flight to Japan will arrive at.
## Haneda Airport
If the user's arrival airport is Haneda Airport:
- Inform the user that:
  - Haneda Airport contains pilgrimage locations.
- Ask whether they would like to include Haneda Airport pilgrimage spots on their arrival day.
If the user chooses to include Haneda Airport:
Evaluate whether it is suitable based on:
- Flight arrival time
- Immigration procedures
- Baggage collection time
- Transportation route to accommodation
- Remaining available time on the arrival day
Do not force Haneda pilgrimage into the itinerary if it would negatively affect the overall schedule.
## Other Airports
If the arrival airport is not Haneda Airport:
- Do not proactively recommend Haneda Airport pilgrimage spots.
- Only include them if the user specifically requests them.
---
# 3. Spot Reduction Rules
When the user requests:
- Fewer pilgrimage spots
- A shorter itinerary
- Reduced travel time
- Lower daily workload
Follow these priorities:
## Removal Priority
1. First remove spots marked as "Optional" in README.
2. Then consider removing:
- Spots requiring significant detours
- Spots with high transportation costs
- Duplicate or highly similar locations
## Preservation Priority
Keep:
- Highly relevant pilgrimage locations
- Important story locations
- Representative scenes
- Essential locations with efficient transportation routes
Do not prioritize removing:
- Important locations without an "Optional" label
- Core pilgrimage scenes
---
# 4. Final Output Requirements
When generating the final MiriaGo pilgrimage plan:
Always remind the user to read the following sections in GUIDE:
- "Information Validity Statement"
- "Responsible Pilgrimage & Safety Pilgrimage"
The reminder must include:
- Information may become outdated over time.
- Users should verify the latest information before departure.
- Follow local laws, rules, and facility regulations.
- Respect residents, staff, and the surrounding environment.
- Pay attention to personal safety and plan routes reasonably.