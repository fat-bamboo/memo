# Insmemo roadmap

## Versions

### v0.0.1

- Memo 模块：
  - 增加、删除、修改、查；
  - localStorage 存储；
  <!-- - 补充随笔； -->
- Account 模块 (Done)：
  - 登录；
  - 注销；

## TODO

- [ ] 数据本地存储逻辑；
- [ ] 补充 memo；
- [ ] memo 标签；
- [ ] 移动端样式适配；

## Daily Plan

### 2021/4/9

- [x] 数据本地存储逻辑；
- [ ] 完善文案，发版 v0.0.1;

### 2021/4/8

- [x] 账号模块；
      api:
  - /api/user/me check sign in status
  - /api/user/signin sign in
  - /api/user/signup sign up
  - /api/user/signout sign out
- [x] memo 模块
      api:
  - get /api/memo/all?page=0&
  - post /api/memo/new new memo
  - post /api/memo/delete delete memo
  - post /api/memo/update update
- [ ] memo 本地存储
      未登录时，自动本地存储；登录后，将其转为线上

### 2021/4/6

- [x] 后台项目初始化；
- [ ] 账号模块；

### 2021/4/5

- [x] memo item 增加操作按钮：删除；
- [ ] 后台项目初始化；
- [ ] 优化 editor 根据内容自动增高；