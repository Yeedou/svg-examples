# SVG

##  SVG 简介

SVG 指的是可缩放矢量图形（Scalable Vector Graphics）。
SVG 以 XML 格式定义基于矢量的图形。

## SVG 参考手册
### SVG 元素

| 元素                  | 描述                                                         |
| :-------------------- | :----------------------------------------------------------- |
| <a>                   | 创建包围 SVG 元素的链接。                                    |
| <altGlyph>            | 提供对用于呈现特定字符数据的字形的控制。                     |
| <altGlyphDef>         | 定义字形的替换集。                                           |
| <altGlyphItem>        | 定义字形替换的候选集。                                       |
| <animate>             | 定义元素的属性如何随时间变化。                               |
| <animateMotion>       | 使引用的元素沿着运动路径移动。                               |
| <animateTransform>    | 对目标元素上的变换属性进行动画处理，从而允许动画控制平移、缩放、旋转和/或倾斜 |
| <circle>              | 定义圆。                                                     |
| <clipPath>            | 定义剪切路径                                                 |
| <color-profile>       | 指定颜色配置文件描述（当使用 CSS 设置文档样式时）。          |
| <cursor>              | 定义独立于平台的自定义光标。                                 |
| <defs>                | 定义被引用元素的容器。                                       |
| <desc>                | 定义对 SVG 中容器元素或图形元素的纯文本描述。                |
| <ellipse>             | 定义椭圆。                                                   |
| <feBlend>             | 按照一定的混合模式将两个对象组合在一起。                     |
| <feColorMatrix>       | SVG 滤镜。应用矩阵变换。                                     |
| <feComponentTransfer> | SVG 滤镜。执行对数据按组件的重新映射。                       |
| <feComposite>         | SVG 滤镜。执行两个输入图像的智能像素组合。                   |
| <feConvolveMatrix>    | SVG 滤镜。应用矩阵卷积滤镜效果。                             |
| <feDiffuseLighting>   | SVG 滤镜。光照图像，使用 alpha 通道作为隆起映射。            |
| <feDisplacementMap>   | SVG 滤镜。映射置换。                                         |
| <feDistantLight>      | SVG 滤镜。定义光源。                                         |
| <feFlood>             | SVG 滤镜。填充滤镜子区域。                                   |
| <feFuncA>             | SVG 滤镜。为输入图形的透明度（alpha）组件定义变换函数。      |
| <feFuncB>             | SVG 滤镜。为输入图形的蓝色成分定义变换函数。                 |
| <feFuncG>             | SVG 滤镜。为输入图形的绿色成分定义变换函数。                 |
| <feFuncR>             | SVG 滤镜。为输入图形的红色成分定义变换函数。                 |
| <feGaussianBlur>      | SVG 滤镜。对图像执行高斯模糊。                               |
| <feImage>             | SVG 滤镜。从外部来源取得图像数据，并提供像素数据作为输出。   |
| <feMerge>             | SVG 滤镜。创建彼此叠加的图像层。                             |
| <feMergeNode>         | SVG 滤镜。feMerge 的子元素。                                 |
| <feMorphology>        | SVG 滤镜。对源图形执行“加肥”或“细化”。                       |
| <feOffset>            | SVG 滤镜。相对于当前位置移动图像。                           |
| <fePointLight>        | SVG 滤镜。                                                   |
| <feSpecularLighting>  | SVG 滤镜。照亮源图形，使用 alpha 通道作为隆起映射。          |
| <feSpotLight>         | SVG 滤镜。光源元素，用于 SVG 文件。                          |
| <feTile>              | SVG 滤镜。输入图像是平铺的，结果用来填充目标。               |
| <feTurbulence>        | SVG 滤镜。利用 Perlin 噪声函数创建图像。                     |
| <filter>              | 滤镜效果的容器。                                             |
| <font>                | 定义字体。                                                   |
| <font-face>           | 描述字体的特征。                                             |
| <font-face-format>    | 描述了它的父 <font-face-uri> 元素引用的字体的类型。          |
| <font-face-name>      | 指向本地安装的字体副本，用字体名称识别。                     |
| <font-face-src>       | 相当于 CSS 规范中的 @font-face 属性。                        |
| <font-face-uri>       | 指向远程字义的当前字体。                                     |
| <foreignObject>       | 允许包含来自不同的 XML 命名空间的元素。                      |
| <g>                   | 用于对元素分组。                                             |
| <glyph>               | 定义给定字形的图形。                                         |
| <glyphRef>            | 定义可能使用的字形。                                         |
| <hkern>               | 精细调整两个雕刻文字的水平距离。                             |
| <image>               | 定义图像。                                                   |
| <line>                | 定义线。                                                     |
| <linearGradient>      | 定义线性渐变。                                               |
| <marker>              | 定义在给定元素上绘制箭头或者多边标记所使用的图形。           |
| <mask>                | 定义遮罩元素。                                               |
| <metadata>            | 规定元数据。                                                 |
| <missing-glyph>       | 如果对于给定的字符，字体没有定义合适的<glyph>，则呈现missing-glyph元素的内容 |
| <mpath>               | 引用外部的 <path> 元素作为运动路径的定义。                   |
| <path>                | 定义路径。                                                   |
| <pattern>             | 定义图案。                                                   |
| <polygon>             | 定义包含至少三个边的图形。                                   |
| <polyline>            | 定义仅由直线组成的任何形状。                                 |
| <radialGradient>      | 定义径向渐变。                                               |
| <rect>                | 定义矩形。                                                   |
| <script>              | 定义脚本容器（例如 ECMAScript）。                            |
| <set>                 | 设置指定持续时间的属性值。                                   |
| <stop>                | 渐变的停止点。                                               |
| <style>               | 允许样式表直接嵌入到 SVG 内容中。                            |
| <svg>                 | 创建 SVG 文档片段。                                          |
| <switch>              | 对其直接子元素上的属性按照顺序进行评估，然后处理和呈现第一个评估为 true 的子元素。 |
| <symbol>              | 定义图形模板对象，它可以用 <use> 元素实例化。                |
| <text>                | 定义文本。                                                   |
| <textPath>            | 根据 <path> 元素的形状来放置文字。                           |
| <title>               | 对 SVG 中元素的纯文本描述。用户代理可将文本显示为工具提示。  |
| <tref>                | 引用 SVG 文档中的任何 <text> 元素并重用它。                  |
| <tspan>               | 与 <text> 元素相同，但可以嵌套在 text 标签内及其自身内部。   |
| <use>                 | 在 SVG 文档内取得目标节点，并在别的地方复制它们。            |
| <view>                | 查看图片的一种限定方法，就像缩放级别或者详细视图。           |
| <vkern>               | 精确地调整两个字符（glyph）间的垂直距离。                    |
