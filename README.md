# LanhuStyleToReactNative

用于将蓝湖web的style转换为react native的模式
例如：
width: 81px;
height: 38px;
font-size: 27px;
font-family: PingFangSC-Medium, PingFang SC;
font-weight: 500;
color: #222222;
line-height: 38px;
将会转换为：
width: px(81),
height: px(38),
fontSize: px(27),
fontWeight: 'bold',
color: '#222222',
lineHeight: px(38),