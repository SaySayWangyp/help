## GET /action

### 搜索有声资源action 
所属领域服务：有声资源v0.2

### 服务地址

<pre>
http://action.ruyi.ai/xmly/search
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>q</td>
    <td>String</td>
    <td>是</td>
    <td>搜索关键词</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://action.ruyi.ai/xmly/search?q=%E7%BD%97%E8%BE%91%E6%80%9D%E7%BB%B4'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
    {
	"code": 0,
	"msg": "成功",
	"result": {
		"id": "xmly:sound:2060680",
		"html_link": "http://www.ximalaya.com/sound/2060680",
		"source": "喜马拉雅",
		"source_link": "http://www.ximalaya.com/",
		"sound_id": "2060680",
		"title": "女人是一道题 59",
		"media_url": "http://audio.xmcdn.com/group14/M07/03/C1/wKgDZFbBlX2CJbrzAWriWVSHstU747.m4a",
		"cover_url": "http://fdfs.xmcdn.com/group5/M09/4B/A5/wKgDtVS4cZezc7RDAAHjHCQ8i2g645_web_meduim.jpg",
		"mp3_audio_url": "http://fdfs.xmcdn.com/group11/M00/F4/F5/wKgDa1bBlUqxzs9EALN_2uwltV4193.mp3",
		"album": "罗辑思维 全集",
		"album_id": "239463",
		"type": "sound",
		"tracks": {
			"id": 2060680,
			"kind": "track",
			"category_id": 8,
			"track_title": "女人是一道题 59",
			"track_tags": "脱口秀,罗振宇",
			"track_intro": "",
			"cover_url_small": "http://fdfs.xmcdn.com/group5/M09/4B/A5/wKgDtVS4cZezc7RDAAHjHCQ8i2g645_web_meduim.jpg",
			"cover_url_middle": "http://fdfs.xmcdn.com/group5/M09/4B/A5/wKgDtVS4cZezc7RDAAHjHCQ8i2g645_web_large.jpg",
			"cover_url_large": "http://fdfs.xmcdn.com/group5/M09/4B/A5/wKgDtVS4cZezc7RDAAHjHCQ8i2g645_mobile_large.jpg",
			"announcer": {
				"id": 1412917,
				"kind": "user",
				"nickname": "罗辑思维脱口秀",
				"avatar_url": "http://fdfs.xmcdn.com/group5/M07/4A/35/wKgDtlS4cmeAM8R4AAC2jG7vGBo443_web_large.jpg",
				"is_verified": true
			},
			"duration": 2941,
			"play_count": 1415565,
			"favorite_count": 10229,
			"comment_count": 1498,
			"download_count": 0,
			"play_url_32": "http://fdfs.xmcdn.com/group11/M00/F4/F5/wKgDa1bBlUqxzs9EALN_2uwltV4193.mp3",
			"play_size_32": 11763674,
			"play_url_64": "http://fdfs.xmcdn.com/group11/M00/0E/0F/wKgDbVbBlWGB057YAWb-3-_3T0E597.mp3",
			"play_size_64": 23527135,
			"play_url_64_m4a": "http://audio.xmcdn.com/group14/M07/03/C1/wKgDZFbBlX2CJbrzAWriWVSHstU747.m4a",
			"play_size_64_m4a": 23781977,
			"play_url_24_m4a": "http://audio.xmcdn.com/group12/M08/02/4B/wKgDXFbBlYTAooWVAIqCIOy8kuo618.m4a",
			"play_size_24_m4a": 9077280,
			"download_url": "http://download.xmcdn.com/group3/M07/0A/08/wKgDslMBdUSgRM9EALpBxD4mtx4422.aac",
			"download_size": 12206532,
			"subordinated_album": {
				"id": 239463,
				"album_title": "罗辑思维 全集",
				"cover_url_small": "http://fdfs.xmcdn.com/group5/M09/4A/32/wKgDtlS4cZeCzmE2AAHjHCQ8i2g083_mobile_small.jpg",
				"cover_url_middle": "http://fdfs.xmcdn.com/group5/M09/4A/32/wKgDtlS4cZeCzmE2AAHjHCQ8i2g083_mobile_meduim.jpg",
				"cover_url_large": "http://fdfs.xmcdn.com/group5/M09/4A/32/wKgDtlS4cZeCzmE2AAHjHCQ8i2g083_mobile_large.jpg"
			},
			"source": 2,
			"updated_at": 1455777916000,
			"created_at": 1392604484000,
			"order_num": 121
		},
		"match_rule": "match"
	}
}
```

### 查天气 action 功能介绍
所属领域服务：查询天气v0.4

### 服务地址

<pre>
http://api.ruyi.ai/ruyi-action/weather2
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>location</td>
    <td>String</td>
    <td>否</td>
    <td>地理位置（与经纬度至少有一个）</td>
   </tr>
   <tr>
    <td>date</td>
    <td>String</td>
    <td>否</td>
    <td>查询日期（格式"yyyy-MM-dd"，没有的话默认今天）</td>
   </tr>
   <tr>
    <td>lat</td>
    <td>String</td>
    <td>否</td>
    <td>纬度</td>
   </tr>
   <tr>
    <td>lon</td>
    <td>String</td>
    <td>否</td>
    <td>经度</td>
   </tr>
   <tr>
    <td>weatherEntity</td>
    <td>String</td>
    <td>否</td>
    <td>天气实体（雨、雪、风、雾、伞、紫外线、羽绒服）</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://api.ruyi.ai/ruyi-action/weather2?location=%E4%B8%8A%E6%B5%B7&weatherEntity=%E9%9B%A8'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"month_day": "5月27日",
		"week_day": "星期五",
		"suggestion": {
			"comf": {
				"brf": "舒适",
				"txt": "白天不太热也不太冷，风力不大，相信您在这样的天气条件下，应会感到比较清爽和舒适。"
			},
			"cw": {
				"brf": "不宜",
				"txt": "不宜洗车，未来24小时内有雨，如果在此期间洗车，雨水和路上的泥水可能会再次弄脏您的爱车。"
			},
			"drsg": {
				"brf": "较舒适",
				"txt": "建议着薄外套、开衫牛仔衫裤等服装。年老体弱者应适当添加衣物，宜着夹克衫、薄毛衣等。"
			},
			"flu": {
				"brf": "易发",
				"txt": "相对于今天将会出现大幅度降温，空气湿度较大，易发生感冒，请注意适当增加衣服。"
			},
			"sport": {
				"brf": "较不宜",
				"txt": "有较强降水，建议您选择在室内进行健身休闲运动。"
			},
			"trav": {
				"brf": "一般",
				"txt": "温度适宜，有微风同行，但较强降雨的天气将给您的出行带来很多的不便，若坚持旅行建议带上雨具。"
			},
			"uv": {
				"brf": "最弱",
				"txt": "属弱紫外线辐射天气，无需特别防护。若长期在户外，建议涂擦SPF在8-12之间的防晒护肤品。"
			}
		},
		"aqi": {
			"city": {
				"aqi": "30",
				"co": "1",
				"no2": "43",
				"o3": "77",
				"pm10": "24",
				"pm25": "21",
				"qlty": "优",
				"so2": "7"
			}
		},
		"day_weather": {
			"astro": {
				"sr": "04:52",
				"ss": "18:50"
			},
			"cond": {
				"code_d": "306",
				"code_n": "305",
				"txt_d": "中雨",
				"txt_n": "小雨"
			},
			"date": "2016-05-27",
			"hum": "83",
			"pcpn": "4.8",
			"pop": "99",
			"pres": "1010",
			"tmp": {
				"max": "22",
				"min": "19"
			},
			"vis": "2",
			"wind": {
				"deg": "70",
				"dir": "东北风",
				"sc": "微风",
				"spd": "5"
			},
			"condition": "中雨转小雨"
		},
		"speech": "会下的哦，记得要带伞呀",
		"weatherEntity": "雨",
		"is_weather": "yes",
		"prov": "直辖市",
		"basic": {
			"city": "上海",
			"cnty": "中国",
			"id": "CN101020100",
			"lat": "31.213000",
			"lon": "121.445000",
			"update": {
				"loc": "2016-05-27 11:51",
				"utc": "2016-05-27 03:51"
			}
		}
	}
}
```

