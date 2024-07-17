# 简介
根据干支和八字信息，查询神煞组合的算法。涵盖51种常用神煞。
使用方法参考方法注释：
```javascript
/**
 * 根据干支和八字信息，查询神煞组合。
 * @param String ganzhi 干支(柱)
 * @param Array bazi 八字数组，数组元素0-7，分别是年柱、月柱、日柱、时柱的干支
 * @param boolean isman 性别
 * @param int witch 哪一柱，1，2，3，4分别代表年/月/日/时柱。其它分别代表大运，流年，流月，流时。
 * @param String 年柱纳音
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
