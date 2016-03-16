1. getLastKnownLocation (String provider) 返回上一次的位置，如果provider没有打开，返回null
2. requestLocationUpdates (String provider, long minTime, float minDistance, LocationListener listener)更新位置
3. removeUpdates (LocationListener listener)移除监听
4. 在室内测试时，优先选用NETWORK_PROVIDER，室内GPS信号差