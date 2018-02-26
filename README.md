# 教务管理+在线考试系统

# 项目采用 React + React Router 4.0 + Redux + Ant Design

# 开发环境使用Webpack搭建

### 功能模块

- 登录

- 主页面
    - 左边菜单
    - 顶部导航
    - 快速进入版块

- 试题录入（根据后台数据自动生成选项）
    - java
      - 初级
        - 单选题、多选题、填空题、判断题、简答题、程序题
      - 中级
      - 高级
    - 前端
      - 初级
      - 中级
      - 高级

- 出卷 （教师出卷）

- 成绩查询（查询学生成绩）

- 学生信息管理
    - 添加学生
    - 删除学生
    - 修改学生
    - 查询学生

- 教师信息管理（超级管理员权限）
    - 添加教师
    - 删除教师
    - 修改教师
    - 查询教师

- 班级信息管理
    - 添加班级
    - 删除班级
    - 修改班级
    - 查询班级

- 考试管理
    - 创建考试
    - 在线阅卷（选择、判断机器阅卷，填空、简答、程序人工阅卷，教师需要管理员授予权限才能阅卷）
      - 所有班级的试卷
        - 某班级所有学生的试卷
          - 某个学生的试卷（开始评分）

- 个人中心
    - 修改密码

### 角色管理
- 教学老师（试题录入、出卷、成绩查询、学生管理、班级管理、考试）
- 教务老师（试题录入、出卷、成绩查询、学生管理、班级管理、考试）
- 超级管理员（教师一般权限，教师管理权限，授予教师阅卷权限）
