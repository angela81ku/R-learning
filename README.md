# R-learning
100 coding challenge day1
#向量的加減乘除
當兩個不同長度的向量加減乘除的時候，R會直接把短的向量依序補到跟長的向量相同(無論有無整除)
x <- c(1,2,3,4,5,6,7)
y <- c(1,2,3)
z <- x + y
z就會是一個有七個元素的向量2 4 6 5 7 9 8
具體拆解就是z會等於c(1,2,3,4,5,6,7)+c(1,2,3,1,2,3,1)
另外以前已經知道
x*2+100就會得到一個有七個元素的向量，每個向量都是對各x向量內的元素*2+100
102 104 106 108 110 112 114
這其實就是用到剛才的觀念，2跟100都是一個只有一個元素的向量，但是R會自動把他補齊到7個元素!
看超多基本教材都沒有講到這個XD
今天終於在MIT的教材裡面看到了
推薦玩這個課程，你只要打對一行代碼他就會鼓勵你打對了XDD
14 310x Intro to R

#workspace and file 如何用R語言直接管理檔案(平常在window圖形化介面上點點按按的東西如何用R語言來控制)