### 娱乐推送 action 功能介绍
所属领域服务：娱乐推送v0.2

### 服务地址

<pre>
http://action.ruyi.ai/xxhh
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>tag1</td>
    <td>String</td>
    <td>否</td>
    <td>标签1</td>
   </tr>
   <tr>
    <td>tag2</td>
    <td>String</td>
    <td>否</td>
    <td>标签2</td>
   </tr>
   <tr>
    <td>tag3</td>
    <td>String</td>
    <td>否</td>
    <td>标签3</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://lab.ruyi.ai/ruyi-action/xxhh'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"category": "趣图",
		"tags": ["2B青年", "恶搞", "雷人", "趣图", "搞笑图片"],
		"image_url": "http://pic.xxhh.com/cons/20141210/e2dfc4faf01dd287.jpg",
		"article": "哥的美貌谁人能及？",
		"type": "image",
		"id": "283383"
	}
}
```

### 美图搜搜 action 功能介绍
所属领域服务：美图搜搜v0.2

### 服务地址

<pre>
http://action.ruyi.ai/image/word
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>word</td>
    <td>String</td>
    <td>是</td>
    <td>搜索关键词</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://lab.ruyi.ai/ruyi-action/image/word?word=%E5%88%9D%E9%9F%B3'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"image_url": "http://i1.17173.itc.cn/2011/news/2011/06/28/lj0628yxdgg08s.jpg",
		"type": "image"
	}
}
```

