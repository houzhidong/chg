计182 侯志东 2018310763
# 一、实验目的
1、掌握字符串String及其方法的使用
2、掌握异常处理结构
# 二、实验要求
内容：利用已学的字符串处理知识编程完成《长恨歌》古诗的整理对齐工作，写出功能函数，并运行。达到如下功能：
1.	每7个汉字加入一个标点符号，奇数时加“，”，偶数时加“。”
2.	允许提供输入参数，统计古诗中某个字或词出现的次数
3.	考虑操作中可能出现的异常，在程序中设计异常处理程序

输入：汉皇重色思倾国御宇多年求不得杨家有女初长成养在深闺人未识天生丽质难自弃一朝选在君王侧回眸一笑百媚生六宫粉黛无颜色春寒赐浴华清池温泉水滑洗凝脂侍儿扶起娇无力始是新承恩泽时云鬓花颜金步摇芙蓉帐暖度春宵春宵苦短日高起从此君王不早朝承欢侍宴无闲暇春从春游夜专夜后宫佳丽三千人三千宠爱在一身金屋妆成娇侍夜玉楼宴罢醉和春姊妹弟兄皆列士可怜光采生门户遂令天下父母心不重生男重生女骊宫高处入青云仙乐风飘处处闻缓歌慢舞凝丝竹尽日君王看不足渔阳鼙鼓动地来惊破霓裳羽衣曲九重城阙烟尘生千乘万骑西南行<未完，待续>
输出：
汉皇重色思倾国，御宇多年求不得。
杨家有女初长成，养在深闺人未识。
天生丽质难自弃，一朝选在君王侧。
回眸一笑百媚生，六宫粉黛无颜色。
春寒赐浴华清池，温泉水滑洗凝脂。
侍儿扶起娇无力，始是新承恩泽时。
云鬓花颜金步摇，芙蓉帐暖度春宵。
春宵苦短日高起，从此君王不早朝。…………
注意： 输入的内容，利用main方法中的args数组传递
# 三、实验过程
1. 学习字符串String结构和用法。
2. 编写代码，判断字符个数，自动加入标点。
3. 加入异常处理结构。
# 四、流程图
![image](https://github.com/houzhidong/chg/blob/master/hzd.jpg)
# 五、核心代码
异常处理结构：
package test;
public class three extends Exception{
	public three(String str){ 
           System.out.println (str);
 	}
}
将文字转换为字符串
public class one {
	String x = "汉皇重色思倾国御宇多年求不得杨家有女初长成养在深闺人未识天生丽质难自弃一朝选在君王侧回眸一笑百媚生六宫粉黛无颜色春寒赐浴华清池温泉水滑洗凝脂侍儿扶起娇无力始是新承恩泽时云鬓花颜金步摇芙蓉帐暖度春宵春宵苦短日高起从此君王不早朝承欢侍宴无闲暇春从春游夜专夜后宫佳丽三千人三千宠爱在一身金屋妆成娇侍夜玉楼宴罢醉和春姊妹弟兄皆列士可怜光采生门户遂令天下父母心不重生男重生女骊宫高处入青云仙乐风飘处处闻缓歌慢舞凝丝竹尽日君王看不足渔阳鼙鼓动地来惊破霓裳羽衣曲九重城阙烟尘生千乘万骑西南行"; 
	StringBuffer s = new StringBuffer(x);
# 六、实验结果
![image](https://github.com/houzhidong/chg/blob/master/syjg.png)
# 七、实验感想
这次实验我对java有了更多的了解，知道了字符串String。学会了异常处理结构。实验过程中经常遇到不会的问题，这时便在网上寻找解决办法，找不到便讨论，最终解决问题。编写代码时要认真仔细，这样才能减少程序出错。希望以后在java实验中学到更多东西。
