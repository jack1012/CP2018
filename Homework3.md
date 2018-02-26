Matlab畫圖，繳交兩個.m檔案，及一個word檔案，要有圖片(可以存成jpg檔)。

作業1：f(n)=1+1/2+1/3+...+1/n，g(x)=ln(x)，使用plot指令畫出兩條函數曲線。

條件：
(1) f函數曲線為紅色，虛線，g函數曲線為藍色，實線。
(2) 標題：1+1/2+1/3+...+1/n V.S. ln(n) 
(3) x軸設定標籤為 n

補充：
f(n)的數值計計算程式碼：

k=10^4;
x=1:1:k;
y=1./x;
for ii=1:k
    f(ii)=sum(y(1:ii)) ;   
end


作業2：f(n)=1+1/2^2+1/3^2+...+1/n^2，g(x)=(pi^2)/6，使用plot指令畫出兩條函數曲線。

條件：
(1) f函數曲線為紅色，虛線，g函數曲線為藍色，實線。
(2) 標題：1+1/2^2+1/3^2+...+1/n^2 V.S. (pi^2)/6
(3) x軸設定標籤為 n