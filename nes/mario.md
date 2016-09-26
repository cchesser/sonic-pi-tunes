The initial tune of [Super Mario Brothers](https://en.wikipedia.org/wiki/Super_Mario_Bros.).
This was an initial example to learn [chiptunes](https://en.wikipedia.org/wiki/Chiptune) and
[MML](https://en.wikipedia.org/wiki/Music_Macro_Language). This is originally sourced from
the example shared [here](https://gist.github.com/xavriley/87ef7548039d1ee301bb).

```ruby
# cerner_2^5_2016
use_bpm 100
use_synth :pulse
use_synth_defaults release: 0.2, mod_rate: 5, amp: 0.6
play_pattern_timed([:e5, :e5, nil, :e5, nil, :c5, :e5, nil, :g5], [0.25])
```
