# 简介
创建 BetterRa创建于2017年11月28日..他是在Rathena的基础上经过二次修改的一款模拟器, 加入了大量的功能..

# 更新日志

* 20171202  [添加] 脚本指令 warpparty2 用于传送整个组队, 可以传送死亡玩家
* 20171202  [添加] 脚本指令 setheaddir 调整角色头的朝向
* 20171202  [添加] 脚本指令 setbodydir 调整角色身体的朝向
* 20171202  [添加] 脚本指令 party_leave 让指定的角色立刻退出队伍
* 20171202  [添加] 脚本指令 openbank 让指定的角色立刻打开银行界面(只对拥有账号随身银行的客户端版本有效)
* 20171202  [添加] 脚本指令 instance_users 获取副本实例中的参与人数
* 20171202  [添加] 脚本指令 mesclear 清空当前NPC的对话框内容
* 20171202  [添加] 脚本指令 cap_value 用来确保数值变量不会低于最小值, 超过最大值
* 20171202  [添加] 脚本指令 mobremove 根据GID移除一个魔物(只是移除, 没有死亡动画)
* 20171202  [添加] 脚本指令 getsameipinfo 获得某个IP在线的玩家数以及玩家的角色编号等信息
* 20171202  [添加] 脚本指令 logout 使指定的角色立刻登出游戏(踢下线)
* 20171202  [添加] 脚本指令 searcharray 查询数组中第一次出现待查询内容的索引序号
* 20171202  [修改] 脚本指令 getinventorylist 添加返回 @inventorylist_idx[] 和 @inventorylist_uid$[]
* 20171202  [添加] 脚本指令 countinventory 根据指定背包序号, 获取该道具在背包中的数量
* 20171202  [添加] 脚本指令 equipinventory 穿戴指定背包位置的装备
* 20171202  [添加] 脚本指令 unequipinventory 脱下指定背包位置的装备
* 20171202  [添加] 脚本指令 viewequip 查看指定账号在线角色的装备信息
* 20171202  [添加] 脚本指令 setrenttime 增加/减少指定位置装备的租赁时间
* 20171202  [添加] 脚本指令 battleignore 将指定的角色设置为魔物无视状态
* 20171202  [添加] 脚本指令 sc_check 用于判断指定的状态(Buff)是否存在, 并取得状态参数
* 20171202  [添加] 脚本指令 bonus_script_remove 移除指定的 bonus_script 效果
* 20171202  [添加] 脚本指令 getchartitle 获得指定玩家的称号ID
* 20171202  [添加] 脚本指令 getequipidx 用来获取穿戴在指定位置的装备的“背包位置序号”.
* 20171202  [添加] 脚本指令 resetoptionbyidx 给定背包位置序号, 清空物品的随机属性
* 20171202  [添加] 脚本指令 resetoptionbypos 给定装备位置编号, 清空物品的随机属性
* 20171202  [添加] 脚本指令 getoptionbyidx 给定背包位置序号, 获得物品的随机属性
* 20171202  [添加] 脚本指令 getoptionbypos 给定装备位置编号, 获得物品的随机属性
* 20171202  [添加] 脚本指令 setoptionbyidx 给定背包位置序号, 配置物品的随机属性
* 20171202  [添加] 脚本指令 setoptionbypos 给定装备位置编号, 配置物品的随机属性
* 20171202  [添加] 脚本指令 duplicate 将一个指定的NPC复制到一个新的位置
* 20171202  [添加] 脚本指令 copynpc 将一个指定的NPC复制到一个新的位置
* 20171202  [添加] 脚本指令 unloadduplicate 卸载用脚本复制的NPC
* 20171202  [添加] 脚本指令 unloadcopynpc 卸载用脚本复制的NPC
* 20171202  [添加] 事件 OnPCGuildCreateFilter 玩家创建公会前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCPetSkillFilter 玩家宠物使用技能前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCGuildJoinFilter 玩家加入公会后触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCGuildLeaveFilter 玩家离开公会后触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCPetLootEvent 玩家宠物拾物品后触发
* 20171202  [添加] 事件 OnPCPetFeedEvent OnPCFoodPet 玩家给宠物喂食后触发
* 20171202  [添加] 事件 OnPCViewEquipFilter 玩家查看其他玩家装备后触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCUseSkillExFilter 玩家施放技能前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCUseSkillExEvent 玩家技能施放后触发
* 20171202  [添加] 事件 OnPCUseItemExFilter 玩家使用道具前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCUseItemExEvent 玩家使用道具后触发
* 20171202  [添加] 事件 OnPCWillLoadMapEvent 玩家进入地图或切换地图前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCInChatroomFilter 玩家进入聊天室前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCChangeTitleFilter 玩家改变称号前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCOpenRouletteFilter 玩家打开幸运转盘前触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCCloseRouletteEvent 玩家关闭幸运转盘后触发
* 20171202  [添加] 事件 OnPCStartRouletteFilter 玩家在转盘点击开始后触发, 可使用 processhalt 中断
* 20171202  [添加] 事件 OnPCGetRouletteEvent 玩家在转盘点击获取物品后触发
* 20171201  [添加] 事件 OnPCHomLvUpEvent 玩家的人工生命体升级后触发
* 20171201  [添加] 事件 OnPCHomCallEvent 玩家召唤出人工生命体后触发
* 20171201  [添加] 事件 OnPCHomRestEvent 玩家将人工生命体安息后触发
* 20171201  [添加] 事件 OnPCHomDeadEvent 玩家的人工生命体死亡后触发
* 20171201  [添加] 事件 OnPCHomAliveEvent 玩家复活人工生命体后触发, 可使用 processhalt 中断
* 20171201  [添加] 事件 OnPCIdentifyFilter 玩家成功鉴定装备前触发
* 20171201  [添加] 事件 OnPCIdentifyEvent 玩家成功鉴定装备后触发
* 20171201  [添加] 事件 OnBfReloadScriptEvent 刷新脚本前触发
* 20171201  [添加] 事件 OnAfReloadScriptEvent 刷新脚本结束时触发
* 20171201  [添加] 事件 OnPCKillMvpEvent 杀死MVP魔物时触发
* 20171201  [添加] 事件 OnPCEquipFilter 玩家准备穿戴物品后触发
* 20171201  [添加] 事件 OnPCEquipEvent 玩家穿戴物品后触发
* 20171201  [添加] 事件 OnPCUnequipFilter 玩家准备脱掉物品后触发
* 20171201  [添加] 事件 OnPCUnequipEvent 玩家成功脱掉物品后触发
* 20171201  [添加] 事件 OnPCBuffStartEvent 玩家获得状态(Buff)后触发
* 20171201  [添加] 事件 OnPCBuffEndEvent 玩家解除状态(Buff)后触发
* 20171201  [添加] 事件 OnPCPartyCreateFilter 当玩家创建队伍前触发, 可使用 processhalt 中断
* 20171201  [添加] 事件 OnPCPartyJoinFilter 当玩家加入队伍前触发, 可使用 processhalt 中断
* 20171201  [添加] 事件 OnPCPartyLeaveFilter 当玩家离开队伍前触发, 可使用 processhalt 中断
* 20171130  [添加] item_flag.txt支持物品不会由于被玩家主动使用而消耗(256), 物品不会由于被发动技能所需要而消耗(512)
* 20171130  [翻译] db数据库文件中文化
* 20171129  [翻译] conf配置文件中文化
* 20171129  [添加] 用于配置新加入的控制台输出文本 conf/msg_conf/BetterRa_map_msg.conf
* 20171128  [添加] 控制台翻译代码, 控制台翻译文件 conf\msg_conf\translation.conf
