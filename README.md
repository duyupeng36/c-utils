# c-utils

C 语言工具库：动态数组（`vec`）+ 字符串库，带单元测试与双构建系统（Makefile + CMake）。

> 学习计划 M1 交付物（见 [backend](https://github.com/duyupeng36/backend) 仓库 2.5 年学习计划）。

## 计划 API

- `vec`：`vec_new / vec_push / vec_get / vec_set / vec_remove / vec_sort / vec_free`
- 字符串：`my_strlen / my_strcpy / my_strcmp / my_strstr`

## 构建

```bash
# Makefile
make && make test

# CMake
cmake -B build && cmake --build build && ctest --test-dir build
```

## 验收标准（v1.0）

- [ ] API 完整，测试全绿
- [ ] valgrind 零报告
- [ ] Makefile 与 CMake 双构建通过
- [ ] v1.0 tag