### 黄历 action 功能介绍
所属领域服务：查询黄历0.1

### 服务地址

<pre>
http://test.shuoshuorili.com/smartv-box/laohuangli
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>date</td>
    <td>date（yyyy-mm-dd）</td>
    <td>是</td>
    <td>查询日期</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://test.shuoshuorili.com/smartv-box/laohuangli?date=2016-05-08'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"yinli": "丙申(猴)年四月初二",
		"yi": "解除 出行 纳采 冠笄 竖柱 上梁 移徙 作灶 进人口 入宅 纳畜 牧养",
		"ji": "祭祀 伐木 架马 安床 修造 动土 安葬 修坟 破土",
		"date": "2016-05-08"
	}
}
```

### 星座运势 action 功能介绍
所属领域服务：星座运势0.1

### 服务地址

<pre>
http://test.shuoshuorili.com/smartv-box/constellation
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>name</td>
    <td>string</td>
    <td>是</td>
    <td>星座名称</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://test.shuoshuorili.com/smartv-box/constellation?name=%E5%B0%84%E6%89%8B%E5%BA%A7'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"name": "射手座",
		"all": "40%",
		"color": "黑色",
		"number": 2,
		"summary": "这个周末你感到略微有些不爽，与他人分享你的观点可能并不能获得认同，让你感到有一些挫败感，而你也容易在沟通中想到自己目前的瓶颈期，和能力上的不足。总之不要气馁，先安顿好自己私生活吧。",
		"friend": "天秤座",
		"date": "2016-05-08"
	}
}
```


### 成语接龙 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://action.ruyi.ai/chengyujielong/play
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>q</td>
    <td>String</td>
    <td>是</td>
    <td>输入文本（成语)</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://action.ruyi.ai/chengyujielong/play?q=%E4%B8%80%E5%B8%86%E9%A3%8E%E9%A1%BA'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"isChengyu": true,
		"isValidMatch": true,
		"chengyuToMatch": "顺水推舟",
		"explanation": "顺著水流的方向推船。比喻顺应情势行事。",
		"lastPinyin": "zhou",
		"score": 1,
		"beatPercent": 1,
		"totalNumUserSay": 1,
		"prevChengyu": "顺水推舟"
	}
}
```

### 词语接龙 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://action.ruyi.ai/ciyujielong/play
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>q</td>
    <td>String</td>
    <td>是</td>
    <td>输入文本（词语)</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://action.ruyi.ai/ciyujielong/play?q=%E8%8B%B9%E6%9E%9C'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"isCiyu": true,
		"isValidMatch": true,
		"ciyuToMatch": "果汁",
		"score": 1,
		"beatPercent": 1,
		"totalNumUserSay": 1,
		"prevCiyu": "果汁"
	}
}
```


