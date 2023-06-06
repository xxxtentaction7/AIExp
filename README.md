# -由刘逸飞与孟庆民完成

基于opencv模板匹配的车牌识别，有简单的GUI，软件环境是python3.8,opencv4.2。用pycharm写的。
由于是识别字符采用的是模板匹配，模板比较多，所以运行时间比较长，识别一张车牌大概20s，并且准确度不高，有可能出现无法得出结果或者识别的结果错误，因为识别车牌对输入的图片的分辨率和色偏有关系。总之，这是一个比较粗糙简单的车牌识别项目，我做这个是为了应付课程设计。
识别的结果是车牌号码和牌照颜色。
算法主要步骤是：定位车牌，矫正车牌，识别颜色，分割字符，识别字符。
算法和GUI都有借鉴别人的博客
refer1是模板，function.py是算法,gui.py是界面
refer1请先解压

Based on opencv template matching license plate recognition, there is a simple GUI, the software environment is python 3.8, opencv 4.2. Written in pycharm.
Because the recognition character is a template matching, there are more templates, so the running time is relatively long, the recognition of a license plate is about 20s, and the accuracy is not high, there may be no results or recognition results error, because the recognition of license plates has a relationship with the resolution and color cast of the input picture. In short, this is a relatively crude and simple license plate recognition project, and I did this to cope with the course design.
The result of the identification is the license plate number and the license plate color.
The main steps of the algorithm are: locating the license plate, correcting the license plate, recognizing the color, segmenting the character, recognizing the character.
Both algorithms and GUIs borrow from other people's blogs
refer1 is the template, the function.py is the algorithm, and the gui.py is the interface
refer1: Please decompress it first
