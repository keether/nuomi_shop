仿糯米网 v0.8
1.添加用户模块所有输入数据的验证
2.编辑用户可以不修改密码
	1.密码和确认密码框都没有值时 自动识别无需修改密码
	2.只要有一个有值得时候 自动识别为修改密码状态（此时确认密码和密码框的值必须一样）
3.编辑用户可以不修改头像
	1.无上次头像时自动使用默认图像充当头像
	2.如果已经上传头像，则讲上传的图像设为用户头像
4.无法删除炒鸡鹳狸猿
5.用户被禁用后不得登陆
6.分类部分BUG修复
7.添加商品模块所有输入数据的验证
	1.编辑商品时自动从数据库中读取默认值并打印
	2.编辑状态下可以不上传商品图像，不上传则默认用添加商品时已经上传的头像
	3.点击详情之后跳转到商品详情页
8.订单管理模块除了之前的退款功能还增加了在【交易完成】后的评论模块（交易关闭状态下无法评论）
9.登陆注册模块上的权限验证，可以非鹳狸猿不得进入后台，但可以进入个人中心，未登录的用户不得进入个人中心但可以使用购物车功能。
注册成功后免登陆。

商城前台：
1.可以按最热（浏览量最高），价格（从低到高），最新发布（最新添加） 最商品进行排序
2.样式美化，达到最大的还原度（自认为挺好看了）
3.增加本周精选模块 最多显示两个 可来回切换
4.进入商品详情页自增浏览量功能