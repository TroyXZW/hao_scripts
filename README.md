# jd_scripts
自用


特征|类型|注释|解释
---|:--:|:---|
uid| int||
is_noactive| int|是否为15天内活跃用户|标签
create_days| int|注册了多久|
long_city_id| int|用户常驻城市id|
last_city_id| int|用户末次城市id|
xy_money| bigint|用户当前氧分|
focus_cnt| int|关注用户数|
fans_cnt| int|粉丝数|
sign_cnt| int|签到数|
task_cnt| int|完成任务数|
second_order_cnt| bigint|用户复购次数|
cancel_order_cnt| bigint|取消订单数|
cash_back_cnt| bigint|退款订单数|
pay_gmv| bigint|用户支付gmv|
pay_order_cnt| bigint|用户支付订单数|
pct_seven_days| bigint|最近七天访问深度|
avgpv_seven_days| bigint|最近七天平均pv数|
pct_fourteen_days| bigint|最近14天访问深度|
avgpv_fourteen_days| bigint|最近14天平均pv数|
pct_one_months| bigint|最近一个月访问深度|
avgpv_one_months| bigint|最近一个月平均pv数|
pct_six_months| bigint|最近六个月访问深度|
avgpv_six_months| bigint|最近六个月平均pv数|
avgpst_seven_days| bigint|用户近七天平均停留时长(s)|
avgpst_one_months| bigint|用户近一个月平均停留时长(s)|
product_cnt| bigint|用户当前购物车产品种类数量|
calendar_group_cnt| int|有效日记本数|
post_cnt| int|帖子数|
short_comment_cnt| int|短评数|
answer_cnt| int|用户问题回答数|
like_cnt| int|点赞数总和（日记、日历、帖子）|
belike_cnt| int|被赞数总和(日记、日历、帖子)|
answer_belike_cnt| int|有用数 问答被赞数的总和|
question_cnt| int|用户发表问题数|
group_click_cnt| int|群发push点击阅读数|
topic_post_cnt| int|用户话题发帖数|
clock_post_cnt| int|用户打卡发帖数|
msg_cnt| int|用户发送私信数|
msg_7days_cnt| bigint|近7天私信数|
tiezi_cnt| bigint|发帖数(图文帖+视频帖)|
follow_doctor_cnt| bigint|用户关注医生数|
follow_hospital_cnt| bigint|用户关注机构数|
follow_user_cnt| int|用户关注用户数|
order_consume| double|消费潜力-订单|
sc_consume| double|消费潜力-购物车|
sx_consume| double|消费潜力-私信|
search_consume| double|消费潜力-搜索|
click_consume| double|消费潜力-点击|
predict_consume| double|预测消费潜力|
visit_7days| bigint|最近7天访问天数|
visit_14days| bigint|最近14天访问天数|
visit_30days| bigint|最近30天访问天数|
pv_7days| bigint|最近七天的pv数|
comment_cnt| bigint|一级+二级评论数|
place_order_cnt| bigint|用户下单数|
accumulate| bigint|用户累积活跃天数|
user_behavior_value| int|用户行为价值-行为等级|
cheat_score| bigint|用户作弊分|
since_last_awake_days| int|末次唤醒app时间距今时间（天）|
since_last_pay_order_days| int|末次支付订单时间距今时间（天）|
since_last_punchcard_days| int|末次打卡时间距今时间（天）|
since_last_post_days| int|末次发帖时间距今时间（天）|
device_id| bigint||
gender| int||
age| tinyint||
account_total_amount| double|账号总金额|
experience| int|用户当前经验值|
vip_status| int|vip状态 1：非黑卡 2、历史办过黑卡现在不是 3、当前为黑卡|
level| int|用户等级|
is_visitor| int|是否游客,1:游客，没有注册的用户 ，0:非|
search_click_sum7| bigint|最近七天搜索结果页超级列表-feed区-点击|
rec_click_sum7| bigint|最近七天首页feed流点击数|
add_cart7| bigint|最近七天加入购物车点击数|
stay_time_sum14| bigint|最近14天页面停留时间|
diary_hd_sum14| bigint|最近14天日记互动数|