### 翻译 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://action.ruyi.ai/baidu/translate
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>q</td>
    <td>String</td>
    <td>是</td>
    <td>要翻译的内容</td>
   </tr>
   <tr>
    <td>from</td>
    <td>String</td>
    <td>否</td>
    <td>原文语种</td>
   </tr>
   <tr>
    <td>to</td>
    <td>String</td>
    <td>否</td>
    <td>译文语种</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://lab.ruyi.ai/ruyi-action/baidu/translate?q=I%20love%20you'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"from": "en",
		"to": "zh",
		"trans_result": [{
			"src": "I love you",
			"dst": "我爱你"
		}]
	}
}
```


### 星座知识 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://action.ruyi.ai/constellation/search
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>month</td>
    <td>Integer</td>
    <td>是</td>
    <td>出生月份</td>
   </tr>
   <tr>
    <td>day</td>
    <td>Integer</td>
    <td>是</td>
    <td>出生日</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://lab.ruyi.ai/ruyi-action/constellation/knowledge?constellation=%E6%B0%B4%E7%93%B6%E5%BA%A7'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"love": {
			"女": "",
			"男": ""
		},
		"most": "最会看人脸色、最不怕透露隐私、最没原则\n最会突发奇想、最爱恶作剧、最可能国际联姻\n双子座\n双子座\n最容易分心、最会肢体语言、最拿得起放得下\n最会学第二语言、最不正经、最常脚踏两条船\n最爱作弊、最鬼灵精、最善辩、最善变、最聒噪\n最不体贴、最会临时抱佛脚、最怕无聊、最神经质\n最有人缘、最圆滑处事、最会投机取巧、反应最快。[2]",
		"pair": {
			"天蝎座：": "友情：★★★★爱情：★★★★★婚姻：★★★★★亲情：★★★如果你们在一起，其实就等于组成了强势团体！因为你们两个人虽然不尽相同，但是强势互补，思想行为情投意合，最初的时候，双子座会被天蝎座这种激情同神秘所吸引，但一相处，你会发觉天蝎座的神秘，其实是他收起自己的情绪，不表白出来，对有什么说什么的你，等于看一部侦探小说，极度想知道内心的天蝎是什么样子的！而你同朋友来往多些，他的妒忌心又出现，妒而生爱，越爱越深，只是眼神都令你神魂颠倒。相反天蝎座在被双子座这种灵活乖巧的魅力吸引，相处后就会feel到他挺暖而且挺Cool的，正是你所需要的，而你用的一套方法，只会更吸引他的注意，习大大和彭妈妈就是最强的双子天蝎组合。",
			"巨蟹座：": "友情：★★★★爱情：★★★婚姻：★★亲情：★★★★其实双子座的人和你谈恋爱，心态上只是“搭讪”，谁知道搭上了就发现非常聊得来。双子那一种谈笑风生的态度，打动巨蟹座相当温柔的心。很偶然地搭讪，接着一起坐着、一起吃饭、一起埋单，这个过程，正是双子座和巨蟹座相识至相恋的写照，但吃完这顿饭之后再怎么下去就是你们要面对的问题，这一场的欢乐搞不好就会成为将来的悲哀。因为大家的人生观根本不同，双子用理性看爱情，巨蟹用感性，相处之后，意见不合，矛盾顿生，敏感的巨蟹座会尝试去抓紧非常外向的双子座，但用力过度，钳伤他的话，双子座会走的，要留意，巨蟹座喜欢留在家，但双子座会觉得在家如坐牢。",
			"摩羯座：": "友情：★★爱情：★★★婚姻：★★亲情：★★★要下足功夫去互相适应的一对情侣。如果摩羯是男，双子是女还好，要是相反的话，就麻烦了，要加油哦。因为男的摩羯座会在实际生活上帮到双子座，而且一认定她之后很少会变心，组织家庭之后在经济上更能把双子座胡乱花费的习惯强迫改变，将来生活有保障。反而男的是双子座的话，麻烦多多，摩羯座女生会受不了他那种全世界都是朋友而且花心的态度，双子座也受不了摩羯座老婆的唠唠叨叨，干脆不回家。而这又会搞到摩羯座更加不妥，矛盾越积越深了。",
			"金牛座：": "友情：★★爱情：★★婚姻：★★亲情：★★基本上，金牛座无办法适应双子座那种“没一刻能停下来”的性格，虽然大家的交往的过程中，双子座会带给金牛座很多很多乐趣，但相处久了，金牛座往往会跟不上双子座的步伐。双子座的人又会为金牛座那一种沉默稳定的生活方式感到乏味。两个人要想走在一起，大家都要付出很多。另一方面必须要注意的就是金牛座那种强烈的性需要，有时会让双子座有需索过多的感受。",
			"双子座：": "友情：★★★★★爱情：★★★婚姻：★★★亲情：★★★★半斤八两的两个小朋友碰在一起，一定玩得很开心很高兴，世界上怎会可能有这样的一对，一碰上已经觉得观念行为一摸一样，大家有讲不完的话题标题，日日新鲜？！这个就是双子座的组合。当然这个组合也不是无懈可击的，彼此太小朋友的脾性，自然发生争执的机会也增多，全都是芝麻绿豆的事，虽然不会放在心，但难免影响感情，而且大家都爱玩一些小聪明，欺骗、不负责任是你们的强项，可惜这次遇到的人完全看穿你那一套，动一动尾巴，对方已经知你在搞什么鬼，真不过瘾啊。",
			"射手座：": "友情：★★★★爱情：★★★婚姻：★★亲情：★★★你们是成180度对角的对宫星座，所以在一起只有两个可能，非常极端的好或者非常极端的坏。双子座和射手座首先面对的问题就是，这对情侣单独在一起的时间实在太少，大家都外向，朋友又多，嗜好多箩，哪有机会享受到二人世界呢？只不过最初的时候，双子座觉得射手座的人很能聊，而且有一句说一句，直接了当不罗嗦，自己没有的好处，好象他都有齐，而射手座一样中计。但长久相处下来，真面目败露，麻烦就来啦。在恋爱中途，经常发生的情况就是大家都另有新欢，随时随地是一个四角以上的关系，开始的优点也变成互相憎恨的缺点。",
			"白羊座：": "友情：★★★★爱情：★★★★婚姻：★★★亲情：★★★火象星座的白羊座加上风象星座的双子座，大家都是乐观一族，白羊座和双子座一起，热情总是一发不可收拾。由于生活的态度和方式很接近，多变的双子结合冲动的白羊更添趣味。这对组合，男双子女白羊会更合适。因为白羊没有双子刁钻的脑袋，如果是白羊座的男性遇上双子座的女性，你会被她搞得又爱又恨。一旦追到手了，白羊又要小心不可让自己的大男人主义抬头，太过压迫她的话，她随时会有婚外情的。",
			"水瓶座：": "友情：★★★★爱情：★★★★★婚姻：★★★★★亲情：★★★★★Perfect的一对!!!又一对非常情侣。因为大家都是风象星座，变化好大，感觉很相似。所以相识之初，很容易被对方“电”到，急速堕入爱河，大家都飞不出大家的掌心咯。你们这种自由自然开放豁达的态度，谈起情来比一般情侣来得潇洒，不会将爱情变成了令自己不开心的压力，大家生活圈子又广阔，真是啥都不用愁，两个人之间的关系可谓这么近又那么远，介乎友情同爱情之间，有什么都讲出来，不会有隔夜仇。这样组合的确好适合，只不过可能有时大家都太忙而忽略了对方，可以留一点两人的时间和空间给大家。",
			"双鱼座：": "友情：★★爱情：★★婚姻：★★亲情：★★★不是太默契，因为大家是不同一类，而且都有多面性格和起伏的情绪，除了开头可能因为性的吸引力被对方迷倒之外，长远相处，很难融入对方陌生的世界之中，越来越想脱离对方。所以你们开始恋爱之后，一定要为对方而改变一下自己，起码大家都不要今天这样、明天那样，变来变去。有这个决心才有未来。还有一点要小心，双子座为了自己利益，总是讲大话，双鱼座又会为取悦对方而讲大话，骗来骗去，真的可以吗？",
			"天秤座：": "友情：★★★★★爱情：★★★★★婚姻：★★★★亲情：★★★★Perfect的一对!!!大家都是风象星座，都是爱变动，贪新鲜，初初见面已经有一见如故的感觉，而且即食面的爱情心态，往往过程一拍即合，很快已经谈起情来了。相处下来这种有点像又不像的人生态度，使你们永远保持新鲜，不会太激烈，但又不会很平淡，真是一对好搭档，而且不会谁要领导谁，是交互式的关系。",
			"狮子座：": "友情：★★★★★爱情：★★★★婚姻：★★★★亲情：★★★★简直是天生一对，还是怎么看都看不厌的一对。因为你们都对生活有求进心，不会甘心停留在一个层面，即使内心想法不一样，但步伐一致，能够长久在一起。双子座的人虽然多变，但面对狮子座的霸气，很自然就会收敛起来，狮子座也可以用一种豁达的心去包容双子座那一种善变贪新鲜的特性，明知他们天性如此，不如刻意放上心。",
			"处女座：": "友情：★★★★爱情：★★★婚姻：★★亲情：★★★如果大家不是经常见面，只是偶尔聊聊，那么你们可以做到好朋友，因为大家都有“八卦”的本能，可以互通有无，可能因此对对方产生好感。可惜一旦要一起生活，马上变成敌人。试想想，一个变化无常，虎头蛇尾，一个事事挑剔，容忍不得半点瑕疵的人，怎么相处？双子座那种吊儿郎当的态度，会气死小器量的处女座，在用钱态度上更甚，双子座不停花钱买新鲜无谓东西的行为，常引起吝啬成性的处女座不满。"
		},
		"legend": "丽达王妃生了许多可爱的孩子，其中有两个兄弟，不光是感情特别要好，长相也几乎一模一样，很容易让人以为他们俩是一对双生子。\n其实，在这两兄弟中，哥哥是丽达王妃与天神宙斯所生的儿子，弟弟则是与巴斯达国王所生的，俩人为同母异父的兄弟，而且哥哥的身份是\"神\"，且有永恒的生命，弟弟则是一般的普通人。\n有一天，希腊遭到了一头巨大的野猪攻击，王子们召集许多的勇士去追杀野猪，当野猪顺利地被解决后，勇士之间却因为互争功劳，而在彼此之间结下了仇恨。\n在一次市集的热闹场合中，两边互看对方不顺眼的勇士不期而遇，当然又免不了一番争吵。在争吵中，有人开始动起武来，于是场面变得一发不可收拾，许多人都在这场打杀中受伤，甚至死亡。很不幸地，两位王子当中的弟弟，也是在这一场混乱之中，被杀身亡。\n一向与这个弟弟特别要好的哥哥，完全无法接受弟弟已经死亡的消息，抱着弟弟的尸首不停的痛哭，希望弟弟可以起死回生，让两人可以一起重享以前手足情深的欢乐日子。\n于是，哥哥回到天上向父亲宙斯请求，希望宙斯可以让弟弟复活。但是宙斯向他表示，弟弟只是个普通的人，本就会死，若是真的要让弟弟复活，就必须把哥哥剩余的生命分给弟弟。\n感情深厚的哥哥，当然是毫不犹豫的马上答应了，从此之后，兄弟俩又可以一起快乐的生活了。",
		"interaction": {
			"最容易被影响星座": "双鱼座",
			"最佳学习对象": "射手座",
			"最易掌握的星座": "处女座、摩羯座、白羊座、巨蟹座",
			"100%协调星座": "天秤座、水瓶座",
			"同类型星座": "射手座、双鱼座、处女座",
			"最信任的星座": "处女座",
			"最佳工作搭档": "巨蟹座",
			"对宫星座": "射手座",
			"80%协调星座": "双子座",
			"90%协调星座": "狮子座、白羊座",
			"最需注意的星座": "天蝎座、金牛座、双鱼座、狮子座",
			"最欣赏的星座": "天秤座"
		},
		"career": {
			"职场的优势": "",
			"职场的劣势": "面对事业的经营， 双子座不习惯将自己停留在一个「 位置」 或一份「 职务」 上太久， 对于爱情也是各地奔走。 很有自己想法的双子座， 虽然不想运用自己的才智去填补别人的虚荣， 但有时候人情世故还是必须要兼顾的， 太有个性对双子座的处境并不见得好； 你的天真率性在这工作中确实坏了你不少好事.",
			"职场的忠告": "让自己固定下来， 对双子座来说， 或许真有困难， 但处在变动的时局里， 让自己静定下来反而有好处。"
		},
		"section": [{
			"区间特点": "聪慧敏捷，很有潜力。为人处世无懈可击。但内心潜在二重性，遇事总是优柔寡断、不知所措或进退维谷。从而使他不能把自己的力量集中在一个确定的目标上。他有可能表现出非凡的智慧和才干，也有可能流于徒劳无益的夸夸其谈之中。一切都能使他兴趣盎然；一切对他也能很变得淡漠厌倦。",
			"动力来源": "动力来源：专心致志",
			"日期区间": "5月21日~5月31日："
		}, {
			"区间特点": "在灵感和想象方面有出色的天赋，这是个典型的艺术家的性格。襟怀坦白，但易受非难。幽默和讽刺是他生活中最好的自卫武器。对现实生活的适应能力较差，内心的不安常常折磨着他，使他企图逃避现实或力争改变自身现状。对于这一类型的人，尤其需要理智和敏感的充分协调。",
			"动力来源": "动力来源：直觉创新",
			"日期区间": "6月1日~6月10日："
		}, {
			"区间特点": "有很强的智力天赋。禀性纯正，为人真诚，喜欢与人打成一片。但是，他遇事或碰到困难容易气馁，或者失去清醒的头脑。尽管他的想法层出不穷，但往往很难以有效的方式展现在实际生活中。这一类型的人，从事抽象思维的工作，要比从事具体的工作更容易获得成功。",
			"动力来源": "动力来源：新思想",
			"日期区间": "6月11日~6月21日："
		}],
		"character": {
			"儿童": "双子座孩子生性好动，那么一辆供小孩子儿在里面爬着玩的携带式围栏将是必需之物，对此我不敢苟同。双子座孩子的本性是促使他去寻求、探索和学习，所以被限制在狭小的空间内对他就可能意味着残酷无情，更糟糕的是，这种身体上的禁锢将带给他精神上的厌烦。因此把他关在围栏里的时间必须是短暂的。对双子座孩子的自由给予太多的限制和阻碍，会导致他很难摆脱的感情上的沮丧。请记住，他的象征是空气，而空气是不停流动的。要保证，在你需要把他圈起来时，给他提供各种各样的玩具和众多花花绿绿的画书，来吸引他的注意才行。双子座的孩子以他们那小鸟般敏捷的动作使年龄大而性格沉稳的人感到紧张。成年人总在告诫他们，别再坐卧不宁，要有耐心，一次干一件事。然而同时做两件事对他们来说却是最自然的事，被墨守成规或沉静的人称作坐卧不宁的状态，对于双子座孩子来说，恰恰是正常的活动状态。让双子座孩子觉得，只有模仿比他缺乏生气、行动迟缓的孩子才能得到更多的赞许的做法，是不正确的。我们应该尽量提醒自己，使性格内向的成年人担忧的、行动敏捷的双子座孩子，和使敢作敢为的成年人恼怒的、沉默胆小的摩羯座孩子，都恰恰表现着他们自我。想表现自己并非易事，因为人们总是力图改变别人的性格。",
			"女": "女人，总会有一定的典型。但对于双子座的女性来说可就不一定了。由于她双重，甚至多重的个性，她所欣赏的、吸引的男性，可就是各种类型都有了！这么听起来，你的处境好像有点四面楚歌的样子！不过你应该能够了解，其它的男人也跟你一样很难抵抗她的魅力。凭良心说，双子座的女子实在很有趣，非常外向，话特别多。她可以像个小男生一样，陪你上山下海的疯狂玩乐；也可以正经八百的跟你聊天文地理！当然，她更会像个小公主一样跟你花前月下温柔缠绵。她是那么的充满着乐趣和变化！只可惜她对你的态度，也是变化多端，难以捉摸。你几乎很难理解，为什么昨天才令她痴迷的优点，今天竟成了被她嗤之以鼻的缺点。先不要伤心，也不要生气！你应该先冷静下来，认真的了解一下这个让你开心又叫你烦心的小精灵。",
			"男": "你小时候一定很喜欢看魔术，否则，你怎么会跟一个“谜”样的双子座男人恋爱呢？我们都不得不承认，他真的很可爱，脑子里装满了千奇百怪的新鲜点子，谈话中尽是幽默和机智。如果你在一个社交场合遇见他，你真的会很容易被他吸引，他总是妙语如珠的逗得大伙儿很开心。他的态度亲切自然，一点都不给人压迫感。从政治、人生，到黄色笑话，保证绝无冷场。跟他在一起真是有趣极了。但是，如果你是个占有欲极强的女人，我劝你趁早死心吧！否则气死自己是迟早的事。想要他每天一大早向你报告行程，让你随时找得到他，几乎是不可能的。就算你事先知道他的行踪，这一天当中也会有太多事情可能让他改变原先的计划。他是“双子”座的！两个脑袋加在一起，念头当然会转来转去，让人捉摸不定啰！"
		},
		"feature": "基本性格\n双子座的人喜爱变化，不可能同一时间只做一件事情，五时花六时变，心不在焉；虽然拥有些小聪明，但不专一，往往流于肤浅，持久力又低，成功很难，可以说是理性但不安的星座。\n双子座的守护星水星是使者之神，会刺激智慧，但也会令人产生挑剔、紧张的情绪；不过双子座掌握沟通，所以双子座的人善于和人相处。双子座的人可以不停说话，和他们谈情最好的方法就是聊天。\n不要以为双子座的人花心，只是他们的不专心影响你的看法，他只是贪新鲜和喜欢吸收资讯，这样他们才会觉得快乐。\n双子座的人反应灵敏口才一流，天生善于胡编瞎凑而且不着痕迹，丝毫没有狐狸尾巴可以露，一面说谎一面对你晓以大义，再加甜言蜜语，有声有色。如果想骗你到外地旅行，连山上的小花小草都会编得活灵活现呢！一路说来天衣无缝鲜龙活跳，最厉害的是：通常，他一说完自个儿就会忘啦！",
		"adv_and_disadv": {
			"优点": "多才多艺擅长沟通适应力强充满生命力懂得随机应变风趣幽默乐观知进退，有分寸八面玲珑，善于交际足智多谋，反应灵敏见人说人话，见鬼说鬼话",
			"缺点": "处世缺乏原则让人觉的不可靠意志不坚定、善变易受外来事物影响三分钟热度、不专心过于圆滑、容易紧张做事蜻蜓点水不深入举一反十、过于神经质"
		},
		"basic": {
			"星座名称": "双子座",
			"守护星": "水星",
			"守护石": "黄水晶",
			"阴阳性": "阳性",
			"幸运色": "黄色、橙色",
			"守护神": "赫尔墨斯",
			"出生日期": "5月21日～6月21日",
			"理想居住条件": "新式建筑，室内空气流通，家具少而精，丰富多彩的书籍和唱片以及音响设备，要有供朋友间促膝谈心的幽静的小角落。",
			"掌管身体": "肩膀、手臂、肺",
			"最大特征": "思想",
			"喜欢的场所": "飞机场、书店、学校、出版社、旅游圣地、无人售货商店、紧张而热烈的场所，靠窗处等。",
			"星座属性": "风象",
			"幸运石": "玛瑙",
			"理想的游居国": "俄罗斯、比利时、希腊、北非、撒丁岛，英国。",
			"金属": "水银",
			"幸运日": "星期二",
			"英文名": "Gemini",
			"幸运数字": "5、14、23、32",
			"幸运花": "羊齿蕨、仙人掌、紫玫瑰",
			"三方宫": "变动宫",
			"幸运物": "双数事物",
			"掌管宫位": "第三宫"
		},
		"quick_pair": {
			"双子座最佳暧昧星座组合": "金牛座",
			"双子座最佳同事组合": "金牛座、摩羯座、天蝎座",
			"双子座最佳朋友组合": "白羊座、狮子座、双子座",
			"双子座最佳仇人组合": "处女座、双鱼座",
			"最配星座第三名": "　　配对指数：90　　配比拟重：44：56　　配对点评：风向双子的你和一个华丽贵气的狮子座，同样都是阳性星座，位置也相近，一样平常而言融通较易，是相互吸引又很相合的一对。狮子座跟你一样热爱交际生存。你应对狮子灼烁开阔的风格与可信任的态度深具好感。只是因为你们都有任性、独立、天性忽冷忽热的缺点，须特别过细。",
			"最配星座第一名": "　　配对指数：100　　配比拟重：48：52　　配对点评：同属风向星座们，无论事情或是恋爱，你们都能创建起良好的干系，艺术创作与来往方面更能取得和谐。在事业上，你们可以到达相助无间的地步，也可以借此增长相互的干系，得到相当高的符合度。天秤座可从交谈中以为到本身的空想即将实现，而你只要和他在一起，就以为将来弥漫灼烁和盼望。若能具备经济根本，踏上红毯的大概性很大。",
			"最配星座第二名": "　　配对指数：100　　配比拟重：52：48　　配对点评：两个同属风象星座的你们，很容易会孕育产生一种相知相惜的以为，进而洞开心胸采取对方，是开朗飘逸的组合。水瓶是天生聪明良好的好门生或好老师，由擅善于盛行信息、消息、数理化、谋略机，以是是个聪明尽头的人物。双子的头脑不停的动来动去，不停地从一个观点跳到另一个观点，你着实必要恒心和稳固，这点可汲打水瓶的能量，不但是爱情，在人际干系之中也是云云，因此水瓶是双子的绝配。"
		},
		"constellation_name": "双子座"
	}
}
```

