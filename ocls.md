The manager can use xss in the place where the product name is set in the background

Use the default account password "admin/admin&123" to log in url 'http://localhost:3456/php-ocls/admin/?page=product/manage_product&id=2'

Set the product name as follows

![image-20230404190741131](https://typero-1312563978.cos.ap-shanghai.myqcloud.com/typero/202304041909114.png)

then click save

![image-20230404191028588](https://typero-1312563978.cos.ap-shanghai.myqcloud.com/typero/202304041910663.png)

Visiting the homepage will trigger xss

![image-20230404191148365](https://typero-1312563978.cos.ap-shanghai.myqcloud.com/typero/202304041911436.png)

![image-20230404191120461](https://typero-1312563978.cos.ap-shanghai.myqcloud.com/typero/202304041926508.png)