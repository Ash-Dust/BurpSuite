Login vào trang chọn Lightweight "l33t" Leather Jacket có giá hơn 1k$
![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/ba0012c5-abe0-4351-84d9-a5d2953f3136)

Sau đó bật Intercept lên để kiểm tra request và click Add to cart.
![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/2f67a349-ab90-4986-a3fd-ce73da0883a3)

Để ý thấy request có gửi kèm theo price và do đó ta có thể thử chỉnh sửa ở phía client-side.
Chỉnh sửa giá tiền thành 1 sau đó tắt Intercept đi để gửi request lên server

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/c4b1bea0-7c9c-4868-b5ca-0ef3b4b9f3fb)

Sau đó click vào giỏ hàng, ta có thể thấy giá tiền đã được điều chỉ còn 0.01$. 

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/164bfeaa-47df-44b8-8ec9-dc167a2a8b17)

Và sau khi click Place order thì.. voidla Đến đây thì mình sẽ có thể mua đồ 1337$ với giá 0.01$ :D
