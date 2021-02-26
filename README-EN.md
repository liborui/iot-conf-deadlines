## IoT-related Conference Deadlines

Countdown timers to keep track of a bunch of Network/Mobile/IoT/Edge_Computing conference deadlines.

中文版教程请移步 [这里](README.md).

## Contributing

Contributions are very welcome!

To keep things minimal, I'm only looking to list top-tier conferences in Network/Mobile/IoT/Edge_Computing as per [conferenceranks.com][6] and the CCF rank. Feel free to maintain a separate fork if you don't see your sub-field or conference of interest listed.

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
    + Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `conf_date`, `conf_start`, `conf_end`, `place`, `sub` attributes
      + You can find `sub` in `_data/types.yml`.
      + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `ccf`, `hindex`, `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
    + You can find the `hindex` data (h5 index) via [here](https://www.guide2research.com/topconf/).
- Send a pull request

## Forks & other useful listings


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