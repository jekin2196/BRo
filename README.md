# 简介
创建 BetterRa创建于2017年11月28日..他是在Rathena的基础上经过二次修改的一款模拟器, 加入了大量的功能..

# 更新日志

* 20180102  [添加] 战斗配置 enable_coply 当其他职业拥有流氓的抄袭技能时, 是否可以复制技能
* 20180102  [修复] 当背包大于128时, 商城不能购买的问题.
* 20180102  [添加] 脚本指令 getidxrandomoption 用来获取玩家背包中物品的OPT
* 20180102  [添加] 脚本指令 setidxrandomoption 用来设置玩家背包中物品的OPT
* 20180102  [添加] 属性拓展 bWeaponAddDamage 增加武器攻击伤害
* 20180102  [添加] 属性拓展 bMagicAddDamage 增加魔法攻击伤害
* 20180102  [添加] 属性拓展 bMiscAddDamage 增加特殊攻击伤害
* 20180102  [添加] 脚本指令 is_bot 用来判断指定玩家是否为机器人
* 20180102  [添加] 脚本指令 bot_run 启动机器人, 配置方法请查看 doc/BetterRa_script_commands.txt
* 20180102  [添加] 脚本指令 bot_reset 用来重新配置机器人参数, 配置方法请查看 doc/BetterRa_script_commands.txt
* 20171228  [添加] 护身符道具 类型为20, 需要在 conf/battle/BetterRa.conf 启用护符
* 20171228  [添加] 机器人系统
* 20171222  [修改] 提取 packet_keys 配置服务端封包混淆KEY的设置提取到 conf/map_athena.conf
* 20171222  [添加] 地图标记 nopet 禁止玩家在此地图上使用宠物, 登陆到此地图宠物会自动变蛋回到玩家背包.
* 20171222  [添加] 地图标记 nohomunculus 禁止玩家在此地图上使用生命体, 登陆到此地图生命体会被自动安息.
* 20171222  [添加] 地图标记 nomercenary 禁止玩家在此地图上使用佣兵, 登陆到此地图佣兵会被自动解散.
* 20171222  [修改] 宠物脚本 pet_skill_attack 的伤害太小的问题
* 20171222  [修改] 指令名称 hasfollow -> getservantgid 用来获取玩家有没有 宠物、佣兵、生命体、元素体等
* 20171222  [添加] 脚本指令 tribe_mob_spawn 用于召唤指定阵营下的魔物
* 20171214  [添加] 战斗配置 buff_for_guild_member 在GVG模式下 群体辅助技能 是否对所有公会成员有效
* 20171214  [添加] 战斗配置 buff_for_tribe_member 在阵营模式下 群体辅助技能是否对同阵营成员（玩家、魔物）有效
* 20171214  [添加] 脚本指令 tribe_getteam 获取玩家的阵营ID
* 20171214  [添加] 脚本指令 tribe_setteam 将玩家添加至某个阵营
* 20171214  [添加] 脚本指令 tribe_mobteam 将上次召唤的魔物全部添加至某个阵营
* 20171212  [添加] 路点系统 使用 setsteppath 为魔物设置路点
* 20171212  [添加] 阵营系统 在 mapflag 被设为 tribe 时生效
* 20171209  [添加] 脚本指令 setsteppath 用于设置MOB的行走路径, 配置以后魔物会自动行走
* 20171209  [添加] policies.conf 文件
* 20171209  [添加] 脚本配置文档 npc/script_BetterRa.conf
* 20171209  [添加] demo文件 npc/BetterRa/BetterRa_event_demo.txt
* 20171209  [添加] GM指令 policy 用于设置指定玩家的行为策略编号
* 20171209  [添加] GM指令 title 用于更改称号
* 20171209  [添加] policies 行为策略，用于动态修改 经验 掉率 GM等级等
* 20171209  [添加] setpolicyid 设置指定玩家的行为策略编号, 配合 conf/policies.conf 中定义的规则使用
* 20171209  [添加] getpolicyid 获取指定玩家的行为策略编号, 配合 conf/policies.conf 中定义的规则使用
* 20171209  [添加] getpolicyinfo 获得指定玩家当前的行为策略详情, 配合 conf/policies.conf 中定义的规则使用
* 20171208  [添加] 脚本指令 mail_create mail_additem* mail_send 发送邮件支持
* 20171208  [添加] BD配置文档 item_announce.txt 根据物品掉率来判定是否需要进行公告
* 20171208  [修复] 登陆时, 显示"不知名区域"的BUG
* 20171207  [修复] getitem3 delitem3 等指令不能使用玩家关联的变量的问题
* 20171207  [添加] GM指令 recallmap 将地图上的玩家瞬移至身旁
* 20171207  [添加] 脚本指令 hasfollower 用来获取玩家有没有 宠物、佣兵、生命体、元素体等
* 20171206  [添加] 脚本指令 unitremove 可以通过GID移除实体, 并播放指定的消失动画
* 20171205  [修复] 事件队列问题带来的一系列问题
* 20171205  [修复] callshop 后玩家可以随意移动的问题
* 20171205  [添加] 战斗配置 combo_mode 用于配置 item_combo 效果生效策略
* 20171204  [汉化] 生命体DB中的名称
* 20171204  [添加] 地图标记 hideguildinfo 隐藏公会信息
* 20171204  [添加] 地图标记 hidepartyinfo 隐藏组队信息
* 20171204  [添加] 地图标记 notoken 不能使用复活之证
* 20171204  [添加] 地图标记 nocapture 不能捉宠物
* 20171204  [添加] 地图标记 noautoloot 不能使用自动拾取
* 20171204  [添加] BetterRa 战斗配置文件 conf/battle/BetterRa.conf
* 20171204  [添加] 战斗配置 max_pvp_aspd 玩家在PVP地图时的最大攻速限制
* 20171204  [添加] 战斗配置 max_gvg_aspd 玩家在GVG地图时的最大攻速限制
* 20171204  [添加] 战斗配置 extremityfist_castend_ball_check 阿修罗霸凰拳咏唱完毕时, 是否再次确认气弹数量
* 20171204  [添加] 战斗配置 extremityfist_castend_status_check 阿修罗霸凰拳咏唱完毕时, 是否再次确认“爆气”状态
* 20171204  [添加] 战斗配置 extremityfist_nocast_sp 使用“阿修罗霸凰拳”不会直接耗尽玩家的SP
* 20171204  [添加] 战斗配置 loadevent_for_eachmap 强制所有地图触发 OnPCLoadMapEvent 事件
* 20171204  [添加] 战斗配置 get_identify_equip 通过特定渠道获得的装备, 强制变成已鉴定
* 20171204  [添加] 战斗配置 mounting_cant_use 当玩家乘坐商城坐骑后, 是否禁止使用物品
* 20171204  [添加] 战斗配置 hide_cmd 当没有权限的玩家执行了GM指令是否隐藏并返回一条信息
* 20171204  [添加] 战斗配置 bAspd_fixed 使用 bonus bAspd,x; 进行攻速加成时, x 值是否会受到其他加成因素影响
* 20171204  [添加] 战斗配置 share_quests_area 在什么位置才能共享任务的杀怪进度
* 20171204  [修改] 战斗配置 show_mob_info 添加 级别/编号/体型/种族/属性和属性等级
* 20171204  [添加] 脚本指令 identifybyidx 根据指定的背包序号, 对该道具进行鉴定操作
* 20171204  [添加] 脚本指令 setrenttime(resume) 增加/减少指定位置装备的租赁时间
* 20171204  [添加] 脚本指令 script4each 对指定范围的玩家执行相同的一段脚本
* 20171204  [添加] 脚本指令 itemexists(existitem) 确认服务器的 item_db 中是否存在指定物品
* 20171204  [添加] 脚本指令 getequipexpiretick(isrental) 获得指定位置装备的租赁到期剩余秒数.
* 20171204  [添加] 脚本指令 gethotkey(get_hotkey) 获取指定快捷键位置的信息
* 20171204  [添加] 脚本指令 sethotkey(set_hotkey) 设置玩家快捷键上的内容
* 20171204  [添加] 脚本指令 statuscalc(status_calc) 为了兼容一些脚本
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
* 20171130  [汉化] db数据库文件中文化
* 20171129  [汉化] conf配置文件中文化
* 20171129  [添加] 用于配置新加入的控制台输出文本 conf/msg_conf/BetterRa_map_msg.conf
* 20171128  [添加] 控制台翻译代码, 控制台翻译文件 conf\msg_conf\translation.conf
