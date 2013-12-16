REST == CURD
________________________________________________________________________________________________
```
GET       Read                        /GET /resource/<id>

POST      Create<non_id>              /GET /resource            --  /POST /resource
          Update<has_id>              /GET /resource/<id>/edit  --  /POST /resource/<id>/edit
          Delete                      /GET /resource/<id>/del   --  /POST /resource/<id>/del

PUT       Create<non_id>              /GET /resource            --  /PUT /resource
          Update<has_id>              /GET /resource/<id>/edit  --  /PUT /resource/<id>/edit

DELETE    Delete                      /GET /resource<id>/del    --  /DELETE /resource/<id>/del

HEAD      --                          /HEAD /resource/<id>
```
> resource指资源实体、或资源集合
