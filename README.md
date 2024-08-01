在控制台中创建基于文本的波浪动画。
由 FireStar0507 编写
参数：
1· content（列表）：定义内容字符及其行为的列表：
（1）content[0]：用于波浪的字符（默认为“*”）。
（2）content[1]：初始方向（1 表示增加，0 表示减少）。
（3）content[2]：内容字符的初始计数。
（4）content[3]：内容字符的最大计数。
（5）content[4]：内容字符的最小计数。
2· filler（列表）：定义填充物字符及其行为的列表（与“content”的结构相同）。
3· interval （数值）：每个动画帧之间的时间间隔（以秒为单位）。
        

Creates a text-based wave animation in the console.
Written by FireStar0507
Args:
1· content (list): A list defining the content character and its behavior:
（1）content[0]: The character used for the wave (default "*").
（2）content[1]: Initial direction (1 for increasing, 0 for decreasing).
（3）content[2]: Initial count of the content character.
（4）content[3]: Maximum count of the content character.
（5）content[4]: Minimum count of the content character.
2. filler (list):  A list defining the filler character and its behavior (same structure as 'content').
3. interval (float): The time interval between each animation frame (in seconds).
