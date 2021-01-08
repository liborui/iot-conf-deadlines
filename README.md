## IoT-related Conference Deadlines

追踪网络、移动计算、物联网、边缘计算相关会议的deadline.

English version [see](README-EN.md).

## 如何添加一个新的会议deadline?

非常欢迎各位的更新！

更新方法：
- Fork这个仓库.
- 在自己的Fork里更新`_data/conferences.yml`.
    + 必填项：`title`（会议简称）, `year`（年份）, `id`（一般为小写）, `link`（会议主页链接）, `deadline`（截止日期）, `timezone`（截止日期的时区）, `conf_date`（会议日期，字符串）, `conf_start`（会议开始日期）, `conf_end`（会议结束日期）, `place`（字符串，在线会议填写Online）, `sub`（分类）.
      + `sub`可以从`_data/types.yml`找到.
      + `timezone`可以填写如`UTC+10`或`America/New_York`格式, 具体参见[这里](https://momentjs.com/timezone/).
    + 选填项：`ccf`（会议CCF级别）, `note`（备注）, `abstract_deadline`（如有）, `hindex`（会议的h5-index）.
      + 会议的`hindex`可以在[这里](https://www.guide2research.com/topconf/)找到.
- 发送一个pull request.
    + [Pull request教程](https://blog.csdn.net/potato_prince/article/details/89305084).
    + [github fork 别人的项目源作者更新后如何同步更新](https://blog.csdn.net/zhongzunfa/article/details/80344585).
## 致谢

- [geodeadlin.es][3] by @LukasMosser
- [neuro-deadlines][4] by @tbryn
- [ai-challenge-deadlines][5] by @dieg0as
- [CV-oriented ai-deadlines (with an emphasis on medical images)][8] by @duducheng
- [es-deadlines (Embedded Systems, Computer Architecture, and Cyber-physical Systems)][9] by @AlexVonB and @k0nze
- [2019-2020 International Conferences in AI, CV, DM, NLP and Robotics][10] by @JackieTseng
- [aideadlin.es][11] by @abhshkdz
## License

[MIT][1]

[1]: https://abhshkdz.mit-license.org/
[2]: http://aideadlin.es/
[3]: https://github.com/LukasMosser/geo-deadlines
[4]: https://github.com/tbryn/neuro-deadlines
[5]: https://github.com/dieg0as/ai-challenge-deadlines
[6]: http://www.conferenceranks.com/#
[8]: https://creedai.github.io/ai-deadlines/
[9]: https://ekut-es.github.io/es-deadlines/
[10]: https://jackietseng.github.io/conference_call_for_paper/conferences.html
[11]: https://github.com/abhshkdz/ai-deadlines