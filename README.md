# check-idleness
#查询闲的程度

TODO: 
- backend
  - get a bilibili uid
  - crawl some user data
  - based on time spent on bilibili activities (?), output idleness 
- frontend
  - write some creative texts related to nana7mi


## example user data

```json
{
	"code": 0,
	"message": "0",
	"ttl": 1,
	"data":
	{
		"mid": XXXXXXX,
		"name": "XX_",
		"sex": "保密",
		"face": "http://i0.hdslb.com/bfs/face/XXX.jpg",
		"sign": "",
    
		"rank": 10000,
		"level": 6,
    
		"jointime": 0,
		"moral": 0,
		"silence": 0,
		"coins": 0,
		"fans_badge": false,
		"fans_medal":
		{
			"show": true,
			"wear": true,
      
			"medal":
			{
				"uid": 1579251,
				"target_id": 13248198,
				"medal_id": 159322,
				"level": 1,
				"medal_name": "海妈妈",
				"medal_color": 6067854,
				"intimacy": 60,
				"next_intimacy": 201,
				"day_limit": 1500,
				"medal_color_start": 6067854,
				"medal_color_end": 6067854,
				"medal_color_border": 6067854,
				"is_lighted": 1,
				"light_status": 1,
				"wearing_status": 1,
				"score": 60
			}
      
		},
		"official":
		{
			"role": 0,
			"title": "",
			"desc": "",
			"type": -1
		},
		"vip":
		{
    
			"type": 2,
			"status": 1,
			"due_date": 1648569600000,
      
			"vip_pay_type": 0,
			"theme_type": 0,
			"label":
			{
				"path": "",
        
				"text": "年度大会员",
				"label_theme": "annual_vip",
        
				"text_color": "#FFFFFF",
				"bg_style": 1,
				"bg_color": "#FB7299",
				"border_color": ""
			},
			"avatar_subscript": 1,
			"nickname_color": "#FB7299",
			"role": 3,
			"avatar_subscript_url": "http://i0.hdslb.com/bfs/vip/icon_Certification_big_member_22_3x.png"
		},
		"pendant":
		{
			"pid": 0,
			"name": "",
			"image": "",
			"expire": 0,
			"image_enhance": "",
			"image_enhance_frame": ""
		},
		"nameplate":
		{
			"nid": 74,
			"name": "大会员2018年度勋章",
			"image": "http://i2.hdslb.com/bfs/face/421179426c929dfeaed4117461c83f5d07ffb148.png",
			"image_small": "http://i1.hdslb.com/bfs/face/682001c2e1c2ae887bdf2a0e18eef61180c48f84.png",
			"level": "稀有勋章",
			"condition": "2018.6.26-7.8某一天是年度大会员"
		},
		"user_honour_info":
		{
			"mid": 0,
			"colour": null,
			"tags": []
		},
		"is_followed": false,
		"top_photo": "http://i1.hdslb.com/bfs/space/cb1c3ef50e22b6096fde67febe863494caefebad.png",
		"theme":
		{},
		"sys_notice":
		{},
		"live_room":
		{
			"roomStatus": 1,
			"liveStatus": 0,
			"url": "https://live.bilibili.com/XXXX",
			"title": "XXXX",
			"cover": "",
			"online": 0,
			"roomid": XXXX,
			"roundStatus": 0,
			"broadcast_type": 0
		},
		"birthday": "",
		"school":
		{
			"name": ""
		},
		"profession":
		{
			"name": ""
		},
		"tags": null,
		"series":
		{
			"user_upgrade_status": 3,
			"show_upgrade_window": false
		}
	}
}
```
