# 信贷需求预测
## 问题描述
信贷需求预测目的在于利用以往用户的行为信息预测在未来一段时间内用户的贷款数目，帮助放贷公司对预备金进行调控。本实验的用户数据包括客户基本信息（客户信息表）、在移动端的行为数据（点击信息表）、购物记录（订单信息表）和历史借贷信息（贷款信息表）。具体包括5个csv文件表，其具体信息如下：

| 文件名 | 字段名 | 字段描述 |
|:------:|:------:|:------:|
|  t_user.csv | uid | 用户ID |
|            | age | 年龄 |
|            | sex | 性别 |
|            | active_date | 客户激活日期 |
|            | limit | 初始额度 |
|t_order.csv|	uid|	客户ID|
||	buy_time |	购买时间|
||	price|	价格|
||	qty|	数量|
||	cate_id|	品类ID|
||	discount|	优惠金额|
|t_click.csv|	uid|	客户ID|
||	click_time	|点击时间|
||	pid	|点击页面|
||	param	|页面参数|
|t_loan.csv|uid|客户ID|
||	loan_time|	借款时间|
||	loan_amount|	借款金额|
||	plannum|	分期期数|




