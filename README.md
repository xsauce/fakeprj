FakePrj

功能：
1、建立一个本地数据库sqlite，app_db
2、从apk中解析中文名，包名，md5值，签名md5值（可选），版本，英文名
3、根据下载列表，下载正版的android app，解析其信息，存储到authorized_app(appid, app_name, app_zh_name, package_name, md5, version）
4、根据应用市场列表，下载应用市场中所有的android app，解析其信息，存储到sample_app(appid, app_name, app_zh_name, package_name, md5, version, market) 
5、从sample_app查找与一个正版app相似的app_zh_name的like_fake_apps
6、根据app的信息对比找出like_fake_apps中哪些是fake_app

