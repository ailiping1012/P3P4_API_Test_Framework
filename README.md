20201115:
1、项目初始化配置  == 放到github上去
2、数据源处理：
2.1、config读取的封装
2.2、excel存放测试数据转换到代码中的处理
合并单元格 == 》 封装excel_utils == 》把excel数据转换成测试用例业务数据
（setdefault() 为了把用例步骤整合到对应的测试编号中）==》封装testcase_data_utils
==》形态变化：
{[],[]} == {"":[],"":[]} == [{"case_id":'','case_step':[]},...]
