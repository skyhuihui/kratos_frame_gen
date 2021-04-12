# kratos_frame_gen
根据数据库表对应的model，生成依赖于kratos_frame框架结构的service及controller代码
https://github.com/skyhuihui/kratos_frame

# 使用
使用替换模板中的应用的包的路径。能找到对应的结构和包即可
* params_tmpl中的 kratos_frame_gen/model
* server_tmpl中的
* service_tmpl中的

执行此方法生成mvc结构：Gen
编写params中的增删改查参数信息，以及添加json，note两个tag。
执行生成的params文件夹中的gen_md文件生成可用于postman中的markdown说明