### 随机笑话 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://api.ruyi.ai/ruyi-action/data/joke/random
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>



### 服务调用示例
curl 'http://api.ruyi.ai/ruyi-action/data/joke/random'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"text": "你喜欢我吗？”“你猜。”“喜欢！”“你再猜。”",
		"id": "joke:366d84269886c557cb6b55a52b6f4109",
		"tags": ["clean"],
		"type": "text"
	}
}
```

### 随机图片 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://api.ruyi.ai/ruyi-action/data/image/random
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>



### 服务调用示例
curl 'http://api.ruyi.ai/ruyi-action/data/image/random'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"image_url": "https://dn-vbuluo-storage.qbox.me/Fil8cNinWf8shEf4921bB_qdFAQu/40269979_401.jpg\n",
		"id": "image:04447f958e82ca70d23d0bc6b6614dc0",
		"tags": ["image", "艺术"],
		"type": "image"
	}
}
```

### 时间差 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://api.ruyi.ai/ruyi-action/time/diff
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>time1</td>
    <td>Long</td>
    <td>否</td>
    <td>第一个时间（UNIX毫秒数,没有的话默认当前时间）</td>
   </tr>
   <tr>
    <td>time1</td>
    <td>Long</td>
    <td>否</td>
    <td>第一个时间（UNIX毫秒数,没有的话默认当前时间）</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://api.ruyi.ai/ruyi-action/time/leapyear?time=12616151321'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"leapyear": "no",
		"pre_leapyear": 1968,
		"next_leapyear": 1972
	}
}
```

### 判断闰年 action 功能介绍
所属领域服务：

### 服务地址

<pre>
http://api.ruyi.ai/ruyi-action/time/leapyear
</pre>

### 输入参数

<ul>
<li>注意，所有字符串参数需要 URL-encoded.</li>
</ul>

<table  class="table-responsive border">
  <thead>
    <tr>
      <th>参数</th>
      <th nowrap="nowrap">参数类型</th>
      <th nowrap="nowrap">是否必须</th>
      <th>含义</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>time</td>
    <td>Long</td>
    <td>否</td>
    <td>需要判断的时间（UNIX毫秒数,没有的话默认当前时间）</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://api.ruyi.ai/ruyi-action/time/leapyear?time=12616151321'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->
```
{
	"code": 0,
	"msg": "成功",
	"result": {
		"leapyear": "no",
		"pre_leapyear": 1968,
		"next_leapyear": 1972
	}
}
```


