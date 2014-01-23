REST == CURD == URI
________________________________________________________________________________________________
```
GET       Read                        /GET /resource/<id>

POST      *Create<collection>         /GET /resource            --  /POST /resource
          Create<non_id>              /GET /resource/new        --  /POST /resource/new
          Update<has_id>              /GET /resource/<id>/edit  --  /POST /resource/<id>/edit
          Delete                      /GET /resource/<id>/del   --  /POST /resource/<id>/del

PUT       Create<non_id>              /GET /resource            --  /PUT /resource
          Update<has_id>              /GET /resource/<id>/edit  --  /PUT /resource/<id>/edit

DELETE    Delete                      /GET /resource<id>/del    --  /DELETE /resource/<id>/del

HEAD      --                          /HEAD /resource/<id>
```
> resource指资源实体、或资源集合

> 给每个资源取唯一的名字，有唯一的一个匹配模板

> 根据seo等实际要求，资源名应该是稳定的，不会删除/修改，除非产品下线

> 根据资源名，模板，模板参数，可以唯一生成url

短横线还是下划线，-、_
________________________________________________________________________________________________

> 短横线表示连词

> 下划线标识空格/分词
