# 需求

## 后台系统
        ​	菜品管理（批量删除、起售停售）
        ​	套餐管理（修改、起售停售）
        ​	订单明细

## 移动端
        ​	个人中心（退出登录、最新订单查询、历史订单、地址管理-修改地址、地址管理-删除地址）
        ​	购物车（删除购物车中的商品)
***

# 技术选型
        ​	1. 用户层：H5、VUE、ElementUI、微信小程序
        ​	2. 网关层：Nginx
        ​	3. 应用层：SpringBoot、SpringMVC、SpringSession、Spring、Swahher、lombox
        ​	4. 数据层：Mysql、Mybatis、MybatisPlus、redis
        ​	5. 工  具：git、maven、junit
***

# 数据库说明
| 序号 | 表名           | 说明      |
|:--:|:-------------|:--------|
| 1  | employee     | 员工      |
| 2  | category     | 菜品和套餐分类 |
| 3  | dish         | 菜品      |
| 4  | setmeal      | 套餐      |
| 5  | setmeal_dish | 套餐和菜品关系 |
| 6  | dish_flavor  | 菜品口味关系  |
| 7  | user         | 用户表（C端） |
| 8  | address_book     | 地址      |
| 9  | shopping_cart     | 购物车     |
| 10 | orders     | 订单      |
| 11 | order_detail     | 订单明细表   |
***

