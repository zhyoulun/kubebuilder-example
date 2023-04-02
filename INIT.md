https://juejin.cn/post/6943182462813995044

```
kubebuilder init --domain my.domain
```

```
kubebuilder create api --group example --version v1 --kind Guestbook
```

```
api/v1 -> api/example/v1
```

```
make update-codegen
```

问题：zz_generated.deepcopy.go会被改掉，需要改回来。。原因待确定