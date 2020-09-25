## 1. 音频

## 1.1 声音的本质
声音的本质是机械波

声音震动信号 -> 电信号 -> AD采集数字化 PCM -> 加上一个头WAV

* 采样位数

* 采样率
采样频率一般共分为22.05KHz、44.1KHz、48KHz三个等级。22.05KHz只能达到FM广播的声音品质，44.1KHz则是理论上的CD音质界限，48KHz则已达到DVD音质了

* 码率
一套双声道数字音频若取样频率为44.1KHz，每样值按16bit量化，则其码率为：2*44.1kHz*16bit=1.411Mbit/s


### 1.2 声音传输

* 编码

数字音频压缩编码采取去除声音信号中冗余成分的方法来实现。所谓冗余成分指的是音频中不能被人耳感知到的信号，它们对确定声音的音色，音调等信息没有任何的帮助。

冗余信号包含人耳听觉范围外的音频信号以及被掩蔽掉的音频信号等。例如，人耳所能察觉的声音信号的频率范围为20Hz～20KHz，除此之外的其它频率人耳无法察觉，都可视为冗余信号