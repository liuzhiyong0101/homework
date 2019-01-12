设$$overline{X}$$表示X的各个位置取反，设M(x)表示X的补码，<br/>
若X的某位为0，则$$overline{X}$$对应位置为1，反之亦然。<br/>
因此：X+$$overline{X}$$=$$underbrace{ 11\cdots 1}_{n}$$=$$2^n$$-1<br/>
X+$$overline{X}$$+1=$$2^n$$<br/>
X+M(x)=$$2^n$$<br/>
所以M(x)=$$overline{X}$$+1<br/>
即二进制的负数X等于X每位取反加一<br/>




证明：<br/>
设一二进制数X=X<sub>1</sub>X<sub>2</sub>......X<sub>n</sub><br/>
由负数表示法可得：<br/>
Negative(X)=2<sup>k</sup>-I<br/>
Negative(X)=(2<sup>k</sup>-1)-I+1<br/>
Negative(X)=(2<sup>k-1</sup>+2<sup>k-2</sup>+......+2+1)-X+1<br/>
2<sup>k-1</sup>+2<sup>k-2</sup>+......+2+1转换为二进制即为111......111(n个1)<br/>
故(2<sup>k-1</sup>+2<sup>k-2</sup>+......+2+1)-X即为X的每位求反<br/>
所以二进制的负数等于其每位求反加1




$$I=\sum_{i=1}^n d_i*2^i$$<br/>
$$=0+\sum_{i=1}^n d_i*2^i$$<br/>
$$=\sum_{i=k+1}^m 0*2^i+\sum_{i=1}^n d_i*2^i$$<br/>
$$=\sum_{i=k+1}^m 0*2^i+I$$<br/>
可得当I为正数，在左边用0补齐即可。<br/>
对于负数扩展：<br/>
$$-I=-\sum_{i=1}^n d_i*2^i$$<br/>
$$=-(\sum_{i=k+1}^m 0*2^i+\sum_{i=1}^n d_i*2^i)$$<br/>
由于二进制的负数等于其每位求反加1,可得<br/>