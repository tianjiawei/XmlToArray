# XmlToArray
curl获取xml数据并转换成array

代码功能：
1、通过CURL获取接口的XML数据，并把XML转换成数组的形式
2、为实现multi模式的并发

使用：
直接引入类
get_curl_xml方法：通过curl获取HTTPS协议下的需要验证的接口数据

toArray方法：传入xml字符串可以解析成多级数组
