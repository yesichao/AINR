linner_net  
--------------------------  
1. 0522  
描述： 通过线性折叠方式压缩网络，10.8G@1024*1024*4  
结果： 250fps  
2. 0525  
描述： 减少一层，第一层与最后一层的核size改为3  
结果： 438  
3. 0527  
描述： 去除1，3层add，relu改为prelu  