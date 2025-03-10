# 简介
根据干支和八字信息，查询神煞组合的算法。涵盖51种常用神煞。
使用方法参考方法注释：
```javascript
/**
 * 根据干支和八字信息，查询神煞组合。
 * @param String ganzhi 要查询神煞的某柱干支，例如要查询月柱为甲寅，则参数值为：甲寅
 * @param Array bazi 八字数组，数组元素从0-7，分别是年干、年支、月干、月支、日干、日支、时干、时支
 * @param boolean isman 性别，true为男，否则为女
 * @param int witch 查的是哪一柱，1，2，3，4分别代表年/月/日/时柱。其它分别是5大运，6流年，7流月，8流时。
 * @param String 年柱纳音,查询学堂、词馆神煞时用。例如：海中金
 * @returns Array 返回神煞数组
 */
function queryShenSha(ganzhi, bazi, isman, witch, niannayin) {
...

}
```
# 应用示例
本神煞算法已应用于吉时雨排盘软件：https://ji.js.cn

# 关于作者
xianbo.chen@gmail.com
本人将在丙午年公开[吉时雨排盘](https://ji.js.cn)全部源码，敬请关注。
