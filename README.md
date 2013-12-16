REST == CURD
________________________________________________________________________________________________

GET       Read                              /GET /archive/<id>

POST      Create<non_id>                    /GET /archive            --  /POST /archive
          Update<has_id>                    /GET /archive/<id>/edit  --  /POST /archive/<id>/edit
          Delete                            /GET /archive/<id>/del   --  /POST /archive/<id>/del

PUT       Create<non_id>                    /GET /archive            --  /PUT /archive
          Update<has_id>                    /GET /archive/<id>/edit  --  /PUT /archive/<id>/edit

DELETE    Delete                            /GET /archive<id>/del    --  /DELETE /archive/<id>/del

HEAD      --                                /HEAD /archive/<id>
