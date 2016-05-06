## GET /action

### 搜索有声资源action 功能介绍
为RUYI API的意图理解结果对接整合知识库语义搜索以及第三方数据服务。

### 服务地址

<pre>
http://action.ruyi.ai/
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


### 喜马拉雅获取专辑曲目action 功能介绍
为RUYI API的意图理解结果对接整合知识库语义搜索以及第三方数据服务。

### 服务地址

<pre>
http://action.ruyi.ai/
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
    <td>album_id</td>
    <td>String</td>
    <td>是</td>
    <td>专辑ID</td>
   </tr>
   <tr>
    <td>page</td>
    <td>Integer</td>
    <td>否</td>
    <td>起始页</td>
   </tr>
   <tr>
    <td>count</td>
    <td>Integer</td>
    <td>否</td>
    <td>每页显示数目，默认200</td>
   </tr>
  </tbody>
</table>



### 服务调用示例
curl 'http://action.ruyi.ai/xmly/search?q=%E7%BD%97%E8%BE%91%E6%80%9D%E7%BB%B4'

返回结果示例
<!--<h3 id="-4">返回结果示例</h3>-->


### 成语接龙 action 功能介绍
为RUYI API的意图理解结果对接整合知识库语义搜索以及第三方数据服务。

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


### 词语接龙 action 功能介绍
为RUYI API的意图理解结果对接整合知识库语义搜索以及第三方数据服务。

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

