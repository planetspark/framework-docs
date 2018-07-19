# Events

```
window.EVENTS.push({
  event_name: _event_name,
  level_state: _current_level,
  success: _boolean,
  entered_value: _int,
  expected_value: _int
})
```

## Arguments 

  **There are several arguments possible** - 
  + *("game_start", 0, true, 0, 0)*
  + *("tutorial_start", 1, true, 0, 0)*
  + *("exit", 1, true, 0, 0)*
  + *("tutorial_end", 1, true, 0, 0)*
  + *("retry", 1, true, 0, 0)*
  + *("tutorial_skip", 1, true, 0, 0)*
  + *("level_start", 1, true, 0, 0)*
  + *("question_start", 1, true, 0, xyz)*
  + *("question_attempt", 1, false, abc, xyz)*
  + *("question_timeout", 1, false, abc, xyz)*
  + *("question_hint", 1, true, abc, xyz)*
  + *("level_end", 1, true, 0, 0)*
  + *("score_seen", 1, true, 0, 0)*
  + *("level_retry", 1, true, 0, 0)*
