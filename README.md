# ngx_cache_file
nginx+lua实现本地缓存

```nginx
http {
    ...
    lua_shared_dict my_cache 256m;
    ...
}
```

