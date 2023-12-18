# I AM EVE

## 本库已启用权限验证，仅限群内用户或非代挂使用！
### [频道](https://t.me/Wall_E_Channel)
### CREATED BY [iMeagic](https://t.me/iMeagic)

### 变更日志
#### 2023-12-18

| 类型  | 说明                 | 变量 | 参数       | 默认值   | 作者                              |
|-----|--------------------|--|----------|-------|---------------------------------|
| 新增  | 支持代理池，携带密码访问       |  |          |       | [无名](https://t.me/iMeagic)      |
| 新增  | 支持自定义超时退出开关        | M_TIMEOUT_QUIT | 配置true生效 | false | [无名](https://t.me/iMeagic)      |

#### 2023-12-07

| 类型  | 说明                   | 变量 | 参数    | 默认值 | 作者                             |
|-----|----------------------|--|-------|-----|--------------------------------|
| 新增  | 移除代理缓存机制             |  |   M_WX_PROXY_TIMEOUT    |  | [iMeagic](https://t.me/iMeagic) |
| 新增  | 引入超时退出机制，解决发通知后卡本子问题 |  |  |  | [无名](https://t.me/iMeagic)     |
| BUG | 修复抽奖gzsl域名未关注死循环问题   |  |  |  | [iMeagic](https://t.me/iMeagic)    |
| BUG | 处理加购未满足条件跳出循环        |  |  |  | [iMeagic](https://t.me/iMeagic)  |
#### 2023-11-13

| 类型  | 说明         | 变量                                                                                                                                                                                      | 参数    | 默认值 | 作者                              |
|-----|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|-----|---------------------------------|
| 新增  | 多代理api支持   | 1. M_WX_PROXY_URL=必须参数<br>2.M_WX_PROXY_CLOSE=非必需，默认 启用 0关闭<br>3. M_WX_PROXY_TIMEOUT=非必需参数 默认缓存30秒<br>4. M_WX_PROXY_URL1<br>5. M_WX_PROXY_CLOSE2<br>6. M_WX_PROXY_TIMEOUT3<br>…. …. 以此类推 |       |  | [ccwav](https://t.me/BattenWei)   |
| 新增  | 扩展ck支持     | 脚本执行目录下新增ck文件夹，读取.txt结尾的文件，文件内每行一个ck。                                                                                                                                                   |  |  | [ccwav](https://t.me/BattenWei)   |
| BUG | 关注有礼不走代理   |                                                                                                                                                                                         |       |  | [iMeagic](https://t.me/iMeagic) |
| BUG | sign获取不走代理 |                                                                                                                                                                                         |       |  | [iMeagic](https://t.me/iMeagic) |

#### 2023-11-09

| 类型 | 说明         | 变量         | 参数           | 默认值 | 作者                              |
|----|------------|------------|--------------|-----|---------------------------------|
| 新增 | 对非代挂用户不再鉴权 |     |  |  | [iMeagic](https://t.me/iMeagic)  |
| BUG | 修复10043活动  |     |  |  | [寒寒づ♡ど](https://t.me/djun97)  |

#### 2023-11-06

| 类型  | 说明                         | 变量         | 参数           | 默认值 | 作者                              |
|-----|----------------------------|------------|--------------|-----|---------------------------------|
| BUG  | 支持不初始化initPintoken方法基于正则判断 |     |  |  | [Doraemon_o](https://t.me/Doraemon_o)  |
#### 2023-10-31

| 类型  | 说明                    | 变量         | 参数           | 默认值 | 作者                              |
|-----|-----------------------|------------|--------------|-----|---------------------------------|
| BUG  | 修复等级不足                 |     |  |  | [寒寒づ♡ど](https://t.me/djun97) |

| 类型  | 说明                    | 变量         | 参数           | 默认值 | 作者                              |
|-----|-----------------------|------------|--------------|-----|---------------------------------|
| 新增  | 不限量填地址                | 详见脚本54-64行 | 默认随机模式       |   RANDOM  | [iMeagic](https://t.me/iMeagic) |
| 新增  | 大牌只关注加购抽奖             |    M_WX_OPENCARD_OPEN        | 设置为off及可关闭开卡 | on  | [iMeagic](https://t.me/iMeagic) |
| 新增  | isvObfuscator 403使用代理 |            |  |   | [iMeagic](https://t.me/iMeagic) |
#### 2023-09-13

| 类型 | 说明     | 变量   | 参数                 | 默认值 | 作者                              |
|----|--------|------|--------------------|-----|---------------------------------|
| 新增 | 新增9个   | 详见脚本 | 参考解析文件             |  | [iMeagic](https://t.me/iMeagic) |
| 删除 | 移除过期脚本 |  |              |  | [iMeagic](https://t.me/iMeagic) |
#### 2023-09-05

| 类型  | 说明             | 变量                   | 参数                 | 默认值 | 作者                              |
|-----|----------------|----------------------|--------------------|-----|---------------------------------|
| 新增  | M投票抽奖          |  M_WX_VOTE_DRAW_URL   | 参考解析文件             |  | [寒寒づ♡ど](https://t.me/djun97) |
| 新增  | M无线游戏          |  M_WX_GAME_URL   | 参考解析文件 |  | [寒寒づ♡ど](https://t.me/djun97) |
| 新增  | M老虎机抽奖          | M_WX_CENTER_DRAW_URL   | 参考解析文件 |  | [iMeagic](https://t.me/iMeagic)|
| BUG | 修复100系列活动      |     |                    |  | [iMeagic](https://t.me/iMeagic) |
| 新增 | M活动检测,无豆和实物不通知 |   M_WX_CHECK_ACT_URL  |                    |  | [iMeagic](https://t.me/iMeagic) |
#### 2023-08-30

| 类型 | 说明                             | 变量                   | 参数                                   | 默认值 | 作者                              |
|----|--------------------------------|----------------------|--------------------------------------|-----|---------------------------------|
| 新增 | 非邀请类默认车头数配置 |  M_WX_LEADER_NUM   |  | 999 | [Doraemon_o](https://t.me/Doraemon_o) |
#### 2023-08-22

| 类型 | 说明                             | 变量                   | 参数                                   | 默认值                     | 作者                              |
|----|--------------------------------|----------------------|--------------------------------------|-------------------------|---------------------------------|
| 新增 | M通用开卡支持大牌                      |     |  |                         | [iMeagic](https://t.me/iMeagic) |
| 新增 | 支持jingyun-rc.isvjcloud.com域名活动 |     |  |                         | [Doraemon_o](https://t.me/Doraemon_o) |
#### 2023-08-17

| 类型 | 说明         | 变量                   | 参数                                   | 默认值                     | 作者                              |
|----|------------|----------------------|--------------------------------------|-------------------------|---------------------------------|
| 新增 | M京东签到 |     |  |                         | [iMeagic](https://t.me/iMeagic) |
#### 2023-08-16

| 类型  | 说明         | 变量                   | 参数                                   | 默认值                     | 作者                              |
|-----|------------|----------------------|--------------------------------------|-------------------------|---------------------------------|
| BUG | M关注抽奖未取关问题 |     |  |                         | [iMeagic](https://t.me/iMeagic) |

#### 2023-08-15

| 类型  | 说明              | 变量 | 参数                                   | 默认值                     | 作者                              |
|-----|-----------------|---|--------------------------------------|-------------------------|---------------------------------|
| 新增  | M银行卡支付有礼           |   |  |                         | [iMeagic](https://t.me/iMeagic) |
| 新增  | M无线关注           |  M_WX_SHOP_GIFT_URL |详见脚本  |                         | [iMeagic](https://t.me/iMeagic) |

#### 2023-08-14

| 类型  | 说明              | 变量                   | 参数                                   | 默认值                     | 作者                              |
|-----|-----------------|----------------------|--------------------------------------|-------------------------|---------------------------------|
| BUG | 修复开卡allStatus异常 |     |  |                         | [iMeagic](https://t.me/iMeagic) |
| 新增  | M关注抽奖           | M_WX_FOLLOW_DRAW_URL    |  |                         | [iMeagic](https://t.me/iMeagic) |

#### 2023-08-11

| 类型  | 说明      | 变量                   | 参数                                   | 默认值                     | 作者                              |
|-----|---------|----------------------|--------------------------------------|-------------------------|---------------------------------|
| BUG | 修正组队车头数 |     |  |                         | [iMeagic](https://t.me/iMeagic) |

#### 2023-08-10

| 类型 | 说明            | 变量                   | 参数                                   | 默认值                     | 作者                                    |
|----|---------------|----------------------|--------------------------------------|-------------------------|---------------------------------------|
| 新增  | 自定义正则屏蔽ck     | M_WX_BLOCK_PIN_REGX    | 格式：regx1@pin1\|pin2;regx2@pin1\|pin2 |                         | [Doraemon_o](https://t.me/Doraemon_o) |
| 新增  | 100xx活动强制开卡变量 | M_WX_OPEN_CARD_TYPES | 多个类型用`@,&\|`任一符号分割                   | 10033,10043,10052,10068 |
| 新增  | 黑号提示AUTHBLACK | -                    | -                                    |

#### 2023-08-04

| 类型 | 说明         | 变量                                            | 参数                   | 默认值 |
|----|------------|-----------------------------------------------|----------------------|-----|
| 新增  | 支持开启代理配置   | M_WX_PROXY_ENABLE                             | 1:关闭 2:开启            | 2   |
| 新增  | 支持开启重拨消息   | M_RE_ROUTER_ENABLE                            | 1关闭 2开启              | 2   |
| 新增  | 支持自定义重拨消息体 | M_RE_ROUTER_MSG                               | -                    | 重拨  |
| 新增  | M关注有礼      | M_FOLLOW_SHOP_ARGV                            | 详见脚本                 |     |
| 新增  | M店铺刮奖      | M_GYG_SHOP_ARGV                               | 详见脚本                 |     |
| 新增  | M入会有礼      | 1. M_OPEN_CARD_ARGV <br/>2. M_OPEN_CARD_FORCE | 1.详见脚本<br/>2.强制开卡配置,1关闭 2开启 | 1   |
