gmall_learning

common :全局类，常量都放在里面

service:和dao层对接，为controller层提供服务

dao:在最下面和db交互,是一个接口供service调用

vo：pojo通过vo进行封装，返回给controller

pojo:是和数据库一一对应的一个对象

util:工具类都放在里面

mybatis-generator：根据数据库自动生成pojo和dao以及对应的xml